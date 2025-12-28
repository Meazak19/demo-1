<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dessert</title>
 
<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Big+Shoulders:opsz,wght@10..72,100..900&family=Roboto+Condensed:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet"> 


<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

<!--swiper-->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css">

 


<style type="text/css">


    /* font-family: 'Bebas Neue', sans-serif;
    font-family: 'Big Shoulders', sans-serif;
    font-family: 'Roboto Condensed', sans-serif; */
 

    body .page-wrapper { 
    font-family: 'Bebas Neue', sans-serif; 
    line-height: 24px; 
    overflow: hidden; 
    scroll-behavior: smooth; 
    background: var(--white-color); 
    --white-color: #ffffff;
    --black-color: #000000;
    --gray-color: #1d1d1d;
    --blue-color: #12bdb5;
    --orange-color: #ff6b19;
    --purple-color: #341a9c;
    --purple-light-color: #6857e3;
    --pink-color: #ff9cee;
    } 
    
   .page-wrapper p {
   margin-bottom: 25px;
    font-size: 30px;
    color: #fbf0e0;
    letter-spacing: 2px;
    line-height: 1.5;
    font-weight: 400;
    font-family: 'Roboto Condensed', sans-serif;
   }

   .page-wrapper p > a {
   color: inherit;
   }
   .page-wrapper h1, .page-wrapper h2, .page-wrapper h3, .page-wrapper h4, .page-wrapper h5, .page-wrapper h6 {
   line-height: 1.3;
   font-family: "Big Shoulders", sans-serif;
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

   .page-wrapper .textBlack{
    color: #000;
   }
   .page-wrapper .textWhite{
    color: #ffffff;
   }
   .page-wrapper .textRed{
    color: #ff0000;
   }

   .page-wrapper h1 {
font-size: 100px;
    font-weight: 800;
    letter-spacing: 0px;
    text-transform: uppercase;
    color: var(--blue-color);
    margin-top: -30px;
    margin-bottom: 30px;
    -webkit-text-stroke: 1px var(--white-color);
    -webkit-text-fill-color: transparent;
   }
    .page-wrapper h1 span{ 
    font-size: 60px;
    font-weight: 800;
    letter-spacing: 0px;
    color: #000;
    -webkit-text-stroke: 0;
    -webkit-text-fill-color: #000;
    display: block;
    margin-bottom: -20px;
    }
   .page-wrapper h2 {
    font-size: 90px;
    color: #ed0200;
    margin-bottom: 20px;
    font-weight: 600;
   }
   .page-wrapper h3 {
    font-size: 55px;
color: #fff;
    font-weight: 900;
    text-transform: uppercase;
    }
   .page-wrapper h4 {
    font-size: 50px;
    color: #fff;
    font-weight: 900;
    text-transform: uppercase;
    margin-bottom: 35px;
   }
   .page-wrapper h5 {
   color: #ed0200;
    font-size: 40px;
    text-transform: uppercase;
    font-weight: 500;
   }
   .page-wrapper .headerSection {
    background: linear-gradient(90deg, #a61208 0%, #e8ab36 100%);
    padding: 100px 0;
   }
   .page-wrapper .orderBtn {
        font-size: 32px;
    font-weight: 500;
    color: #b83c17;
    background: #000000;
    padding: 20px 30px;
    display: inline-block;
    font-family: "Big Shoulders", sans-serif;
   }
   .page-wrapper .orderBtn.two {
        background: #ed0200;
    color: #ffffff;
   }
   .page-wrapper .aboutSection {
    background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766555128phpeR2MPw.jpg');
    background-color: #000;
    padding: 100px 0;
   }
   .page-wrapper .aboutSection::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #000;
    opacity: 0.7;
    z-index: -1;
   }
   .page-wrapper .spoonImg {
    filter: invert(1);
    width: 55px;
   }
   .page-wrapper h2 span {
        display: block;
    -webkit-text-stroke: 2px #ed0200;
    -webkit-text-fill-color: transparent;
   line-height: 1.2;
    font-weight: 900;
    letter-spacing: 3px;
   }

   /* --- SVG Badge Styling --- */
        .badge-wrapper {
                position: relative;
    width: 200px;
    height: 200px;
    border: 2px solid #fff;
    margin-right: 10%;
    margin-left: auto;
    border-radius: 50%;
        }

        .badge-svg {
            width: 100%;
            height: 100%;
            animation: rotateBadge 20s linear infinite;
            padding: 5px;
        }

        .inner-circle-static {
            position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 110px;
    height: 110px;
    background-color: #ed0200;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 5;
        }

        @keyframes rotateBadge {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        .page-wrapper .svgTxt {
        font-size: 19px;
    letter-spacing: 1px;
    font-family: 'Roboto Condensed', sans-serif;
        }
        .page-wrapper .dishName {
                color: #d8842a;
        }
        .page-wrapper .gallerySection {
                padding: 100px 0;
    background: #e30000;
    z-index: 2;        }
        .page-wrapper .dishCard {
                background: #000;
    padding: 50px 30px;
    border-radius: 0 250px 250px;
    text-align: center;
                transition: all 0.2s linear;
        }
        .page-wrapper .dishCard:hover {
                background: #d8842a;
                transition: all 0.2s linear;
        }
        .page-wrapper .dishCard:hover .dishName{ 
            color: #000;
        }
        .page-wrapper .dishCard:hover .cartImg{ 
            background-color: #000;
        }
        .page-wrapper .dishCard:hover .cartImg img{ 
            filter: invert(1);
        }
        .page-wrapper .dishCard.two{
            border-radius: 250px 250px 0 250px;
        }
        .page-wrapper .galleryImg {
            border-radius: 50%;
            margin-bottom: 25px;
        }
        .page-wrapper .cartImg {
            background: #d8842a;
    width: 50px;
    height: 50px;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
        }
        .page-wrapper .patternSection {
                background: #000;
    padding: 300px 0;
    text-align: center;
        }
        .page-wrapper .patternSection::after { 
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766557335phpPUh1XH.png');
            width: 100%;
    height: 100%;
    z-index: -1;
    filter: brightness(0.5);
    transform: scale(1.5);
    background-size: contain;
        }
        .page-wrapper .leftImg {
            position: absolute;
    top: 0; 
    left: 0; 
    width: 175px; 
    transform: scale(4.0); 
        }
        .page-wrapper .rightImg {
            position: absolute;
    right: 0;
    bottom: 0;
    width: 175px;
    transform: scale(4);
        }
        .page-wrapper .paymentSection {
            z-index: 1;
    background: #000;
        }
        .page-wrapper .paymentContainer {
            display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    min-height: 750px;
    color: red;
    max-width: 400px;
    margin: auto;
        }
        .page-wrapper .paymentContainer p {
            color: red;
        }
        .page-wrapper .paymentImg {
            width: 150px;
            margin-bottom: 55px;
            filter: brightness(0) saturate(100%) invert(17%) sepia(85%) saturate(4160%) hue-rotate(20deg) brightness(105%) contrast(105%);
        }
        .page-wrapper .paymentContainer.two .paymentImg{
            filter: unset;
        }
        .page-wrapper .paymentContainer h5 {
                transform: scale(1.5);
    margin-bottom: 25px;
        }
        .page-wrapper .paymentContainer.two::after {
                content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: red;
    z-index: -1;
        }
        .page-wrapper .paymentContainer.two h5, .page-wrapper .paymentContainer.two p{
            color: #000;
        }
        .page-wrapper .lastSection {
            background-color: #000;
            padding: 100px 0;
            background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766560909php0IzSRH.jpg');
        }
        .page-wrapper .lastSection::after { 
            content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #000;
    opacity: 0.7;
    z-index: -1;
        }

        
  .headerImg {
    margin: auto;
  }
 .circleImgOne {
    /* filter: brightness(0) saturate(100%) invert(21%) sepia(75%) saturate(5909%) hue-rotate(348deg) brightness(93%) contrast(94%); */
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-40%, -60%) scale(1.5);
    z-index: -1;
    animation: zoom-in 2s linear infinite;
    width: 50%;
    opacity: 0.9;
    filter: invert(1);
 }
 .circleImgTwo {
    /* filter: brightness(0) saturate(100%) invert(21%) sepia(75%) saturate(5909%) hue-rotate(348deg) brightness(93%) contrast(94%); */
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-40%, -60%) scale(1.8);
    z-index: -1;
    animation: zoom-out 2s linear infinite;
    width: 50%;
    opacity: 0.9;
    filter: invert(1);
 }
 @keyframes zoom-in {
    from {
              -webkit-transform: translate(-40%, -60%) scale(1.8) rotate(180deg);
              transform: translate(-40%, -60%) scale(1.8) rotate(180deg);
    }
    to {
       -webkit-transform: translate(-40%, -60%) scale(2.0) rotate(180deg);
              transform: translate(-40%, -60%) scale(2.0) rotate(180deg);
    }
  }
 @keyframes zoom-out {
    from {
              -webkit-transform: translate(-40%, -60%) scale(2.0) rotate(180deg);
              transform: translate(-40%, -60%) scale(2.0) rotate(180deg);
    }
    to {
       -webkit-transform: translate(-40%, -60%) scale(1.8) rotate(180deg);
              transform: translate(-40%, -60%) scale(1.8) rotate(180deg);
    }
  }
 .mobileInnerImg {
    z-index: 1;
    position: relative;
 }
 .page-wrapper .patternImg {
    position: absolute;
    top: 0;
    z-index: 0;
    opacity: 0.1;
    width: 45%;
    filter: invert(1);
 }

 .page-wrapper .rotateTxt .spanOne {
    font-weight: 900;
    letter-spacing: 50px;
    writing-mode: vertical-lr;
    text-orientation: mixed;
    font-size: 200px;
    text-align: center;
    text-transform: uppercase;
    margin: 0 !important;
    line-height: 1;
    transform: rotate(180deg);
    padding: 0 0 0 10px;
    color: #5f0d04;
   }
   .page-wrapper .rotateTxt::after {
    content: '';
    position: absolute;
    background: #fff;
    background: linear-gradient(270deg, rgb(172 32 12) 10%, rgb(255 255 255 / 0%) 100%, rgb(102 201 128 / 0%) 0%, rgb(237 221 83 / 0%) 100%);
    bottom: 0;
    left: 46px;
    width: 120px;
    height: 100%;
    z-index: 0;
    opacity: 0.9;
   }
   .page-wrapper .rotateTxt {
    position: absolute;
    left: 0;
    width: 100%;
    height: 100%;
    top: 0;
    z-index: -1;
   }
   /* BUTTON */

   
   /* BUTTON */

   
   .page-wrapper .mask{
        -webkit-mask-image: url(https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766550640phptkEXVF.png);
        mask-image: url(https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766550640phptkEXVF.png);
        -webkit-mask-repeat: no-repeat;
        mask-repeat: no-repeat;
        -webkit-mask-size: contain;
        -webkit-mask-position: center;
    }
    .page-wrapper .footerImg {
        transform: scale(1.2);
        transform-origin: left;
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
            font-size: 78px;
            margin-bottom: 15px;
        }
        .page-wrapper h2 {
            font-size: 70px;
        }
        .page-wrapper h3 {
            font-size: 55px;
        }
        .page-wrapper h4 {
            font-size: 40px;
        }
        .page-wrapper h5 {
            font-size: 32px;
        }
        .page-wrapper h1 span {
            font-size: 46px;
        }
       .page-wrapper .headerSection {
            padding: 80px 0;
       }
       .page-wrapper p {
        font-size: 24px;
       }
       .page-wrapper .orderBtn {
            font-size: 30px; 
    padding: 15px 25px;
       }
       .page-wrapper .badge-wrapper {
        width: 180px;
    height: 180px;
       }
       .page-wrapper .badge-svg {
        padding: 2px;
       }
       .page-wrapper .svgTxt {
            font-size: 17px;
    letter-spacing: 2px;
       }
       .page-wrapper .aboutSection {
        padding: 80px 0;
       }
       .page-wrapper .inner-circle-static {
        width: 100px;
        height: 100px;
       }
       .page-wrapper .gallerySection {
        padding: 80px 0;
       }
       .page-wrapper .patternSection {
        padding: 300px 0;
       }
       .page-wrapper .leftImg, .page-wrapper .rightImg  {
            width: 150px;
       }
       .page-wrapper .paymentContainer {
        min-height: 600px;
       }
       .page-wrapper .rotateTxt .spanOne {
        font-size: 125px;
       }
       .page-wrapper .rotateTxt::after {
            left: 13px;
    width: 90px;
       }
       

    }

    @media (max-width:1199px)
    { 
        .page-wrapper h1 {
        font-size: 65px;
        margin-bottom: 15px;
    }
        .page-wrapper h2 {
        font-size: 50px;
    }
    .page-wrapper h2 span {
            -webkit-text-stroke: 1px #ed0200;
    }
        .page-wrapper h3 {
        font-size: 45px;
    }
    .page-wrapper h4 {
        font-size: 35px;
    }
        .page-wrapper h5 {
        font-size: 28px;
    }
        .page-wrapper p {
        font-size: 20px;
    }
        .page-wrapper h1 span {
        font-size: 38px;
        margin-bottom: -12px;
    }
        .page-wrapper .orderBtn {
        font-size: 26px;
        padding: 13px 20px;
    }
    .page-wrapper .headerSection {
        padding: 60px 0;
    }
        .page-wrapper .badge-wrapper {
        width: 160px;
        height: 160px;
    }
        .page-wrapper .inner-circle-static {
        width: 90px;
        height: 90px;
    }
    .page-wrapper .dishCard {
        padding: 40px 20px;
    }
    .page-wrapper .dishName { 
    font-size: 22px;
}
.page-wrapper .patternSection {
        padding: 220px 0;
    }
    .page-wrapper .leftImg, .page-wrapper .rightImg {
        width: 120px;
    }
    .page-wrapper .paymentContainer {
        min-height: 550px;
    }
    .page-wrapper .paymentImg { 
    margin-bottom: 35px;
}
    .page-wrapper .rotateTxt .spanOne {
        font-size: 100px;
        letter-spacing: 40px;
    }
    .page-wrapper .rotateTxt::after {
        left: 14px;
        width: 70px;
    }
    }

    @media (max-width:991px)
    {
      .page-wrapper h1 {
        font-size: 47px;
        margin-bottom: 5px;
    }
        .page-wrapper h2 {
        font-size: 44px;
    }
        .page-wrapper h3 {
        font-size: 40px;
    }
        .page-wrapper h4 {
        font-size: 30px;
        margin-bottom: 20px;
    }
        .page-wrapper h5 {
        font-size: 22px;
    }
        .page-wrapper h1 span {
        font-size: 28px;
        margin-bottom: -7px;
    }
    .page-wrapper .rotateTxt .spanOne {
        font-size: 85px;
        letter-spacing: 30px;
    }
    .page-wrapper .rotateTxt::after {
        left: 23px;
        width: 50px;
    }
        .page-wrapper .aboutSection {
        padding: 60px 0;
    }
        .page-wrapper p {
        font-size: 16px;
    }
        .page-wrapper .badge-wrapper {
        width: 140px;
        height: 140px;
    }
        .page-wrapper .inner-circle-static {
        width: 80px;
        height: 80px;
    }
    .page-wrapper .spoonImg { 
    width: 45px;
}
    .page-wrapper .gallerySection {
        padding: 60px 0;
    }
        .page-wrapper .dishCard {
        padding: 30px 10px;
    }
    .page-wrapper .galleryImg { 
    margin-bottom: 20px;
}
.page-wrapper .dishName {
        font-size: 19px;
        margin-bottom: 10px;
    }
    .page-wrapper .cartImg {
        width: 30px;
    height: 30px;
    }
        .page-wrapper .patternSection {
        padding: 160px 0;
    }
        .page-wrapper .leftImg, .page-wrapper .rightImg {
        width: 90px;
    }
    .page-wrapper .orderBtn {
        font-size: 22px;
        padding: 11px 15px;
    }
    .page-wrapper .paymentContainer {
        min-height: 475px;
        max-width: 225px;
    }
    .page-wrapper .paymentImg {
        width: 120px;
    }
    .page-wrapper .paymentContainer h5 {
        margin-bottom: 20px;
    }
    .page-wrapper .lastSection {
        padding: 50px 0;
    }
    }

    @media (max-width:767px)
    {
        .page-wrapper h1 {
            margin-top: 0;
        }
        .page-wrapper h4 {
                    filter: drop-shadow(-1px -1px 0px #000);
                    margin-bottom: 15px;
        }
            .page-wrapper .rotateTxt .spanOne {
        font-size: 65px;
        letter-spacing: 20px;
    }
        .page-wrapper .rotateTxt::after {
        left: 25px;
        width: 30px;
    }
    .page-wrapper .headerImg {
        margin-top: 50px;
        position: relative;
    }
    .page-wrapper .circleImgOne, .page-wrapper .circleImgTwo {
        opacity: 0.5;
    }
        .page-wrapper .aboutSection {
        padding: 50px 0;
        text-align: center;
    }
        .page-wrapper h2 span {
        -webkit-text-stroke: 2px #ed0200;
    }
        .page-wrapper .badge-wrapper {
        width: 120px;
        height: 120px;
        margin-right: 5%;
    }
        .page-wrapper .inner-circle-static {
        width: 65px;
        height: 65px;
    }
        .page-wrapper .spoonImg {
        width: 35px;
    }
    .page-wrapper .rotateTxt {
        display: flex;
    }
    .page-wrapper .dishCard {
        margin-bottom: 50px;
    }
        .page-wrapper .patternSection {
        padding: 125px 0;
    }
        .page-wrapper .leftImg, .page-wrapper .rightImg {
        width: 75px;
        filter: brightness(0.6);
    }
    .page-wrapper .paymentContainer.three::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: red;
    z-index: -1;
}
    .page-wrapper .paymentContainer.three::before {
content: '';
        position: absolute;
        top: -2px;
        left: 50%;
        transform: translateX(-50%);
        width: 200%;
        display: flex;
        height: 2px;
        background: #ff0000;
        z-index: 0;
}
.page-wrapper .paymentContainer.two::after { 
    width: 2px;
}
.page-wrapper .paymentContainer.two .paymentImg {
        filter: brightness(0) saturate(100%) invert(17%) sepia(85%) saturate(4160%) hue-rotate(20deg) brightness(105%) contrast(105%);
}
.page-wrapper .paymentContainer.three .paymentImg {
        filter: unset;
}
.page-wrapper .paymentContainer.two h5, .page-wrapper .paymentContainer.two p {
    color: #ed0200;
}
.page-wrapper .paymentContainer.three h5, .page-wrapper .paymentContainer.three p {
    color: #000000;
}
    .page-wrapper .paymentContainer {
        min-height: 450px;
    }
    .page-wrapper .lastSection {
        text-align: center;
    }
    .page-wrapper .lastSection h2 span{ 
        font-size: 40px;
    letter-spacing: 1px;
    }
    .page-wrapper .footerImg {
        margin-top: 100px;
    }
    .page-wrapper .lastSection::after {
        opacity: 0.8;
    }
    }

    @media (max-width:575px)
    {
            .page-wrapper h1 {
        font-size: 40px;
        margin-bottom: 5px;
            -webkit-text-stroke: unset;
    -webkit-text-fill-color: #fff;
    }
    .page-wrapper h2 {
        font-size: 38px;
    }
        .page-wrapper h2 span {
        -webkit-text-stroke: unset;
        -webkit-text-fill-color: #ed0200;
        font-weight: 600;
    }
        .page-wrapper h3 {
        font-size: 32px;
    }
    .page-wrapper h4 {
        font-size: 28px;
    }
            .page-wrapper h1 span {
        font-size: 25px;
        margin-bottom: -5px;
    }
        .page-wrapper .patternSection {
        padding: 100px 0;
    }
        .page-wrapper .rotateTxt::after {
        left: 14px;
        width: 40px;
    }
    .page-wrapper .rotateTxt {
            width: 50%;
    height: 50%;
    top: 60%;
    transform: translateY(-50%);
    }
    .page-wrapper .rotateTxt::after {
            background: linear-gradient(270deg, rgb(178 47 16) 10%, rgb(255 255 255 / 0%) 100%, rgb(102 201 128 / 0%) 0%, rgb(237 221 83 / 0%) 100%);
    }
    .page-wrapper .patternImg {
        width: 100%;
        z-index: -1;
    }
        .page-wrapper p {
        font-size: 15px;
    }
        .page-wrapper .orderBtn {
        font-size: 20px;
        letter-spacing: 1px;
        padding: 9px 13px;
    }
        .page-wrapper .badge-wrapper {
        width: 100px;
        height: 100px;
        margin-right: 0%;
        margin-top: 10px;
    }
        .page-wrapper .svgTxt {
        font-size: 19px;
        letter-spacing: 1px;
        font-weight: 400;
    }
        .page-wrapper .inner-circle-static {
        width: 50px;
        height: 50px;
    }
        .page-wrapper .spoonImg {
        width: 27px;
    }
        .page-wrapper .gallerySection {
        padding: 50px 0;
    }
        .page-wrapper .dishCard {
        max-width: 300px;
        margin: auto;
        margin-bottom: 50px !important;
    }
        .page-wrapper .paymentContainer.two::after {
        width: 100%;
    }
        .page-wrapper .paymentContainer.two .paymentImg {
        filter: unset;
    }
        .page-wrapper .paymentContainer.two h5, .page-wrapper .paymentContainer.two p {
        color: #000000;
    }
    .page-wrapper .paymentContainer.three::before, .page-wrapper .paymentContainer.three::after {
        opacity: 0;
    }
    .page-wrapper .paymentContainer.three .paymentImg {
        filter: brightness(0) saturate(100%) invert(17%) sepia(85%) saturate(4160%) hue-rotate(20deg) brightness(105%) contrast(105%);
    }
        .page-wrapper .paymentContainer.three h5, .page-wrapper .paymentContainer.three p {
        color: #ed0200;
    }
        .page-wrapper .paymentContainer {
        min-height: 350px;
    }
    .page-wrapper .lastSection .row {
        flex-direction: column-reverse;
    }
        .page-wrapper .lastSection h2 span {
        font-size: 26px;
        letter-spacing: 0px;
    }
        .page-wrapper .footerImg {
        margin-top: 0;
        margin-bottom: 10px;
        transform: scale(1.0);
    }
    .page-wrapper .paymentImg {
        margin-bottom: 20px;
    }
    .page-wrapper .dishCard {
        padding: 30px 25px;
    }
        .page-wrapper .gallerySection {
        padding: 50px 0 15px;
    }
    }
    
    @media (max-width:375px)
    {

    }

