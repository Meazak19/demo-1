<style type="text/css">


  /* 
  
  font-family: "Inter", sans-serif;
  
  font-family: "Poppins", sans-serif;

  font-family: "Agbalumo", system-ui; 
  
  */  
  
      body .page-wrapper { 
      font-family: "Poppins", sans-serif; 
      color: #6c6a6a; 
      line-height: 24px; 
      overflow-x: hidden; 
      scroll-behavior: smooth; 
      background: #f7a72d;
      overflow: hidden; 
      background: radial-gradient(circle, rgb(253 243 231) 0%, rgb(247 167 45) 70%);
      } 
      
     .page-wrapper p {
      margin-bottom: 25px;
      font-size: 22px;
      font-family: "Poppins", sans-serif;
      color: #000;
      letter-spacing: 2px;
      line-height: 1.5;
      font-weight: 500;
     }
  
     .page-wrapper p > a {
     color: inherit;
     }
     .page-wrapper h1, .page-wrapper h2, .page-wrapper h3, .page-wrapper h4, .page-wrapper h5, .page-wrapper h6 {
     line-height: 1.3;
     font-family: "Inter", sans-serif;
     }
     .page-wrapper .row {
     margin: 0 -15px!important;
     }
     .page-wrapper .bg-dark {
     background-color: #fc673f!important;
     }
  
     .page-wrapper .bg-primary {
     background-color: #241e5e!important;
     }
     .page-wrapper .bg-light {
     background-color: #f1f1f1!important;
     }
     .page-wrapper section {
     position: relative;
     z-index: 1;
     background-size: cover;
     background-position: center center;
     background-repeat: no-repeat;
     }   
     .page-wrapper .btn {
     font-size: 14px;
     border-radius: 0;
     padding: 0 30px;
     line-height: 50px;
     }  
  
     .page-wrapper .overlay{
        content: "";
      background: rgb(0 0 0 / 58%);
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      z-index: -1;
     }
  
     .page-wrapper h1 {
      font-size: 75px;
      text-transform: uppercase;
      color: #971b1e;
      font-weight: 700;
     }
     .page-wrapper h2 {
      font-size: 60px;
      text-transform: capitalize;
      font-weight: 700;
      color: #97021f;
     }
     .page-wrapper h3 {
              color: #fff;
      font-size: 50px;
      font-weight: 700;
      }
     .page-wrapper h4 {
      
     }
     .page-wrapper h5 {
      
     }
     .page-wrapper h6 {
      
     }
  
         /* ── THUMBNAILS ── */
      page-wrapper .thumbnails {
          display: flex;
      gap: 30px;
      margin-top: 100px;
      align-items: flex-end;
      opacity: 0;
      animation: fadeUp .7s .55s cubic-bezier(.22, 1, .36, 1) forwards;
      }
  
     .page-wrapper  .thumb {
          width: 225px;
          height: 225px;
        border-radius: 20px; 
        border: 3px solid rgba(255, 255, 255, 0);
        cursor: pointer;
        transition: transform .25s, border-color .25s, box-shadow .25s;
        position: relative; 
      }
     .page-wrapper  .thumb img {
        width: 100%; height: 100%;
        object-fit: cover;
        display: block;
        transition: transform .35s;
        border-radius: 20px; 
      }
     .page-wrapper  .thumb:hover { transform: translateY(-6px) scale(1.05); border-color: #fff; box-shadow: 0 12px 28px rgba(0,0,0,.35); }
     .page-wrapper  .thumb:hover img { transform: scale(1.08); }
     .page-wrapper  .thumb.active {
        border-color: #fff;
        transform: translateY(-10px) scale(1.08);
        /* box-shadow: 0 14px 32px rgba(0,0,0,.4); */
      }
  
     .page-wrapper  .cart-badge {
        display: none;
        position: absolute;
        inset: 0;
        background: rgba(0,0,0,.38);
        align-items: center;
        justify-content: center;
        border-radius: 20px;
      }
     .page-wrapper  .thumb.active .cart-badge {     display: flex;
          transform: scale(1.08); }
     .page-wrapper  .cart-badge svg { width: 36px; height: 36px; filter: drop-shadow(0 2px 4px rgba(0,0,0,.5)); }
     .page-wrapper  .thumb.active img{
          transform: scale(1.08);
      }
  
      /* ── ARROW ── */
    .page-wrapper   .thumb-arrow {
          position: absolute;
      width: 0;
      height: 0;
      top: -60px;
      left: 0;
      right: 0;
      margin: auto;
      border-left: 25px solid transparent;
      border-right: 25px solid transparent;
      border-top: 25px solid rgba(255, 255, 255, .85);
      transition: left .35s cubic-bezier(.22, 1, .36, 1);
      z-index: 3;
      animation: fadeUp .5s .8s forwards;
      opacity: 0 !important; 
      }
  
     .page-wrapper  .thumb.active .thumb-arrow{ 
          opacity: 1 !important;
      transition: left .35s cubic-bezier(.22, 1, .36, 1); 
  
      }
  
      @keyframes slideIn {
        to { opacity: 1; transform: translateX(0); }
      }
      @keyframes fadeUp {
        from { opacity: 0; transform: translateY(18px); }
        to   { opacity: 1; transform: translateY(0); }
      }
      @keyframes heroReveal {
        from { opacity: 0; clip-path: inset(0 100% 0 0); }
        to   { opacity: 1; clip-path: inset(0 0% 0 0); }
      }
  
      /* ── RIGHT HERO ── */
     .page-wrapper  .hero-img {  
        overflow: hidden;
        border-radius: 50px 0 0 50px;
        opacity: 0;
        animation: heroReveal .9s .2s cubic-bezier(.22,1,.36,1) forwards;
      }
     .page-wrapper  .hero-img img {
        width: 100%; height: 100%;
        object-fit: cover;
        transition: transform 8s ease, opacity .3s;
      }
      .hero-img:hover img { transform: scale(1.04); }
      
      .page-wrapper .hero-img img {
          width: 100%;
      height: 750px;
      object-fit: cover;
      }
      .page-wrapper .headerContent {
          padding-left: 80px;
      }
     .page-wrapper  .hero-img img {
          width: 100%;
      height: 750px;
      object-fit: cover;
      }
      .page-wrapper h1 span{ 
          color: #fff;
      } 

      /* HOVER */

      .page-wrapper .orderBtn {
  position: relative; 
  cursor: pointer; 
  transition: all 0.2s ease;
  color: #ffffff;
      background: #e52e0e;
          border: 2px solid #f36a16;
      display: inline-block;
      padding: 15px 35px;
      font-size: 25px;
      border-radius: 25px;
      font-weight: 600;
      text-transform: uppercase;
}

.page-wrapper .orderBtn:active {
  transform: scale(0.95);
}

.page-wrapper .orderBtn:before,
.page-wrapper .orderBtn:after {
  position: absolute;
  content: "";
  width: 150%;
  left: 50%;
  height: 100%;
  transform: translateX(-50%);
  z-index: -1000;
  background-repeat: no-repeat; 
}

.page-wrapper .orderBtn:hover:before {
  top: -70%;
  background-image: radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, transparent 20%, #ff7f50 20%, transparent 30%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, transparent 10%, #ff7f50 15%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%);
  background-size: 10% 10%, 20% 20%, 15% 15%, 20% 20%, 18% 18%, 10% 10%, 15% 15%,
    10% 10%, 18% 18%;
  background-position: 50% 120%;
  animation: orangeTopBubbles 0.6s ease; 
}
.page-wrapper .orderBtn.two:hover:before { 
    background-image: radial-gradient(circle, #000000 20%, transparent 20%),
    radial-gradient(circle, transparent 20%, #ffffff 20%, transparent 30%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, transparent 10%, #ffffff 15%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%);
}

@keyframes orangeTopBubbles {
  0% {
    background-position: 5% 90%, 10% 90%, 10% 90%, 15% 90%, 25% 90%, 25% 90%,
      40% 90%, 55% 90%, 70% 90%;
  }

  50% {
    background-position: 0% 80%, 0% 20%, 10% 40%, 20% 0%, 30% 30%, 22% 50%,
      50% 50%, 65% 20%, 90% 30%;
  }

  100% {
    background-position: 0% 70%, 0% 10%, 10% 30%, 20% -10%, 30% 20%, 22% 40%,
      50% 40%, 65% 10%, 90% 20%;
    background-size: 0% 0%, 0% 0%, 0% 0%, 0% 0%, 0% 0%, 0% 0%;
  }
}

.page-wrapper .orderBtn:hover::after {
  bottom: -70%;
  background-image: radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, transparent 10%, #ff7f50 15%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%),
    radial-gradient(circle, #ff7f50 20%, transparent 20%);
  background-size: 15% 15%, 20% 20%, 18% 18%, 20% 20%, 15% 15%, 20% 20%, 18% 18%;
  background-position: 50% 0%;
  animation: orangeBottomBubbles 0.6s ease; 
}
.page-wrapper .orderBtn.two:hover::after { 
    background-image: radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, transparent 10%, #ffffff 15%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%),
    radial-gradient(circle, #ffffff 20%, transparent 20%);
}

@keyframes orangeBottomBubbles {
  0% {
    background-position: 10% -10%, 30% 10%, 55% -10%, 70% -10%, 85% -10%,
      70% -10%, 70% 0%;
  }

  50% {
    background-position: 0% 80%, 20% 80%, 45% 60%, 60% 100%, 75% 70%, 95% 60%,
      105% 0%;
  }

  100% {
    background-position: 0% 90%, 20% 90%, 45% 70%, 60% 110%, 75% 80%, 95% 70%,
      110% 10%;
    background-size: 0% 0%, 0% 0%, 0% 0%, 0% 0%, 0% 0%, 0% 0%;
  }
}

      /* HOVER */
      .page-wrapper .headerSection {
          padding: 100px 0 0;
      }
      .page-wrapper .aboutImg {
          background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1772646786phpv5Y5bO.png');
          background-size: cover;
          min-height: 45vh;
              height: calc(100% + 50px);
              margin-top: -50px;
          border-radius: 0 250px 250px 0;
              z-index: -2;
      position: relative;
      background-position: center;
      }
      .page-wrapper .aboutSection {
          padding: 150px 0 100px;
      }
      .page-wrapper .aboutContent {
          padding-right: 100px;
      }
      .page-wrapper .aboutContent h2 span{ 
        color: #db7c26;
      }
      .page-wrapper .aboutContent h2:after {
        content: '';
        position: absolute;
        background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1773057347php8fYuEy.png');
        background-size: cover;
        width: 100%;
        height: 150px;
        background-repeat: no-repeat;
        top: 0px;
        left: 0%;
        z-index: -1;
        transform: scale(1.5);
      }
      .page-wrapper .aboutContent h2 {
        position: relative;
        left: -50px;
        margin-bottom: 50px;
      }
      .page-wrapper .serviseContainer {
              background: #bc2824;
                  background: linear-gradient(0deg, rgb(133 8 26) 0%, rgb(188 40 36) 100%);
      padding: 50px 20px;
      border-radius: 40px;
      text-align: center;
      height: 420px;
      }
      .page-wrapper .serviseContainer p{ 
          color: #fff;
      }
      .page-wrapper .innerContent {
          max-width: 500px;
      }
      .page-wrapper .aboutContent.two {
              padding-left: 100px;
      padding-right: 0;
      }
      .page-wrapper .aboutContent.two h2 {
              left: 100px; 
      }
      .page-wrapper .aboutContent.two h2:after {
              transform: scale(1.5) rotateY(180deg);
              left: -10%;
      }
      .page-wrapper .aboutImg.two {
          border-radius: 250px 0 0 250px;
      }
     .page-wrapper .footerSection {
    padding: 180px 0 100px;
}
      .page-wrapper .footerContent {
              padding: 150px 100px 25px;
      background: #f60730;
      border-radius: 50px;
      text-align: center;
      position: relative;
      }
      .page-wrapper .footerContent h2 {
              font-size: 100px;
      color: #fff;
      text-align: center;
      line-height: 1.2;
      margin-bottom: 15px;
      font-family: "Poppins", sans-serif;
      }
      .page-wrapper .footerContent h2.strokeTxt { 
          -webkit-text-stroke: 2px #ffffff;
          color: transparent;
          z-index: 1;
          position: absolute;
          top: 0;
          width: 100%;
          font-family: "Poppins", sans-serif;
      }
      .page-wrapper .footerHead {
          position: relative;
      }
      .page-wrapper .footerImgLeft {
        position: absolute;
    width: 450px;
    transform: scale(1.5);
    bottom: -50px;
    left: 0px;
    transform-origin: bottom right;
    filter: drop-shadow(0px 10px 10px #0000006e);
      }
      .page-wrapper .footerImgRight {
        position: absolute;
    right: 0;
    width: 450px;
    transform: scale(1.5);
    bottom: 25px;
    transform-origin: bottom left;
      }
      .page-wrapper .footerContent .orderBtn { 
          color: #e52e0e;
      background: #fff;
      position: relative;
      z-index: 1;
      }
      .page-wrapper .paraSpacing {
        max-width: 75%;
        margin-right: auto;
      }
      .page-wrapper .paraSpacing.two { 
        margin-left: auto;
        margin-right: unset;
      }
      .page-wrapper .tastySection {
        padding: 50px 0 100px;
      }
      .page-wrapper .hotChocolateImg {
position: absolute;
    width: 26%;
    right: 0;
    transform: scale(1.4);
    transform-origin: center;
    top: 16%;
    z-index: 1;
      }
      .page-wrapper .footerTopImg {
        position: absolute;
    left: 0;
    right: 0;
    margin: auto;
    width: 550px;
    transform: scale(1.4);
    top: -100px;
    transform-origin: bottom;
    z-index: 1;
    filter: drop-shadow(0px 10px 10px #0000006e);
      }
      .page-wrapper .sandwich {
        font-family: "Inter", sans-serif;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    font-size: 240px;
    text-transform: uppercase;
    font-weight: 900;
    line-height: 1;
    color: #fb859b;
      }
      .page-wrapper .sandwich.two {
    top: 32%;
    opacity: 0.5;
}
      .page-wrapper .sandwich.three {
        top: 63%;
    opacity: 0.3;
}
  .page-wrapper .vectorBg {
        position: absolute;
    top: 20%;
    right: 3%;
    width: 300px;
    z-index: 2;
    filter: drop-shadow(2px 4px 6px black);
}
.page-wrapper .vectorBgTxt { 
    position: absolute;
    top: 33%;
    right: -1%;
    width: 400px;
    z-index: 2;
    text-align: center;
    font-family: "Agbalumo", system-ui;
    font-size: 25px;
    color: #b82623;
}
  
  
      /* RESPONSIVE VIEW */
  
      @media(min-width:1200px){
          .page-wrapper .container{
              max-width: 1140px;
          }
      }
  
      @media(min-width:1500px){
          .page-wrapper .container{
              max-width: 1440px;
          }
        
      }
  
  
  
      @media (max-width:1500px)
      {
        .page-wrapper h1 {
          font-size: 60px;
        }
        .page-wrapper h2 {
          font-size: 45px;
        }
        .page-wrapper .headerSection {
    padding: 75px 0 0;
}
.page-wrapper .hero-img img {
            height: 650px;
          }
          .page-wrapper .orderBtn {
            padding: 10px 25px;
            font-size: 20px;
          }
          .page-wrapper .aboutContent.two h2 {
    left: 40px;
}
.page-wrapper .aboutContent h2:after {
  width: 110%;
  height: 110px;
}
.page-wrapper .paraSpacing {
  max-width: 95%;
}
.page-wrapper p {
  font-size: 20px;
  letter-spacing: 1px;
}
.page-wrapper .tastySection {
    padding: 50px 0 50px;
}
 .page-wrapper .innerContent {
      max-width: 55%;
    }
    .page-wrapper .hotChocolateImg {
              width: 30%;
        right: 0;
        transform: scale(1.4);
        transform-origin: center;
        top: 12%;
        z-index: 1;
    }
        .page-wrapper .aboutContent.two h2 {
        left: 75px;
    }
    .page-wrapper .aboutContent.two {
        padding-left: 50px;
    } 
    .page-wrapper .sandwich {
        font-size: 180px;
    }
    .page-wrapper .footerTopImg {
            width: 500px;
    }
    .page-wrapper .footerImgLeft, .page-wrapper .footerImgRight {
        width: 400px;
    }
    .page-wrapper .vectorBg {
            top: 10%;
    right: 2%;
    width: 270px;
    }
    .page-wrapper .vectorBgTxt {
        top: 23%;
    right: -4%;
    width: 400px;
    }
      }
  
      @media (max-width:1200px)
      {
        .page-wrapper h1 {
        font-size: 45px;
    }
        .page-wrapper h2 {
        font-size: 38px;
    }
    .page-wrapper h3 {
      font-size: 35px;
    }
    .page-wrapper .thumb {
      width: 160px;
      height: 160px;
    }
    .page-wrapper .hero-img img {
        height: 550px;
    }
    .page-wrapper .thumbnails {
      margin-top: 85px;
    }
    .page-wrapper .headerSection {
        padding: 50px 0 0;
    }
    .page-wrapper .thumb-arrow {
      top: -35px;
      border-left: 15px solid transparent;
    border-right: 15px solid transparent;
    border-top: 15px solid rgba(255, 255, 255, .85);
    }
    .page-wrapper .aboutContent {
    padding-right: 0px;
}
.page-wrapper .aboutImg {
  border-radius: 0 150px 150px 0;
}
.page-wrapper p {
        font-size: 18px;
        letter-spacing: 1px;
    }
    .page-wrapper .aboutContent h2:after {
      height: 95px;
    }
    .page-wrapper .aboutImg {
      border-radius: 0 150px 150px 0;
    }
    
        .page-wrapper h3 {
        font-size: 28px;
    }
    .page-wrapper .serviseContainer p { 
    font-size: 15px;
}
    .page-wrapper .serviseContainer {
        height: 320px;
    }
    .page-wrapper .aboutSection {
    padding: 150px 0 50px;
}
.page-wrapper .aboutImg.two {
    border-radius: 150px 0 0 150px;
}
.page-wrapper .footerSection {
    padding: 125px 0 100px;
}
.page-wrapper .footerContent{
        padding: 130px 100px 25px;
}
    .page-wrapper .sandwich {
        font-size: 150px;
    }
   .page-wrapper .sandwich.two { 
    opacity: 0.3;
    transform: scaleY(1.5);
}
.page-wrapper .sandwich.three { 
    opacity: 0.1;
}
    .page-wrapper .footerTopImg {
        width: 400px;
        top: -50px;
    }
    .page-wrapper .footerContent h2 {
        font-size: 75px;
    }
        .page-wrapper .footerImgLeft, .page-wrapper .footerImgRight {
        width: 350px;
    }
    .page-wrapper .footerImgRight {
        bottom: -50px
    }
      }
  
      @media (max-width:991px)
      {
        .page-wrapper h1 {
        font-size: 42px;
    }
    .page-wrapper h2 {
        font-size: 32px;
    }
        .page-wrapper .headerContent {
    padding-left: 20px;
}
.page-wrapper .hero-img {
  border-radius: 25px 0 0 25px;
}
.page-wrapper .orderBtn {
        padding: 10px 25px;
        font-size: 17px;
    }
    .page-wrapper .thumb, .page-wrapper .thumb img, .page-wrapper .cart-badge {
      border-radius: 15px;
    }
    .page-wrapper .aboutContent h2:after {
        height: 80px;
        background-position: left;
        border-top-left-radius: 15px;
    }
    .page-wrapper .aboutContent h2 {
      margin-bottom: 30px;
    }
    .page-wrapper p {
        font-size: 16px;
        letter-spacing: 1px;
    }
    .page-wrapper .aboutSection {
    padding: 120px 0 50px;
}
.page-wrapper .hotChocolateImg {
      position: relative;
    top: unset;
    transform: unset;
    margin: auto;
    width: 95%;
    max-width: 380px;
}
.page-wrapper .tastySection h2 {
  text-align: center;
  margin-bottom: 20px;
}
    .page-wrapper .serviseContainer {
                height: 235px;
        padding: 30px 15px;
    }
        .page-wrapper .serviseContainer p {
        font-size: 14px;
    }
        .page-wrapper .innerContent {
        max-width: 100%;
    }
        .page-wrapper .tastySection {
        padding: 25px 0 0px;
    }
    .page-wrapper .aboutContent.two h2:after {
    transform: scale(1.5) rotateY(180deg);
    left: -15%;
}
    .page-wrapper .aboutContent.two {
        padding-left: 5px;
    }
        .page-wrapper .footerSection {
        padding: 100px 0 100px;
    }
        .page-wrapper .footerContent {
        padding: 85px 100px 25px;
    }
        .page-wrapper .sandwich {
        font-size: 115px;
    }
        .page-wrapper .footerTopImg {
        width: 300px;
        top: -60px;
    }
        .page-wrapper .footerContent h2 {
        font-size: 55px;
    }
        .page-wrapper .footerImgLeft, .page-wrapper .footerImgRight {
        width: 250px;
    }
        .page-wrapper .footerImgRight {
        bottom: -50px;
    }
    .page-wrapper .vectorBg {
                top: 10%;
        right: 0;
        width: 250px;
        transform: rotate(15deg);
    }
    .page-wrapper .hotChocolateImgParent {
            position: relative;
    margin: auto;
    }
    .page-wrapper .vectorBgTxt {
        right: -22%;
    }
      }
  
      @media (max-width:767px)
      {
        .page-wrapper h1 {
        font-size: 35px;
    }
    .page-wrapper h2 {
        font-size: 24px;
    }
        .page-wrapper .hero-img img {
        height: 420px;
    }
    .page-wrapper .thumbnails {
        margin-top: 70px;
    }
    .page-wrapper .thumbnails {
      gap: 15px;
    }
    .page-wrapper .thumb-arrow {
        top: -30px;
        border-left: 10px solid transparent;
        border-right: 10px solid transparent;
        border-top: 10px solid rgba(255, 255, 255, .85);
    }
    .page-wrapper .headerContent {
        padding-left: 20px;
    }
    .page-wrapper .thumb {
        width: 140px;
        height: 140px;
    }
    .page-wrapper .thumb, .page-wrapper .thumb img, .page-wrapper .cart-badge {
        border-radius: 10px;
    }
    .page-wrapper p {
        font-size: 15px;
        letter-spacing: 0px;
    }
    .page-wrapper .aboutContent h2 {
        margin-bottom: 25px;
    }
    .page-wrapper .aboutContent h2:after {
      height: 60px;
    }
    .page-wrapper .aboutImg {
        border-radius: 0 100px 100px 0;
    }
        .page-wrapper .serviseContainer {
        height: 270px;
        border-radius: 25px;
        padding: 30px 15px;
    }
        .page-wrapper .aboutImg.two {
        border-radius: 100px 0 0 100px;
    }
        .page-wrapper .footerSection {
        padding: 80px 0 60px;
    }
            .page-wrapper .footerContent {
        padding: 65px 100px 25px;
    }
        .page-wrapper .sandwich {
        font-size: 85px;
    }
        .page-wrapper .footerTopImg {
        width: 250px;
        top: -65px;
    }
        .page-wrapper .footerContent h2 {
        font-size: 37px;
    }
    .page-wrapper .footerImgLeft, .page-wrapper .footerImgRight {
        width: 180px;
    }
      }
  
      @media (max-width:575px)
      {
        .page-wrapper h1 {
        font-size: 30px;
        text-align: center;
    }
    .page-wrapper h2 {
        font-size: 20px;
    }
    .page-wrapper p {
      font-size: 15px;
    }
        .page-wrapper .headerContent {
        padding-left: 10px;
        padding-right: 10px;
        text-align: center;
    }
    .page-wrapper .orderBtn {
        padding: 8px 15px;
        font-size: 14px;
        border-radius: 10px;
    }
    .page-wrapper .thumbnails {
      justify-content: center;
      margin-bottom: 30px;
    }
    .page-wrapper .hero-img img {
        height: 300px;
        max-width: 550px;
        width: 95%;
        margin: auto;
        display: flex;
        border-radius: 20px;
    }
    .page-wrapper .cart-badge svg {
      width: 26px;
    height: 26px;
    }
    .page-wrapper .aboutSection.one .row {
      flex-direction: column-reverse;
    }
    .page-wrapper .aboutContent {
      text-align: center;
    }
    .page-wrapper .aboutContent h2 {
      left: 0;
    }
    .page-wrapper .aboutSection {
        padding: 75px 0 30px;
    }
    .page-wrapper .aboutContent h2:after {
        height: 50px;
        width: 70%;
        max-width: 250px;
        transform: scale(1.4);
        margin: auto;
        left: 0;
        display: flex;
        right: 0;
        border-radius: 15px;
    }
    .page-wrapper .aboutImg {
        border-radius: 25px;
        min-height: unset;
        height: 300px;
        max-width: 550px;
        width: 95%;
        margin: auto;
        margin-top: 40px;
    }
    .page-wrapper .paraSpacing {
        max-width: 95%;
        margin-left: auto;
        margin-top: 35px;
    }
        .page-wrapper .serviseContainer {
        height: 100%;
        padding: 25px 20px;
        border-radius: 25px;
    }
        .page-wrapper h3 {
        font-size: 22px;
    }
    .page-wrapper .serviseContainer p {
        font-size: 14px;
        margin-bottom: 0;
    }
    .page-wrapper .hotChocolateImg {
        margin-top: 45px;
    }
        .page-wrapper .aboutContent.two h2:after {
        transform: scale(1.4) rotateY(180deg);
        left: 0;
    }
    .page-wrapper .paraSpacing.two {
    margin-left: auto;
    margin-right: auto;
}
    .page-wrapper .aboutImg.two {
        border-radius: 25px;
    }
        .page-wrapper .aboutContent.two h2 {
        left: 0;
    }
        .page-wrapper .footerSection {
        padding: 60px 0 60px;
    }
    .page-wrapper .footerContent {
        padding: 75px 10px 75px;
        max-width: 290px;
        margin: auto;
        border-radius: 25px;
    }
        .page-wrapper .sandwich {
        font-size: 50px;
        top: 10%;
    }
    .page-wrapper .sandwich.two {
            top: 38%;
    opacity: 0.2;
    }
    .page-wrapper .sandwich.three {
        opacity: 0.1;
    }
        .page-wrapper .footerTopImg {
        width: 180px;
        top: -15px;
    }
        .page-wrapper .footerImgLeft, .page-wrapper .footerImgRight {
        max-width: 200px;
        width: 45%;
    }
        .page-wrapper .vectorBgTxt {
        top: 33%;
        right: -25%;
        width: 400px;
        line-height: 1;
        font-size: 20px;
    }
        .page-wrapper .vectorBg {
        top: 20%;
        right: 20px;
        width: 200px;
        transform: rotate(15deg);
    }
      }
      
      @media (max-width:375px)
      {
          
      }
  
  </style>
