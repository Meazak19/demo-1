$.getScript("https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js", function () {
  $.getScript("https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js", function () {
    $.getScript("https://cdn.jsdelivr.net/npm/lenis@1.1.14/dist/lenis.min.js", function () {

      gsap.registerPlugin(ScrollTrigger);

      /* ══════════════════════════════════════════
         LENIS SMOOTH SCROLL
      ══════════════════════════════════════════ */

      const lenis = new Lenis({
        duration          : 1.4,
        easing            : (t) => Math.min(1, 1.001 - Math.pow(2, -10 * t)),
        orientation       : "vertical",
        gestureOrientation: "vertical",
        smoothWheel       : true,
        smoothTouch       : false,
        touchMultiplier   : 2,
        wheelMultiplier   : 1,
        infinite          : false,
      });

      gsap.ticker.add((time) => lenis.raf(time * 1000));
      gsap.ticker.lagSmoothing(0);
      lenis.on("scroll", ScrollTrigger.update);

      ScrollTrigger.scrollerProxy(document.body, {
        scrollTop(value) {
          if (arguments.length) lenis.scrollTo(value, { immediate: true });
          return lenis.scroll;
        },
        getBoundingClientRect() {
          return { top: 0, left: 0, width: window.innerWidth, height: window.innerHeight };
        },
      });

      ScrollTrigger.addEventListener("refresh", () => lenis.resize());
      ScrollTrigger.refresh();

      document.querySelectorAll('a[href^="#"]').forEach((anchor) => {
        anchor.addEventListener("click", (e) => {
          e.preventDefault();
          const target = document.querySelector(anchor.getAttribute("href"));
          if (target) lenis.scrollTo(target, { offset: -80, duration: 1.6 });
        });
      });

      window.lenisStop  = () => lenis.stop();
      window.lenisStart = () => lenis.start();


      /* ══════════════════════════════════════════
         SHARED CONFIG
      ══════════════════════════════════════════ */

      const TOGGLE   = "restart none none reset";
      const isMobile = () => window.innerWidth < 768;


      /* ══════════════════════════════════════════
         1 · HEADER
      ══════════════════════════════════════════ */

      const tl_header = gsap.timeline({
        defaults: { ease: "power3.out" },
        scrollTrigger: {
          trigger: ".headerSection",
          start: "top 85%",
          toggleActions: TOGGLE,
        },
      });

      tl_header
        .from(".headerSection h1", {
          y: -80, opacity: 0,
          rotate: isMobile() ? 0 : -20,
          duration: 1, delay: 0.2,
        })
        .from(".headerSection .arrowImg",
          { x: 60, opacity: 0, duration: 0.7 }, "-=0.4")
        .from(".headerContent .orderBtn",
          { y: 30, opacity: 0, scale: 0.85, duration: 0.6 }, "-=0.3")
        .from(".headerImg img", {
          y: 60, opacity: 0,
          rotate: isMobile() ? 0 : -15,
          scale: 0.9, duration: 1,
        }, "-=0.5");


      /* ══════════════════════════════════════════
         HERO IMAGE → STEP CARD 1  (scroll fly)
         
         As the user scrolls down, a clone of the 
         big header food image flies and shrinks 
         into step card 1's position.
      ══════════════════════════════════════════ */

      const heroImg = document.querySelector(".headerImg img");
      const cards   = document.querySelectorAll(".step-card");
      const card1   = cards[0];

      /* Create a fixed clone that travels across the screen */
      const flyImg = heroImg.cloneNode(true);
      Object.assign(flyImg.style, {
        position      : "fixed",
        top           : "0",
        left          : "0",
        margin        : "0",
        pointerEvents : "none",
        zIndex        : "9998",
        transformOrigin: "top left",
        willChange    : "transform, width, height, opacity",
        objectFit     : "contain",
        borderRadius  : "0px",
        opacity       : "0",
      });
      document.body.appendChild(flyImg);

      /* Store hero rect once (before scroll moves the section) */
      let heroRect = heroImg.getBoundingClientRect();

      /* Re-capture on resize */
      window.addEventListener("resize", () => {
        setTimeout(() => { heroRect = heroImg.getBoundingClientRect(); }, 260);
      });

      

      ScrollTrigger.create({
        trigger : ".paymentSection",
        start   : "top 96%",   /* clone appears just as cards enter view */
        end     : "top 35%",   /* clone lands on card 1 */
        scrub   : 1.5,

        onEnter() {

  // Hide original immediately
  gsap.set(heroImg, {
    autoAlpha: 0
  });

  // Show clone exactly at same position
  gsap.set(flyImg, {
    x: heroRect.left,
    y: heroRect.top,
    width: heroRect.width,
    height: heroRect.height,
    opacity: 1,
    borderRadius: "0px"
  });
},

      onLeaveBack() {

  // Restore original only when scrolling back to top
  gsap.set(heroImg, {
    autoAlpha: 1
  });

  gsap.set(flyImg, {
    opacity: 0
  });
},
      onLeave() {

  // Keep original hidden
  gsap.set(heroImg, {
    autoAlpha: 0
  });

  // Hide flying clone after landing
  gsap.set(flyImg, {
    opacity: 0
  });
},

        onUpdate(self) {
          const p  = self.progress;               /* 0 → 1 as you scroll */
          const cr = card1.getBoundingClientRect(); /* live card position */
          const hr = heroRect;

          const lerp = (a, b, t) => a + (b - a) * t;

          /* Ease the progress for a snappier landing */
          const ep = gsap.parseEase("power2.inOut")(p);

          gsap.set(flyImg, {
            x           : lerp(hr.left,   cr.left,   ep),
            y           : lerp(hr.top,    cr.top,    ep),
            width       : lerp(hr.width,  cr.width,  ep),
            height      : lerp(hr.height, cr.height, ep),
            borderRadius: lerp(0, 18, ep) + "px",
            /* fade in fast, fade out gently as it lands */
            opacity    : 1,
          });
        },
      });

      gsap.to(".wave-letter", {
  y: -12,
  rotation: 2,
  duration: 0.5,
  ease: "sine.inOut",

  stagger: {
    each: 0.03,
    repeat: -1,
    yoyo: true
  },

  force3D: true
});
 



      /* ══════════════════════════════════════════
         2 · PAYMENT / STEP CARDS (unique per card)
      ══════════════════════════════════════════ */

      gsap.set(".step-card", { opacity: 1, y: 0 });

      /* Card 1 — slide from LEFT + rotateY */
      gsap.from(cards[0], {
        scrollTrigger: { trigger: cards[0], start: "top 80%", toggleActions: TOGGLE },
        x: -150, opacity: 0, rotateY: -45, duration: 1.5, ease: "power3.out",
      });

      /* Card 2 — drop from TOP + scale bounce */
      gsap.from(cards[1], {
        scrollTrigger: { trigger: cards[1], start: "top 82%", toggleActions: TOGGLE },
        y: -120, opacity: 0, scale: 0.6, duration: 1, ease: "back.out(1.8)", delay: 0.12,
      });

      /* Card 3 — slide from RIGHT + rotateY */
      gsap.from(cards[2], {
        scrollTrigger: { trigger: cards[2], start: "top 82%", toggleActions: TOGGLE },
        x: 150, opacity: 0, rotateY: 45, duration: 0.9, ease: "power3.out", delay: 0.24,
      });

      /* Step numbers — each spins from a different angle */
      document.querySelectorAll(".step-num").forEach((el, i) => {
        gsap.from(el, {
          scrollTrigger: { trigger: el, start: "top 85%", toggleActions: TOGGLE },
          scale: 0, opacity: 0, duration: 0.6, delay: i * 0.12, ease: "back.out(2.5)",
          rotate: i === 0 ? -90 : i === 1 ? 180 : 90,
        });
      });

      /* Icon circles — different ease per card */
      const iconEases = ["elastic.out(1, 0.4)", "bounce.out", "elastic.out(1.2, 0.3)"];
      document.querySelectorAll(".step-icon-wrap").forEach((el, i) => {
        gsap.from(el, {
          scrollTrigger: { trigger: el, start: "top 85%", toggleActions: TOGGLE },
          scale: 0, opacity: 0, duration: 0.75, delay: 0.3 + i * 0.1, ease: iconEases[i],
        });
      });

      /* Title + desc fade up inside each card */
      cards.forEach((card, i) => {
        gsap.from([card.querySelector(".step-title"), card.querySelector(".step-desc")], {
          scrollTrigger: { trigger: card, start: "top 82%", toggleActions: TOGGLE },
          y: 20, opacity: 0, duration: 0.55, stagger: 0.1,
          delay: 0.5 + i * 0.12, ease: "power2.out",
        });
      });


      /* ══════════════════════════════════════════
         3 · ABOUT
      ══════════════════════════════════════════ */

      gsap.from(".aboutSection h2", {
        scrollTrigger: { trigger: ".aboutSection h2", start: "top 85%", toggleActions: TOGGLE },
        y: 60, opacity: 0, duration: 1, ease: "power4.out",
      });
      gsap.from(".aboutContent p", {
        scrollTrigger: { trigger: ".aboutContent p", start: "top 88%", toggleActions: TOGGLE },
        y: 40, opacity: 0, duration: 0.8, ease: "power2.out", delay: 0.2,
      });
      gsap.from(".aboutContent .orderBtn", {
        scrollTrigger: { trigger: ".aboutContent .orderBtn", start: "top 92%", toggleActions: TOGGLE },
        y: 30, opacity: 0, scale: 0.8, duration: 0.7, ease: "back.out(1.7)",
      });
      gsap.from(".mask", {
        scrollTrigger: { trigger: ".mask", start: "top 85%", toggleActions: TOGGLE },
        x: 80, opacity: 0, duration: 1.1, ease: "power3.out",
      });
      gsap.to(".mask img", {
        scrollTrigger: { trigger: ".aboutSection", start: "top bottom", end: "bottom top", scrub: 1.5 },
        y: -40,
      });


      /* ══════════════════════════════════════════
         4 · BANNER
      ══════════════════════════════════════════ */

      gsap.from(".wrapsImg", {
        scrollTrigger: { trigger: ".bannerSection", start: "top 80%", toggleActions: TOGGLE },
        y: 80, opacity: 0, scale: 0.85, duration: 1.2, ease: "power4.out",
      });

      const bannerH2Lines = gsap.utils.toArray(
        ".bannerSection h2 .spanOne, .bannerSection h2 .spanTwo, .bannerSection h2 .spanThree"
      );
      gsap.from(bannerH2Lines, {
        scrollTrigger: { trigger: ".bannerSection h2", start: "top 85%", toggleActions: TOGGLE },
        y: 40, opacity: 0, duration: 0.7, stagger: 0.12, ease: "power3.out",
      });
      gsap.from(".rightTxtContent p", {
        scrollTrigger: { trigger: ".rightTxtContent p", start: "top 88%", toggleActions: TOGGLE },
        x: 50, opacity: 0, duration: 0.85, ease: "power2.out", delay: 0.3,
      });


      /* ══════════════════════════════════════════
         5 · MENU
      ══════════════════════════════════════════ */

      gsap.from(".manImg", {
        scrollTrigger: { trigger: ".menuSection", start: "top 80%", toggleActions: TOGGLE },
        x: -100, opacity: 0, duration: 1.2, ease: "power3.out",
      });
      gsap.from(".friesImg", {
        scrollTrigger: { trigger: ".menuSection", start: "top 80%", toggleActions: TOGGLE },
        x: 120, rotate: 30, opacity: 0, duration: 1.2, ease: "power3.out",
      });

      ScrollTrigger.create({
        trigger: ".menuSection", start: "top 80%", once: true,
        onEnter() {
          gsap.to(".manImg",  { y: -18, duration: 2.5, ease: "sine.inOut", yoyo: true, repeat: -1 });
          gsap.to(".friesImg",{ y:  18, duration:   3, ease: "sine.inOut", yoyo: true, repeat: -1, delay: 0.5 });
        },
      });

      gsap.from(".menuSection h2", {
        scrollTrigger: { trigger: ".menuSection h2", start: "top 88%", toggleActions: TOGGLE },
        y: 50, opacity: 0, duration: 1, ease: "power4.out",
      });

      const galleryImgs = gsap.utils.toArray(".galleryParent img");
      gsap.from(galleryImgs, {
        scrollTrigger: { trigger: ".galleryGrid", start: "top 85%", toggleActions: TOGGLE },
        scale: 0.82, opacity: 0, y: 50, duration: 0.85,
        stagger: { amount: 0.5, from: "start" }, ease: "power3.out",
      });
      galleryImgs.forEach((img) => {
        gsap.to(img, {
          scrollTrigger: { trigger: img, start: "top bottom", end: "bottom top", scrub: 1.2 },
          y: -25,
        });
      });


      /* ══════════════════════════════════════════
         6 · ORDER BUTTON HOVER
      ══════════════════════════════════════════ */

      document.querySelectorAll(".orderBtn").forEach((btn) => {
        btn.addEventListener("mouseenter", () =>
          gsap.to(btn, { scale: 1.06, duration: 0.25, ease: "power2.out" }));
        btn.addEventListener("mouseleave", () =>
          gsap.to(btn, { scale: 1,    duration: 0.3,  ease: "power2.inOut" }));
      });


      /* ══════════════════════════════════════════
         7 · RESPONSIVE
      ══════════════════════════════════════════ */

      let resizeTimer;
      window.addEventListener("resize", () => {
        clearTimeout(resizeTimer);
        resizeTimer = setTimeout(() => {
          lenis.resize();
          ScrollTrigger.refresh();
        }, 250);
      });

    }); /* end Lenis.getScript */
  }); /* end ScrollTrigger.getScript */
}); /* end gsap.getScript */
