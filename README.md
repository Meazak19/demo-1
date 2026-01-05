<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dessert</title>
 
<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sansation:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&amp;family=Titan+One&amp;display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">



<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css">
 

<style type="text/css">


/* 

font-family: "Titan One", sans-serif;
font-family: "Sansation", sans-serif;

*/  

    body .page-wrapper { 
    font-family: "Sansation", sans-serif; 
    color: #6c6a6a; 
    line-height: 24px; 
    overflow-x: hidden; 
    scroll-behavior: smooth; 
    background: #ffd6b7;
    } 
    
   .page-wrapper p {
    margin-bottom: 25px;
    font-size: 22px;
    font-family: "Sansation", sans-serif;
    color: #434236;
    letter-spacing: 1px;
    line-height: 1.5;
    font-weight: 500;
   }

   .page-wrapper p > a {
   color: inherit;
   }
   .page-wrapper h1, .page-wrapper h2, .page-wrapper h3, .page-wrapper h4, .page-wrapper h5, .page-wrapper h6 {
   line-height: 1.3;
   font-family: "Titan One", sans-serif;
   }
   .page-wrapper .row {
   margin: 0 -15px!important;
   }

   
   .page-wrapper section {
   position: relative;
   z-index: 1;
   background-size: cover;
   background-position: center center;
   background-repeat: no-repeat;
   }    
 
 

   .page-wrapper h1 {
    color: #b84241;
    font-size: 92px;
    margin-bottom: 40px;
    position: relative;
   }
   .page-wrapper h2 {
    font-size: 60px;
    color: #fff;
    filter: drop-shadow(1px 6px 1px #000000ab);
    text-transform: uppercase;
   }
   .page-wrapper h3 {
    font-size: 55px;
    color: #fff;
    filter: drop-shadow(1px 6px 1px #000000ab);
    text-transform: uppercase;
    }
    .page-wrapper .gallerySection h3 {
        margin-left: 250px;
    }
   .page-wrapper h4 {
        font-size: 50px;
    color: #fff;
    text-transform: uppercase;
    margin-bottom: 25px;
   }
   .page-wrapper h5 {
    font-size: 25px;
    font-weight: 600;
    color: #fff;
    font-family: "Sansation", sans-serif;
    margin-bottom: 0;
   }
   .page-wrapper h6 {
    
   }
   .page-wrapper .headerSection {
    padding: 150px 0;
    background: #fed3b3;
    background: linear-gradient(0deg, rgb(223 148 130) 0%, rgb(252 211 179) 100%);
   }
   .page-wrapper .headerSection::after {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    width: 40%;
    height: 100%;
    clip-path: polygon(45% 0%, 100% 0%, 100% 100%, 0% 100%);
    background: #b84241;
    z-index: -1;
   }
   .page-wrapper .orderBtn {
    display: inline-block;
    background: #b84241;
    font-size: 22px;
    padding: 13px 25px;
    border-radius: 12px;
    color: #fff;
   }
   .page-wrapper .orderBtn.two { 
    background: #fff;
    color: #ea7461;
    filter: drop-shadow(3px 2px 5px #0000004f);
   }
   .page-wrapper h1:after { 
    content: '';
    position: absolute;
    bottom: -15px;
    left: 0;
    width: 80%;
    height: 5px;
    background-color: #fff;
   }
   .page-wrapper .headerImgOne {
    transform: scale(1.4);
    transform-origin: left top;
   }
   .page-wrapper .aboutBg:after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #ea7461;
    z-index: -1;
    border-radius: 450px;
    filter: drop-shadow(0px 10px 0px #5d2727);
   }
   .page-wrapper .aboutSection {
    padding: 100px 0;
   }
   .page-wrapper .aboutImg {
    max-width: 350px;
    margin: auto;
    display: flex;
    transform: scale(1.5);
   }
   .page-wrapper .aboutContent {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100%;
    text-align: center;
    max-width: 500px;
   }
   .page-wrapper .aboutBg {
    position: relative;
   }

.page-wrapper .owl-carousel .owl-nav button.owl-next, .page-wrapper .owl-carousel .owl-nav button.owl-prev, .page-wrapper .owl-carousel button.owl-dot {
    font-size: 80px;
    color: #fff;
}

.page-wrapper .carouselCenter {
    margin-top: 50px;
    margin-left: 400px;
    position: relative;
}
.page-wrapper .owl-carousel .owl-item img {
height: 320px;
    object-fit: cover;
    border-radius: 25px 25px 0 0;
}

.page-wrapper .carouselHover {
    z-index: 9;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #fff;
    font-weight: 800;
    font-size: 20px;
    text-align: center;
    font-family: 'Rowdies';
    text-transform: uppercase;
    letter-spacing: 1px;
}
.page-wrapper .owl-theme .owl-nav [class*=owl-]:hover {
    background: #00000000 !important;
}
.page-wrapper .gallerySection .slantingDiv {
       content: '';
    position: absolute;
    top: 12%;
    right: -10px;
    width: 75%;
    background: #b84242;
    height: 75%;
    z-index: -1;
    transform-origin: right;
    border-radius: 50px;
    -webkit-transform: rotateY(5deg);
}
.page-wrapper .gallerySection {
    padding: 100px 0;
    perspective: 350px;
    margin: 50px 0;
}
.page-wrapper .paymentContainer {
     display: flex;
    align-items: center;
    width: 70%;
    background: #b84242;
    border-radius: 0 200px 200px 0;
    padding: 20px 0;
    padding-left: 10%;
}
/* .page-wrapper .paymentImg {
    width: 20%;
} */
.page-wrapper .paymentImg img{ 
          width: 75px;
    height: 100px;
    object-fit: contain;
    filter: invert(1);
    margin-right: 25px;
}
.page-wrapper .paymentContent {
    width: 75%;
}
.page-wrapper .paymentContainer.two {
    width: 85%;
    margin: 30px 0;
}
.page-wrapper .paymentContainer.three {
    width: 100%; 
}
.page-wrapper .paymentSection {
    padding: 100px 0;
}
.page-wrapper .hygieneContainer {
    padding: 130px 70px 50px;
    background: #b84242;
    border-radius: 450px 450px 0 0;
    max-width: 500px;
    margin: auto;
    text-align: center;
}
.page-wrapper .hygieneContent p {
        color: #ffffff;
    font-size: 28px;
    letter-spacing: 0px;
    text-align: center;
}
.page-wrapper .footerSection {
    padding: 50px 0 0 ;
}
.page-wrapper .galleryText {
        background: #5d2727;
    padding: 18px 15px;
    border-radius: 0 0 25px 25px;
}
.page-wrapper .galleryBtn  {
    color: #ffd6b6;
    font-size: 25px;
}
.page-wrapper .plusIcon {
    width: 35px;
    height: 35px;
    background: #ffd6b6;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.page-wrapper .plusIcon svg{ 
        width: 28px;
    height: 28px;
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
                font-size: 70px;
    margin-bottom: 30px;
        }
        .page-wrapper h2 {
            font-size: 55px;
        }
        .page-wrapper h3 {
            font-size: 50px;
        }
        .page-wrapper h4 {
            font-size: 42px;
        }
        .page-wrapper h1:after {
                bottom: -10px;
    left: 0;
    width: 70%;
    height: 3px;
        }
        .page-wrapper p {
            font-size: 20px;
        }
        .page-wrapper .headerSection {
                padding: 80px 0;
        }
        .page-wrapper .headerSection .row {
            justify-content: center;
    align-items: center;
        }
        .page-wrapper .headerImgOne {
    transform: scale(1.2);
    transform-origin: unset;
}
.page-wrapper .gallerySection {
    padding: 100px 0;
    perspective: 300px;
    margin: 50px 0 0;
}
.page-wrapper .gallerySection .slantingDiv {
    top: 12%;
    right: -10px;
    width: 85%;
    -webkit-transform: rotateY(4deg);
}
.page-wrapper .gallerySection h3 {
    margin-left: 80px;
}
.page-wrapper .carouselCenter {
    margin-top: 50px;
    margin-left: 180px;
    position: relative;
}
.page-wrapper .owl-carousel .owl-item img {
    height: 250px;
}
.page-wrapper .owl-theme .owl-nav {
    margin-top: 30px !important;
}
.page-wrapper .galleryBtn {
    font-size: 22px;
}
.page-wrapper .plusIcon svg {
    width: 25px;
    height: 25px;
}
.page-wrapper .plusIcon {
        width: 30px;
    height: 30px;
}
.page-wrapper .paymentSection {
    padding: 50px 0;
}
.page-wrapper .hygieneContainer {
        padding: 130px 35px 50px;
}
    }

    @media (max-width:1199px)
    {
            
        .page-wrapper h1 {
        font-size: 60px;
        margin-bottom: 25px;
        line-height: 1.2;
    }
    .page-wrapper h2 {
        font-size: 50px;
    }
        .page-wrapper h3 {
        font-size: 45px;
    }
    .page-wrapper h4 {
        font-size: 40px;
    }
    .page-wrapper h5 {
        font-size: 23px;
    }
    .page-wrapper .headerSection {
        padding: 75px 0;
    }
    .page-wrapper .aboutImg {
            max-width: 300px;
    }
    .page-wrapper .aboutContent {
        max-width: 400px;
    }
        .page-wrapper p {
        font-size: 18px;
        margin-bottom: 15px;
    }
        .page-wrapper .gallerySection {
        padding: 80px 0;
        perspective: 250px;
        margin: 30px 0 0;
    }
    .page-wrapper .gallerySection .slantingDiv {
        width: 86%;
    }
        .page-wrapper .gallerySection h3 {
        margin-left: 65px;
    }
    .page-wrapper .carouselCenter {
                margin-left: 150px;
    }
        .page-wrapper .owl-carousel .owl-item img {
        height: 225px;
    }
    .page-wrapper .galleryBtn {
        font-size: 20px;
    }
        .page-wrapper .plusIcon {
        width: 28px;
        height: 28px;
    }
        .page-wrapper .plusIcon svg {
        width: 23px;
        height: 23px;
    }
        .page-wrapper .owl-theme .owl-nav {
        margin-top: 25px !important;
    }
        .page-wrapper .paymentSection {
        padding: 15px 0;
    }
    .page-wrapper .paymentContainer.two {
            margin: 20px 0;
            width: 90%;
    }
    .page-wrapper .paymentImg img {
            width: 65px;
    height: 90px;
        margin-right: 20px;
    }
    .page-wrapper .paymentContainer {
            padding: 15px 0;
    padding-left: 7%;
    width: 75%;
    }
    .page-wrapper .footerSection {
    padding: 30px 0 0;
}
    .page-wrapper .hygieneContainer {
        padding: 110px 15px 40px;
    }
    .page-wrapper .hygieneContent p {
        font-size: 23px;
    }
    }

    @media (max-width:991px)
    {
            .page-wrapper h1 {
        font-size: 45px;
    }
        .page-wrapper h2 {
        font-size: 40px;
    }
        .page-wrapper h3 {
        font-size: 38px;
    }
        .page-wrapper h4 {
        font-size: 35px;
        margin-bottom: 15px;
    }
        .page-wrapper h5 {
        font-size: 21px;
    }
            .page-wrapper .headerSection {
        padding: 55px 0;
    }
        .page-wrapper p {
        font-size: 15px;
    }
    .page-wrapper .orderBtn {
        font-size: 20px;
    padding: 10px 20px;
    }
    .page-wrapper .aboutSection {
    padding: 50px 0;
}
    .page-wrapper .aboutImg {
        max-width: 225px;
    }
        .page-wrapper .aboutContent {
        max-width: 350px;
        padding: 25px 0;
    }
    .page-wrapper .gallerySection {
        padding: 50px 0;
        perspective: 300px;
        margin: 20px 0 0;
    }
    .page-wrapper .gallerySection .slantingDiv {
        width: 92%;
    }
        .page-wrapper .carouselCenter {
        margin-left: 80px;
        margin-top: 30px;
    }
        .page-wrapper .gallerySection h3 {
        margin-left: 10px;
    }
        .page-wrapper .owl-carousel .owl-item img {
        height: 200px;
        border-radius: 20px 20px 0 0;
    }
    .page-wrapper .galleryText {
            padding: 14px 12px;
    border-radius: 0 0 20px 20px;
    }
    .page-wrapper .galleryBtn {
        font-size: 18px;
    }
        .page-wrapper .plusIcon {
        width: 22px;
        height: 22px;
    }
        .page-wrapper .plusIcon svg {
        width: 18px;
        height: 18px;
    }
    .page-wrapper .paymentImg img {
        width: 55px;
        height: 70px;
        margin-right: 15px;
    }
        .page-wrapper .paymentContainer {
        padding: 10px 0;
        padding-left: 5%;
        width: 80%;
    }
        .page-wrapper .paymentContainer.two {
        margin: 15px 0;
        width: 92%;
    }
        .page-wrapper .hygieneContainer {
        padding: 80px 15px 30px;
    }
    .page-wrapper .hygieneContent p {
        font-size: 20px;
    }
    }

    @media (max-width:767px)
    {
            .page-wrapper h1 {
        font-size: 38px;
    }
    .page-wrapper h2 {
        font-size: 36px;
    }
        .page-wrapper h3 {
        font-size: 34px;
    }
        .page-wrapper h4 {
        font-size: 26px;
        margin-bottom: 10px;
    }
        .page-wrapper h5 {
        font-size: 19px;
    }
            .page-wrapper .headerSection {
        padding: 45px 0;
    }
    .page-wrapper .headerContent {
        text-align: center;
    }
        .page-wrapper h1:after { 
        width: 100%;
        height: 2px;
    }
        .page-wrapper p {
        font-size: 16px;
    }
        .page-wrapper .headerImgOne {
        transform: scale(1.0);
        margin-top: 50px; 
    }
    .page-wrapper .headerSection::after {
            width: 100%;
    height: 60%;
    top: unset;
    bottom: 0;
    clip-path: polygon(100% 0%, 100% 0%, 100% 100%, 0% 100%);
    }
    .page-wrapper .aboutSection .row {
            flex-direction: column-reverse;
    }
        .page-wrapper .aboutImg {
        max-width: 270px;
        transform: scale(1.3) rotate(0deg);
    }
        .page-wrapper .aboutContent {
        max-width: 455px;
        padding: 25px 0 80px;
        margin: auto;
        margin-top: 65px;
    }
    .page-wrapper .gallerySection {
                perspective: 120px;
    }
       .page-wrapper .gallerySection .slantingDiv {
        width: 84%;
        left: 53.5%;
        -webkit-transform: translateX(-50%) rotateY(2deg);
        border-radius: 25px;
    }
        .page-wrapper .gallerySection h3 {
        margin-left: 0;
        padding-top: 50px;
        text-align: center;
    }
        .page-wrapper .carouselCenter {
                width: 85%;
        margin: auto;
        margin-top: 30px;
    }
        .page-wrapper .paymentContainer {
        padding: 5px 0;
        padding-left: 3%;
        width: 100%;
    }
        .page-wrapper .paymentImg img {
        width: 50px;
        height: 65px;
        margin-right: 10px;
    }
        .page-wrapper .paymentContainer.two {
        margin: 10px 0;
        width: 100%;
    }
    .page-wrapper .hygieneContainer {
        padding: 60px 15px 10px;
    }
        .page-wrapper .hygieneContent p {
        font-size: 16px;
    }
    }

    @media (max-width:575px)
    {
        .page-wrapper h1 {
        font-size: 32px;
    }
        .page-wrapper h2 {
        font-size: 30px;
    }
    .page-wrapper h3 {
        font-size: 28px;
    }
        .page-wrapper h4 {
        font-size: 26px; 
    }
        .page-wrapper h5 {
        font-size: 18px;
    }
        .page-wrapper p {
        font-size: 14px;
    }
        .page-wrapper h1:after {
        width: 65%;
        right: 0;
        margin: auto;
        height: 2px;
    }
        .page-wrapper .orderBtn {
        font-size: 18px;
        padding: 7px 18px;
    }
        .page-wrapper .headerSection {
        padding: 40px 0;
    }
    .page-wrapper .aboutBg:after {
            left: 50%;
    transform: translateX(-50%);
    width: 95%; 
    border-radius: 40px;
    max-width: 475px;
    }
    .page-wrapper .aboutContent {
        margin-top: 0;
    }
        .page-wrapper .aboutImg {
        max-width: 210px; 
    }
        .page-wrapper .paymentContainer {
        padding: 5px 0;
        padding-left: 0;
        width: 100%;
        max-width: 275px;
        margin: auto;
        border-radius: 200px;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
    }
    .page-wrapper .paymentContent {
    width: unset;
}
    .page-wrapper .paymentContainer.two {
        margin: 10px auto;
        width: 100%;
        border-radius: 200px;
    }
        .page-wrapper .hygieneContainer {
        padding: 15px 15px 15px;
        border-radius: 50px;
    }
    .page-wrapper .hygieneContainer.two { 
        margin-top: 15px;
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
    <div class="container">
        <div class="row">
            <div class="col-lg-7 col-md-7 col-sm-12">
                <div class="headerContent">
                    <h1>
                        Traditional Thai Cuisine, Made with Passion!
                    </h1> 
                    <p>
                        Good food should always be within reach! At TEMP-1069-Kabana - 879533  GB, we make it easy to enjoy your favourite Thai dishes at home. 
                    </p>
                    <a href="/order-now" class="orderBtn">
                        Order Now
                    </a>
                </div>
            </div>
            <div class="col-lg-5 col-md-5 col-sm-12">
                <div>
                    <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1767078573phpMyvQpH.png" class="img-fluid headerImgOne" alt="">
                </div>
            </div>
        </div> 
    </div>
</section>

<section class="aboutSection">
    <div class="container aboutBg">
        <div class="row">
            <div class="col-lg-6 col-md-5 col-sm-12">
                <div>
                    <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1767093566phpg0wKVk.png" class="img-fluid aboutImg" alt="">
                </div>
            </div>
            <div class="col-lg-6 col-md-7 col-sm-12">
                <div class="aboutContent">
                    <h2>
                        About Us
                    </h2>
                    <p>
                        Take your taste buds on a Thai adventure with TEMP-1069-Kabana - 879533  GB. Our takeaway service offers a selection of handcrafted Thai dishes, made fresh to order. Whether you're dining solo or sharing with family, our food brings the perfect balance of flavours to every meal.
                    </p>
                    <a href="/order-now" class="orderBtn two">
                        Order Now
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="gallerySection">
    <div class="slantingDiv"></div>
    <div class="container">
        <h3>
            Our Gallery
        </h3>
    </div>
    <div class="container-fluid px-0">
        <div class="carouselCenter">
            <div class="owl-carousel owl-theme">
                <div class="item">
                    <div class="item hovercontent">
                        <a href="/order-now">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1715064946phpK6dHb3.jpg" alt="TEMP-1069-Kabana - 879533  GB Chop Suey">
                            <div class="d-flex justify-content-between align-items-center galleryText">
                                <p class="galleryBtn mb-0">
                                    Order Now 
                                </p>
                                <span class="plusIcon"> 
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640"><path d="M352 128C352 110.3 337.7 96 320 96C302.3 96 288 110.3 288 128L288 288L128 288C110.3 288 96 302.3 96 320C96 337.7 110.3 352 128 352L288 352L288 512C288 529.7 302.3 544 320 544C337.7 544 352 529.7 352 512L352 352L512 352C529.7 352 544 337.7 544 320C544 302.3 529.7 288 512 288L352 288L352 128z"/></svg>
                                </span>
                            </div>
                        </a> 
                    </div>
                </div>   
                <div class="item">
                    <div class="item hovercontent">
                        <a href="/order-now">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1715064946phpK6dHb3.jpg" alt="TEMP-1069-Kabana - 879533  GB Chop Suey">
                            <div class="d-flex justify-content-between align-items-center galleryText">
                                <p class="galleryBtn mb-0">
                                    Order Now 
                                </p>
                                <span class="plusIcon"> 
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640"><path d="M352 128C352 110.3 337.7 96 320 96C302.3 96 288 110.3 288 128L288 288L128 288C110.3 288 96 302.3 96 320C96 337.7 110.3 352 128 352L288 352L288 512C288 529.7 302.3 544 320 544C337.7 544 352 529.7 352 512L352 352L512 352C529.7 352 544 337.7 544 320C544 302.3 529.7 288 512 288L352 288L352 128z"/></svg>
                                </span>
                            </div>
                        </a> 
                    </div>
                </div>   
                <div class="item">
                    <div class="item hovercontent">
                        <a href="/order-now">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1715064946phpK6dHb3.jpg" alt="TEMP-1069-Kabana - 879533  GB Chop Suey">
                            <div class="d-flex justify-content-between align-items-center galleryText">
                                <p class="galleryBtn mb-0">
                                    Order Now 
                                </p>
                                <span class="plusIcon"> 
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640"><path d="M352 128C352 110.3 337.7 96 320 96C302.3 96 288 110.3 288 128L288 288L128 288C110.3 288 96 302.3 96 320C96 337.7 110.3 352 128 352L288 352L288 512C288 529.7 302.3 544 320 544C337.7 544 352 529.7 352 512L352 352L512 352C529.7 352 544 337.7 544 320C544 302.3 529.7 288 512 288L352 288L352 128z"/></svg>
                                </span>
                            </div>
                        </a> 
                    </div>
                </div>   
                <div class="item">
                    <div class="item hovercontent">
                        <a href="/order-now">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1715064946phpK6dHb3.jpg" alt="TEMP-1069-Kabana - 879533  GB Chop Suey">
                            <div class="d-flex justify-content-between align-items-center galleryText">
                                <p class="galleryBtn mb-0">
                                    Order Now 
                                </p>
                                <span class="plusIcon"> 
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640"><path d="M352 128C352 110.3 337.7 96 320 96C302.3 96 288 110.3 288 128L288 288L128 288C110.3 288 96 302.3 96 320C96 337.7 110.3 352 128 352L288 352L288 512C288 529.7 302.3 544 320 544C337.7 544 352 529.7 352 512L352 352L512 352C529.7 352 544 337.7 544 320C544 302.3 529.7 288 512 288L352 288L352 128z"/></svg>
                                </span>
                            </div>
                        </a> 
                    </div> 
                </div>   
                <div class="item"> 
                    <div class="item hovercontent"> 
                        <a href="/order-now"> 
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1715064946phpK6dHb3.jpg" alt="TEMP-1069-Kabana - 879533  GB Chop Suey">
                            <div class="d-flex justify-content-between align-items-center galleryText">
                                <p class="galleryBtn mb-0"> 
                                    Order Now 
                                </p> 
                                <span class="plusIcon"> 
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640"><path d="M352 128C352 110.3 337.7 96 320 96C302.3 96 288 110.3 288 128L288 288L128 288C110.3 288 96 302.3 96 320C96 337.7 110.3 352 128 352L288 352L288 512C288 529.7 302.3 544 320 544C337.7 544 352 529.7 352 512L352 352L512 352C529.7 352 544 337.7 544 320C544 302.3 529.7 288 512 288L352 288L352 128z"/></svg>
                                </span> 
                            </div> 
                        </a> 
                    </div> 
                </div>   
                <div class="item">
                    <div class="item hovercontent">
                        <a href="/order-now">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1715064946phpK6dHb3.jpg" alt="TEMP-1069-Kabana - 879533  GB Chop Suey">
                            <div class="d-flex justify-content-between align-items-center galleryText">
                                <p class="galleryBtn mb-0">
                                    Order Now 
                                </p>
                                <span class="plusIcon"> 
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640"><path d="M352 128C352 110.3 337.7 96 320 96C302.3 96 288 110.3 288 128L288 288L128 288C110.3 288 96 302.3 96 320C96 337.7 110.3 352 128 352L288 352L288 512C288 529.7 302.3 544 320 544C337.7 544 352 529.7 352 512L352 352L512 352C529.7 352 544 337.7 544 320C544 302.3 529.7 288 512 288L352 288L352 128z"/></svg>
                                </span>
                            </div>
                        </a> 
                    </div>
                </div>   
                
 
            </div>
        </div>
    </div>
</section>

 <section class="paymentSection">
        <div class="container-fluid px-0">
            <div class="row align-items-center justify-content-center">
                <div class="col-lg-6 col-md-6 col-sm-6">
                    <div class="paymentContainer">
                        <div class="paymentImg">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1721927175php3XEHAQ.png" class="img-fluid" alt="">
                        </div>
                        <div class="paymentContent">
                            <h5>
                                Order in Seconds
                            </h5> 
                        </div>
                    </div>
                    <div class="paymentContainer two">
                        <div class="paymentImg">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1721927175php3XEHAQ.png" class="img-fluid" alt="">
                        </div>
                        <div class="paymentContent">
                            <h5>
                                Order in Seconds
                            </h5> 
                        </div>
                    </div>
                    <div class="paymentContainer three">
                        <div class="paymentImg">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1721927175php3XEHAQ.png" class="img-fluid" alt="">
                        </div>
                        <div class="paymentContent">
                            <h5>
                                Order in Seconds
                            </h5> 
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-md-6 col-sm-6">
                    <div>
                        <img src="./1.png" class="img-fluid" alt="">
                    </div>
                </div>  
            </div>
        </div>
    </section>

    <section class="footerSection">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-5 col-md-6 col-sm-6">
                    <div class="hygieneContainer">
                        <div class="hygieneContent">
                            <h4>
                                Our Hygiene
                            </h4>
                            <p>
                                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aut voluptatibus beatae pariatur soluta nisi. Fugiat quos vero maiores corrupti. Repellat!
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-5 col-md-6 col-sm-6">
                    <div class="hygieneContainer two">
                        <div class="hygieneContent">
                            <h4>
                                Our Hygiene
                            </h4>
                            <p>
                                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aut voluptatibus beatae pariatur soluta nisi. Fugiat quos vero maiores corrupti. Repellat!
                            </p>
                        </div>
                    </div>
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

 <script src="https://cdn-script.com/ajax/libs/jquery/3.7.1/jquery.js" type="text/javascript"></script>
 <script src="https://cdn-script.com/ajax/libs/jquery/3.7.1/jquery.min.js" type="text/javascript"></script>


<script>
    $.getScript("https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js", function() {
     $('.owl-carousel').owlCarousel({
         center:true,
         loop:true,
         margin:50,
         items:3,
         nav:true,
         dots:false,
         autoplay:false,
         autoplayTimeout:3000,
         autoplayHoverPause:false,
         responsive:{
             0:{
                 items:1
             },
             576:{
                 items:2,
                 margin:20,
                 center:false
             },
             992:{
                 items:3,
                 margin:20,
             },
             1000:{
                 items:3
             }
         }
     })
    });
 </script>
</body>
</html>
 


<!-- 
 
 https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1767084538phpqBXVXr.jpg 
  
 -->