</style>


</head>


<body>

    

<div id="page-top-margin"></div>


<div class="page-wrapper">

  
    <section class="headerSection">
        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766553938phpWLI5Zr.png" class="img-fluid patternImg" alt="">
        <div class="rotateTxt">
            <span class="spanOne"> 
                Chinese
            </span>
            <div class="spanTwo">
    
            </div>
        </div>
       <div class="container">
           <div class="row align-items-center">
               <div class="col-md-6">
                   <div class="headerContent text-center"> 
                       <h1> <span> Authentic Chinese Flavours </span> MADE FRESH DAILY!</h1>
                       <a href="/order-now" class="orderBtn">ORDER NOW</a>
                   </div>
               </div>
               <div class="col-md-6 text-center">
                   <div class="headerImg">
                       <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766550640phpvzaO0d.png" alt="Noodle Bowl" class="img-fluid">
   
                       
                       <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766147905phpJSV6y6.png" class="img-fluid circleImgOne" alt="">
                       <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766147905phpJSV6y6.png" class="img-fluid circleImgTwo" alt="">
                   </div>
               </div>
           </div>
       </div>
   </section>

    <section class="aboutSection">
       <div class="container">
           <div class="row align-items-center">
               <div class="col-lg-6 col-md-6 order-2 order-md-1">
                   <div class="badge-wrapper mb-4">
                   <svg class="badge-svg" viewBox="0 0 200 200">
                       <defs>
                           <path id="circlePath" d="M 100, 100 m -75, 0 a 75,75 0 1,1 150,0 a 75,75 0 1,1 -150,0"></path>
                       </defs>
                       <text fill="white" class="svgTxt">
                           <textPath href="#circlePath">
                               SATISFY YOUR CRAVINGS • SATISFY YOUR CRAVINGS •
                           </textPath>
                       </text>
                   </svg>
                   <div class="inner-circle-static">
                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766550640php7b7eqx.png" class="img-fluid spoonImg" alt="">
                   </div>
               </div>

                   <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766550640phplCMGrO.png" alt="" class="img-fluid">
               </div>
               <div class="col-lg-6 col-md-6 order-1 order-md-2">
                   <h2>FROM TAKEAWAY<span>TO DINE-IN</span></h2>
                   <p>Welcome to the company where the choice of authentic Chinese flavours is vast. Our menu is filled with high quality ingredients and traditional cooking methods to ensure every bite is a journey through China's rich culinary history.</p>
                   <a href="/order-now" class="orderBtn two">ORDER NOW</a>
               </div>
           </div>
       </div>
   </section>

   <section class="gallerySection">
       <div class="container-fluid">
       </div>
       <div class="container">
           <h3 class="text-center">BEST SELLING DISHES</h3>
           <div class="row pt-lg-5 pt-md-4 pt-sm-4 pt-4">
               <div class="col-lg-3 col-md-3 col-sm-6">
                   <div class="dishCard">
                       <div class="dish-img-container mask">
                           <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1722767878phpjaCEkO.jpg" class="img-fluid w-100 galleryImg" alt="">
                       </div>
                       <p class="dishName">FRIED RICE</p>
                       <div class="cartImg">
                           <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1765357749phpR6fTv4.png" class="img-fluid" alt="">
                       </div>
                   </div>
               </div>   
               <div class="col-lg-3 col-md-3 col-sm-6">
                   <div class="dishCard two">
                       <div class="dish-img-container mask">
                           <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1722767878phpjaCEkO.jpg" class="img-fluid w-100 galleryImg" alt="">
                       </div>
                       <p class="dishName">FRIED RICE</p>
                       <div class="cartImg">
                           <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1765357749phpR6fTv4.png" class="img-fluid" alt="">
                       </div>
                   </div>
               </div>   
               <div class="col-lg-3 col-md-3 col-sm-6">
                   <div class="dishCard mb-0">
                       <div class="dish-img-container mask">
                           <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1722767878phpjaCEkO.jpg" class="img-fluid w-100 galleryImg" alt="">
                       </div>
                       <p class="dishName">FRIED RICE</p>
                       <div class="cartImg">
                           <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1765357749phpR6fTv4.png" class="img-fluid" alt="">
                       </div>
                   </div>
               </div>   
               <div class="col-lg-3 col-md-3 col-sm-6">
                   <div class="dishCard two mb-0">
                       <div class="dish-img-container mask">
                           <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1722767878phpjaCEkO.jpg" class="img-fluid w-100 galleryImg" alt="">
                       </div>
                       <p class="dishName">FRIED RICE</p>
                       <div class="cartImg">
                           <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1765357749phpR6fTv4.png" class="img-fluid" alt="">
                       </div>
                   </div>
               </div>   
           </div>
       </div>
   </section>

    <section class="patternSection">
       <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766550640phppgKVt5.png" class="img-fluid leftImg" alt="">
       <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766550640phpLjDBXW.png" class="img-fluid rightImg" alt="">
       <div class="container">
           <div class="row align-items-center justify-content-center">
               
               <div class="col-lg-6 col-md-7 col-sm-10">
                   <h4>A PERFECT BLEND OF TRADITION &amp; TASTE IN EVERY DISH!</h4>
                   <a href="/order-now" class="orderBtn two">ORDER NOW</a>
               </div> 

           </div>
       </div>
   </section>

   <section class="paymentSection">
       <div class="container-fluid">
           <div class="row paymentRow justify-content-center">
               <div class="col-lg-4 col-md-4 col-sm-6">
                   <div class="paymentContainer">
                       <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766557517phpxmkVlz.png" class="img-fluid paymentImg" alt="Domain930 Do not Touch food">
                       <h5>
                           Order in Seconds
                       </h5>
                       <p class="mb-0">
                           Choose from a variety of tasty options.
                       </p>
                   </div>
               </div>
               <div class="col-lg-4 col-md-4 col-sm-6">
                   <div class="paymentContainer two">
                       <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766557517phppmtInQ.png" class="img-fluid paymentImg" alt="Domain930 Do not Touch food">
                       <h5>
                           Order in Seconds
                       </h5>
                       <p class="mb-0">
                           Choose from a variety of tasty options.
                       </p>
                   </div>
               </div>
               <div class="col-lg-4 col-md-4 col-sm-6">
                   <div class="paymentContainer three">
                       <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766557517phpS5BORc.png" class="img-fluid paymentImg" alt="Domain930 Do not Touch food">
                       <h5>
                           Order in Seconds
                       </h5>
                       <p class="mb-0">
                           Choose from a variety of tasty options.
                       </p>
                   </div>
               </div>
           </div>
       </div>
   </section>

    <section class="lastSection">
       <div class="container">
           <div class="row align-items-center">

               <div class="col-lg-6 col-md-6">
                   <h2>DIVE INTO A WORLD <span> OF AUTHENTIC CHINESE CUISINE </span> </h2>
                   <p>Welcome to the company where the choice of authentic Chinese flavours is vast. Our menu is filled with high quality ingredients and traditional cooking methods to ensure every bite is a journey through China's rich culinary history.</p>
                   <a href="/order-now" class="orderBtn two">ORDER NOW</a>
               </div>

               <div class="col-lg-6 col-md-6">
                  <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766560706phpuikyTE.png" alt="" class="img-fluid footerImg">
               </div>
               
           </div>
       </div>
   </section>

   

