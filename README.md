
 

       


  $.getScript("https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js", function() {
    $.getScript("https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js", function() {
      gsap.registerPlugin(ScrollTrigger); 


/* ─────────────────────────────────────────
   GSAP Scroll Animations — Full Page
   Requires: gsap.min.js + ScrollTrigger.min.js
   (already loaded in your page)
───────────────────────────────────────── */

gsap.registerPlugin(ScrollTrigger);

/* ─── Helpers ─── */
const isMobile = () => window.innerWidth < 768;

function revealFrom(targets, from, extra = {}) {
  return gsap.from(targets, {
    scrollTrigger: {
      trigger: targets[0] || targets,
      start: "top 88%",
      toggleActions: "play none none none",
    },
    duration: 0.85,
    ease: "power3.out",
    ...from,
    ...extra,
  });
}


/* ══════════════════════════════════════════
   1 · HEADER SECTION
══════════════════════════════════════════ */

const tl_header = gsap.timeline({ defaults: { ease: "power3.out" } });

tl_header
  .from(".headerSection h1", {
    y: -80,
    opacity: 0,
    rotate: isMobile() ? 0 : -20,
    duration: 1,
    delay: 0.2,
  })
  .from(
    ".headerSection .arrowImg",
    { x: 60, opacity: 0, duration: 0.7 },
    "-=0.4"
  )
  .from(
    ".headerContent .orderBtn",
    { y: 30, opacity: 0, scale: 0.85, duration: 0.6 },
    "-=0.3"
  )
  .from(
    ".headerImg img",
    {
      y: 60,
      opacity: 0,
      rotate: isMobile() ? 0 : -15,
      scale: 0.9,
      duration: 1,
    },
    "-=0.5"
  );


/* ══════════════════════════════════════════
   2 · PAYMENT / STEP CARDS
══════════════════════════════════════════ */

/* Stagger cards in from below — override the CSS animation */
gsap.set(".step-card", { opacity: 1, y: 0 }); /* cancel CSS anim */

gsap.from(".step-card", {
  scrollTrigger: {
    trigger: ".paymentSection",
    start: "top 80%",
    toggleActions: "play none none none",
  },
  y: 70,
  opacity: 0,
  duration: 0.9,
  stagger: 0.18,
  ease: "back.out(1.4)",
});

/* Number counter ping */
document.querySelectorAll(".step-num").forEach((el) => {
  gsap.from(el, {
    scrollTrigger: {
      trigger: el,
      start: "top 85%",
    },
    scale: 0,
    rotate: -45,
    opacity: 0,
    duration: 0.55,
    ease: "back.out(2)",
  });
});

/* Icon circles bounce-in */
gsap.from(".step-icon-wrap", {
  scrollTrigger: {
    trigger: ".paymentSection",
    start: "top 78%",
  },
  scale: 0,
  opacity: 0,
  duration: 0.6,
  stagger: 0.18,
  delay: 0.35,
  ease: "elastic.out(1, 0.5)",
});


/* ══════════════════════════════════════════
   3 · ABOUT SECTION
══════════════════════════════════════════ */

/* Heading: slide up word by word feel */
gsap.from(".aboutSection h2", {
  scrollTrigger: {
    trigger: ".aboutSection h2",
    start: "top 85%",
  },
  y: 60,
  opacity: 0,
  duration: 1,
  ease: "power4.out",
});

/* Paragraph fade + slide */
gsap.from(".aboutContent p", {
  scrollTrigger: {
    trigger: ".aboutContent p",
    start: "top 88%",
  },
  y: 40,
  opacity: 0,
  duration: 0.8,
  ease: "power2.out",
  delay: 0.2,
});

/* About CTA button */
gsap.from(".aboutContent .orderBtn", {
  scrollTrigger: {
    trigger: ".aboutContent .orderBtn",
    start: "top 92%",
  },
  y: 30,
  opacity: 0,
  scale: 0.8,
  duration: 0.7,
  ease: "back.out(1.7)",
});

/* Masked image: reveal with clip */
gsap.from(".mask", {
  scrollTrigger: {
    trigger: ".mask",
    start: "top 85%",
  },
  x: 80,
  opacity: 0,
  duration: 1.1,
  ease: "power3.out",
});

/* Parallax on about image while scrolling */
gsap.to(".mask img", {
  scrollTrigger: {
    trigger: ".aboutSection",
    start: "top bottom",
    end: "bottom top",
    scrub: 1.5,
  },
  y: -40,
});


/* ══════════════════════════════════════════
   4 · BANNER SECTION
══════════════════════════════════════════ */

/* Wraps image: scale up from bottom */
gsap.from(".wrapsImg", {
  scrollTrigger: {
    trigger: ".bannerSection",
    start: "top 80%",
  },
  y: 80,
  opacity: 0,
  scale: 0.85,
  duration: 1.2,
  ease: "power4.out",
});

/* Heading lines stagger */
const bannerH2Lines = gsap.utils.toArray(
  ".bannerSection h2 .spanOne, .bannerSection h2 .spanTwo, .bannerSection h2 .spanThree"
);

gsap.from(bannerH2Lines, {
  scrollTrigger: {
    trigger: ".bannerSection h2",
    start: "top 85%",
  },
  y: 40,
  opacity: 0,
  duration: 0.7,
  stagger: 0.12,
  ease: "power3.out",
});

/* Paragraph slide from right */
gsap.from(".rightTxtContent p", {
  scrollTrigger: {
    trigger: ".rightTxtContent p",
    start: "top 88%",
  },
  x: 50,
  opacity: 0,
  duration: 0.85,
  ease: "power2.out",
  delay: 0.3,
});

/* Subtle parallax on the yellow bar */
gsap.to(".bannerRow::after", {
  scrollTrigger: {
    trigger: ".bannerSection",
    start: "top bottom",
    end: "bottom top",
    scrub: 2,
  },
  y: -20,
});


/* ══════════════════════════════════════════
   5 · MENU SECTION
══════════════════════════════════════════ */

/* Floating deco images — drift in from edges */
gsap.from(".manImg", {
  scrollTrigger: {
    trigger: ".menuSection",
    start: "top 80%",
  },
  x: -100,
  opacity: 0,
  duration: 1.2,
  ease: "power3.out",
});

gsap.from(".friesImg", {
  scrollTrigger: {
    trigger: ".menuSection",
    start: "top 80%",
  },
  x: 120,
  rotate: 30,
  opacity: 0,
  duration: 1.2,
  ease: "power3.out",
});

/* Slow floating loop on deco images (after entry) */
ScrollTrigger.create({
  trigger: ".menuSection",
  start: "top 80%",
  onEnter() {
    gsap.to(".manImg", {
      y: -18,
      duration: 2.5,
      ease: "sine.inOut",
      yoyo: true,
      repeat: -1,
    });
    gsap.to(".friesImg", {
      y: 18,
      duration: 3,
      ease: "sine.inOut",
      yoyo: true,
      repeat: -1,
      delay: 0.5,
    });
  },
});

/* Heading — character-by-character feel via split words */
gsap.from(".menuSection h2", {
  scrollTrigger: {
    trigger: ".menuSection h2",
    start: "top 88%",
  },
  y: 50,
  opacity: 0,
  duration: 1,
  ease: "power4.out",
});

/* Gallery images — staggered cascade */
const galleryImgs = gsap.utils.toArray(".galleryParent img");

gsap.from(galleryImgs, {
  scrollTrigger: {
    trigger: ".galleryGrid",
    start: "top 85%",
    toggleActions: "play none none none",
  },
  scale: 0.82,
  opacity: 0,
  y: 50,
  duration: 0.85,
  stagger: {
    amount: 0.5,
    from: "start",
  },
  ease: "power3.out",
});

/* Subtle parallax scrub on gallery images while scrolling */
galleryImgs.forEach((img) => {
  gsap.to(img, {
    scrollTrigger: {
      trigger: img,
      start: "top bottom",
      end: "bottom top",
      scrub: 1.2,
    },
    y: -25,
  });
});


/* ══════════════════════════════════════════
   6 · GLOBAL — ALL ORDER BUTTONS
══════════════════════════════════════════ */

document.querySelectorAll(".orderBtn").forEach((btn) => {
  btn.addEventListener("mouseenter", () => {
    gsap.to(btn, { scale: 1.06, duration: 0.25, ease: "power2.out" });
  });
  btn.addEventListener("mouseleave", () => {
    gsap.to(btn, { scale: 1, duration: 0.3, ease: "power2.inOut" });
  });
});


/* ══════════════════════════════════════════
   7 · RESPONSIVE — RECALCULATE ON RESIZE
══════════════════════════════════════════ */

let resizeTimer;
window.addEventListener("resize", () => {
  clearTimeout(resizeTimer);
  resizeTimer = setTimeout(() => {
    ScrollTrigger.refresh();
  }, 250);
});

  

    });
  }); 
 


 
     
    