</div>



<script>
   window.addEventListener("load", function(){
   pageTopmargin();
   $(window).scrollTop($(window).scrollTop()+1);
   });
   pageTopmargin();
   function pageTopmargin() {
   var headerHeight = $('#header').height();
   $('#page-top-margin').css({ marginTop : headerHeight + 'px' });
   }
   $("#banner_content").appendTo($("#offer-section"));
   var pageSection = $('[data-background]');
   pageSection.each(function(indx){
   if ($(this).attr("data-background")){
   $(this).css("background-image", "url(" + $(this).data("background") + ")");
   }
   });
</script>

 


<script
      src="https://code.jquery.com/jquery-3.6.0.min.js"
      integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4="
      crossorigin="anonymous"> 
    $.getScript("https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js", function() {
        $('.hero-slider').owlCarousel({
            loop:true,
            margin:0,
            nav:true,
            dots:false,
            autoplay:true,
            items:1
        });
           $('.menu-slider').owlCarousel({
                  loop:true,
                  margin:0,
                  nav:false,
                  dots:true,
                  items:3,
                  autoplay:true, 
                  responsive:{
                      0:{
                          items:1
                      },
                      768:{
                          items:2
                      },
                      1025:{
                          items:3
                      }
                  }
              });
    });
     
 </script>
</body>
</html>
 


<!-- 
 
https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766147804phpA6QjXx.jpg 
https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1766147905phpJSV6y6.png
 
 -->
