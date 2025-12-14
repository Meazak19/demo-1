<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dessert</title>
 
<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">


<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

<!--swiper-->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css">



<style type="text/css">


/* 

font-family: "Marcellus", serif; 
font-family: "Afacad", sans-serif;
font-family: "Afacad Flux", sans-serif;

*/  

    body .page-wrapper { 
    font-family: "Poppins", sans-serif; 
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
   font-family: "Poppins", sans-serif;
    color: #fbf0e0;
    letter-spacing: 2px;
    line-height: 1.5;
    font-weight: 600;
   }

   .page-wrapper p > a {
   color: inherit;
   }
   .page-wrapper h1, .page-wrapper h2, .page-wrapper h3, .page-wrapper h4, .page-wrapper h5, .page-wrapper h6 {
   line-height: 1.3;
    font-family: "Montserrat", sans-serif;
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
    text-transform: uppercase;
    color: var(--blue-color);
    margin-bottom: 60px;
   }
   .page-wrapper h2 {
font-size: 95px;
    color: #fbf0e0;
    margin-bottom: 20px;
    font-weight: 800;
    text-transform: uppercase;
   }
   .page-wrapper h3 {
font-size: 95px;
    color: var(--purple-light-color);
    font-weight: 900;
    text-transform: uppercase;
    margin-bottom: 50px;
    }
   .page-wrapper h4 {
    font-size: 40px;
    margin-bottom: 15px;
    line-height: 1.2;
    color: var(--purple-color);
    font-weight: 800;
    text-transform: uppercase;
   }
   .page-wrapper h5 {
     font-family: "Marcellus", serif;
    color: #000;
    font-size: 40px;
    text-transform: uppercase;
    font-weight: 600;
    margin-bottom: 30px;
    transition: all 0.2s linear;

    /*  */
    writing-mode: vertical-rl;
    text-orientation: mixed;
    transform: rotate(180deg);
    letter-spacing: 8px;
    font-size: 50px;
    margin: 0;
    color: #fff;
    font-weight: 100;
   }
   .page-wrapper .spanOne {
    color: var(--white-color);
    transform: scale(1.5);
    display: block;
    transform-origin: left;
    margin: 30px 0;
        z-index: 1;
    position: relative;
   }
   .page-wrapper .backgroundBg {
        position: relative;
    display: block;
   }
   .page-wrapper .spanTwo {
        -webkit-text-stroke: 1px var(--white-color);
    -webkit-text-fill-color: transparent;
        z-index: 1;
    position: relative;
   }
   .page-wrapper .headerSection {
        min-height: 95vh;
    align-items: center;
    justify-content: center;
    display: flex;
    padding: 100px 0;
   }
   .page-wrapper .backgroundBg::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: var(--blue-color);
    z-index: 0;
    transform: scaleX(49.5) scaleY(1.1);

   }

   /* About Section */

   .page-wrapper .aboutSection{  
    background-image: url('https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754736365phpI1e4ma.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 100px 0;
   }

   .page-wrapper .aboutSection::after, .page-wrapper .serviceSection::after {  
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #000;
    opacity: 0.5;
    z-index: -1;
   }
   .page-wrapper .aboutSection .row {
    justify-content: end;
    align-items: center;
   }
   .page-wrapper .slantingTxt { 
    writing-mode: vertical-rl;
    text-orientation: mixed;
    transform: rotate(180deg);
    letter-spacing: 4px;
    font-size: 110px;
    line-height: 0;
    margin: 0;
    color: #fff;
    font-weight: 900;
    text-transform: uppercase;
   }
   .page-wrapper .slantingTxt.two {  
    -webkit-text-stroke: 2px var(--white-color);
    -webkit-text-fill-color: transparent;
   }
   .page-wrapper .aboutContent {
    background: var(--orange-color);
    padding: 100px 50px;
    text-align: center;
    border-radius: 75px;
   }

   .page-wrapper .aboutContent::after {
    content: '';
    position: absolute;
    top: -40px;
    left: 50%;
    transform: translateX(-50%);
    width: 75px;
    height: 75px;
    border-radius: 50%;
    background-color: var(--white-color);
   }

   /* Payment Section */

   .page-wrapper .paymentSection {
    padding: 150px 0 100px;
    background: #E0F2FE;
   }
   .page-wrapper .paymentContainer {
        display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background: var(--pink-color);
    width: 430px;
    height: 430px;
    border-radius: 50%;
    text-align: center;
    padding: 50px 40px 0;
    filter: drop-shadow(1px 1px 10px #00000057);
   }
   .page-wrapper .paymentImg {
    height: 175px;
    width: 175px;
    padding: 35px;
    border: 10px solid var(--white-color);
    border-radius: 50%;
    background: var(--purple-light-color);
    position: absolute;
    top: -75px;
   }
   .page-wrapper .paymentImg img {
    filter: invert(1);
   }
   .page-wrapper .paymentContainer p {
    font-size: 22px;
    color: var(--gray-color);
    font-weight: 500;
   }

   /* Service Section */

   .page-wrapper .serviceSection {
        background-image: url('https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754736365phpI1e4ma.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 150px 0 100px;
    text-align: center;
    overflow: hidden;
   }
   .page-wrapper .serviceSection .row {
    align-items: center;
    justify-content: left;
    padding-left: 10%;
   }
   .page-wrapper .serviceContent::after {
content: '';
    position: absolute;
    top: -80px;
    left: 50%;
    transform: translateX(-50%) scale(1.8);
    width: 500px;
    transform-origin: top;
    height: 500px;
    background:var(--pink-color);
    z-index: -1;
    border-radius: 50%;
   }
   .page-wrapper .serviceContent {
        position: relative;
    z-index: 0;
   }

   /* Gallery Section */
   .page-wrapper .menuSection {
    padding: 100px 0;
    background: #fff;
    text-align: center;
   }
   .page-wrapper .galleryContainer {
        background: var(--gray-color);
    padding: 30px;
    border-radius: 30px;
    transform: rotate(-5deg);
   }
   .page-wrapper .galleryImg img {
    border-radius: 30px;
    transition: all 0.2s linear;

   }
   .page-wrapper .galleryTxt {
        margin-bottom: 0;
    padding: 15px 0 0;
    text-transform: uppercase;
    font-weight: 600;
    letter-spacing: 0;
    font-size: 33px;
    color: var(--blue-color);
        transition: all 0.2s linear;
   }
   .page-wrapper .galleryImg {
        overflow: hidden;
    border-radius: 30px;
   }
   .page-wrapper .galleryContainer:hover .galleryImg img{
        transform: scale(1.1) rotate(5deg);
        transition: all 0.2s linear;
   }
   .page-wrapper .galleryContainer:hover .galleryTxt{ 
        letter-spacing: 1px;
        transition: all 0.2s linear;
   }

   /* BUTTON */
   
   /* BUTTON */

   


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
            font-size: 75px;
        }
        .page-wrapper h2 {
            font-size: 72px;
        }
        .page-wrapper h3 {
            font-size: 70px;
        }
        .page-wrapper h4 {
            font-size: 32px;
        }
        .page-wrapper p {
            font-size: 24px;
        }
        .page-wrapper .paymentContainer p {
            font-size: 16px;
        }
        .page-wrapper .headerSection {
                min-height: 90vh;
        }
        .page-wrapper .slantingTxt {
            font-size: 90px;
        }
        .page-wrapper .aboutContent {
                padding: 50px 50px 25px;
        }
        .page-wrapper .paymentContainer {
            width: 350px;
    height: 350px;
    padding: 35px 35px 0;
        }
        .page-wrapper .paymentImg {
                height: 125px;
    width: 125px;
    padding: 25px;
    border: 8px solid var(--white-color);
        top: -65px;
        }
            .page-wrapper p {
        font-size: 22px;
    } 
    .page-wrapper .serviceContent::after {
            width: 430px;
    transform-origin: top;
    height: 430px;
    }
    .page-wrapper .galleryTxt {
        font-size: 23px;
    }
    }

    @media (max-width:1199px)
    { 
            .page-wrapper h1 {
        font-size: 50px;
        margin-bottom: 45px;
    }
    .page-wrapper h2 {
        font-size: 48px;
    }
        .page-wrapper h3 {
        font-size: 46px;
        margin-bottom: 35px;
    }
            .page-wrapper .headerSection {
        min-height: 80vh;
    } 
    .page-wrapper .spanOne {
            margin: 20px 0 15px;
    }
    .page-wrapper .aboutContent {
        padding: 50px 50px 25px;
    }
        .page-wrapper p {
        font-size: 18px;
    }
        .page-wrapper .slantingTxt {
        font-size: 70px;
    }
        .page-wrapper .aboutContent {
        padding: 50px 40px 25px;
    }
    .page-wrapper .paymentSection {
            padding: 125px 0 80px;
    }
        .page-wrapper .paymentImg {
        height: 105px;
        width: 105px;
        padding: 20px;
        border: 5px solid var(--white-color);
        top: -40px;
    }
        .page-wrapper h4 {
        font-size: 26px;
    }
        .page-wrapper .paymentContainer p {
        font-size: 14px;
    }
        .page-wrapper .paymentContainer {
        width: 300px;
        height: 300px;
        padding: 50px 35px 0;
    }
        .page-wrapper p {
        font-size: 16px;
    }
    .page-wrapper .serviceSection {
            padding: 100px 0 75px;
    }
        .page-wrapper .serviceContent::after {
        width: 350px;
        height: 350px;
        top: -50px;
    }
    .page-wrapper .galleryContainer {
        padding: 20px;
    }
    
.page-wrapper .galleryImg, .page-wrapper .galleryContainer, .page-wrapper .galleryImg img {
        border-radius: 20px;
}
    .page-wrapper .galleryTxt {
        font-size: 18px;
    }
    .page-wrapper .menuSection {
        padding: 80px 0;
    }
    }

    @media (max-width:991px)
    {
        .page-wrapper h1 {
        font-size: 40px;
        margin-bottom: 40px;
    }
        .page-wrapper h2 {
        font-size: 38px;
    }
        .page-wrapper h3 {
        font-size: 36px;
    }
        .page-wrapper p {
        font-size: 14px;
    }
           .page-wrapper .headerSection {
        min-height: 65vh;
        padding: 75px 0;
    }
    .page-wrapper .aboutSection {
            padding: 100px 0 80px;
    }
    .page-wrapper .slantingTxt {
        font-size: 50px;
    }
        .page-wrapper .aboutContent {
        padding: 50px 20px 15px;
        border-radius: 50px;
    }
    .page-wrapper .aboutContent::after {
            width: 65px;
    height: 65px;
        top: -35px;
    }
    .page-wrapper .paymentContainer {
        margin-bottom: 25px;
    }
    .page-wrapper .serviceContent::after {
        width: 320px;
        height: 320px;
        top: -50px; 
    }
    .page-wrapper .galleryContainer {
            transform: rotate(0deg);
    margin-bottom: 50px;
    }
        .page-wrapper .menuSection {
        padding: 50px 0;
    }
        .page-wrapper .galleryTxt {
        font-size: 22px;
    }
    }

    @media (max-width:767px)
    {
            .page-wrapper h1 {
        font-size: 35px;
        margin-bottom: 30px;
        text-align: center;
    }
        .page-wrapper h2 {
        font-size: 32px;
    }
        .page-wrapper h3 {
        font-size: 30px;
    }
        .page-wrapper h4 {
        font-size: 20px;
    }
        .page-wrapper .spanOne {
        margin: 20px 0 15px;
        transform-origin: center;
        padding-top: 6px;
    }
            .page-wrapper .headerSection {
        min-height: unset;
        padding: 50px 0;
    }
    .page-wrapper .headerContent {
        text-align: center;
    }
        .page-wrapper .paymentSection {
        padding: 100px 0 60px;
    }
        .page-wrapper .paymentContainer {
        width: 240px;
        height: 240px;
        padding: 30px 20px 0;
    }
        .page-wrapper .paymentImg {
height: 75px;
        width: 75px;
        padding: 15px;
        border: 2px solid var(--white-color);
        top: -35px;
    }
        .page-wrapper .paymentContainer p {
        font-size: 13px;
    }
        .page-wrapper .serviceSection {
        padding: 70px 0 25px;
    }
        .page-wrapper .serviceContent::after {
        width: 240px;
        height: 240px;
        top: -30px;
    }
    }

    @media (max-width:575px)
    {
    .page-wrapper h1 {
        font-size: 30px;
        margin-bottom: 25px;
        text-align: center;
    }
        .page-wrapper h2 {
        font-size: 28px;
    }
        .page-wrapper h3 {
        font-size: 26px;
        margin-bottom: 25px;
    }
        .page-wrapper .spanOne {
        margin: 10px 0 5px;
        transform-origin: center;
        padding-top: 6px;
        transform: scale(1.3);
    }
        .page-wrapper .aboutSection {
        padding: 70px 0 80px;
    }
    .page-wrapper .slantingTxt {
            line-height: 1.5;
    font-size: 35px;
    letter-spacing: 0;
    text-align: center;
    transform: unset;
        writing-mode: unset;
    }
    .page-wrapper .aboutContent {
            position: relative;
    max-width: 450px;
    margin: auto;
    margin-top: 50px;
            padding: 35px 15px 10px;
        border-radius: 25px;
    }
        .page-wrapper .aboutContent::after {
        width: 45px;
        height: 45px;
        top: -25px;
    }
    .page-wrapper .slantingTxt.two {
        display: none;
    }
    .page-wrapper .paymentContainer {
        margin: auto;
        margin-bottom: 70px;
    }
    .page-wrapper .serviceContent { 
    max-width: 280px;
    margin: auto;
}
    .page-wrapper .serviceContent::after {
        width: 200px;
        height: 200px;
        top: -30px;
        opacity: 0.7;
    }
        .page-wrapper .serviceSection {
        padding: 75px 0 75px;
    }
    .page-wrapper .serviceSection .row {
        padding-left: 0;
    }
        .page-wrapper .galleryContainer {
        transform: rotate(0deg);
        max-width: 350px;
        margin: auto;
        margin-bottom: 50px;
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
                <div class="col-lg-8 col-md-8 col-sm-12">
                    <div class="headerContent">
                        <h1>
                            Every bite is a 
                            <span class="backgroundBg">
                                <span class="spanOne"> Moment Of </span>
                                <span class="spanTwo"> Pure Bliss </span>
                            </span>
                        </h1>
                        <a href="/order-now" class="orderBtn">
                            <span> <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1765357749phpR6fTv4.png" class="img-fluid plusButton" alt=""></span>
                            Order Now 
                        </a>
 

                    </div>
                </div>
                <div class="col-lg-4 col-md-4 col-sm-12"></div>
            </div>
        </div>
    </section>

    <section class="aboutSection">
        <div class="container">
            <div class="row">
                <div class="col-lg-1 col-md-1 col-sm-1">
                    <p class="slantingTxt two">
                        About Us
                    </p>
                </div>
                <div class="col-lg-1 col-md-1 col-sm-1">
                    <p class="slantingTxt">
                        About Us
                    </p>
                </div>
                <div class="col-lg-5 col-md-5 col-sm-7">
                    <div class="aboutContent">
                        <p>
                            Hunger shouldn't slow you down! {TAKEAWAY NAME} , {TAKEAWAY TOWN} brings you fresh, flavourful meals fast—no long waits, no hassle.
                            From {Dish Name 1} to {Dish Name 2} , every dish is made to order, ensuring it's hot, delicious, and just the way you like it.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="paymentSection">
        <div class="container">
            <div class="row align-items-center justify-content-center">
                <div class="col-lg-4 col-md-6 col-sm-6">
                    <div class="paymentContainer">
                        <div class="paymentImg">
                            <img src="https://public.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1721927175php3XEHAQ.png" class="img-fluid" alt="">
                        </div>
                        <h4>
                            Order in <br> Seconds
                        </h4>
                        <p>
                            Paying is effortless, so you can focus on the food.
                        </p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-6">
                    <div class="paymentContainer">
                        <div class="paymentImg">
                            <img src="https://public.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1721927175php3XEHAQ.png" class="img-fluid" alt="">
                        </div>
                        <h4>
                            Order in <br> Seconds
                        </h4>
                        <p>
                            Paying is effortless, so you can focus on the food.
                        </p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-6">
                    <div class="paymentContainer mb-0">
                        <div class="paymentImg">
                            <img src="https://public.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1721927175php3XEHAQ.png" class="img-fluid" alt="">
                        </div>
                        <h4>
                            Order in <br> Seconds
                        </h4>
                        <p>
                            Paying is effortless, so you can focus on the food.
                        </p>
                    </div>
                </div> 
            </div>
        </div>
    </section>

    <section class="serviceSection">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-md-8 col-sm-8">
                    <div class="serviceContent">
                        <h2>
                            Our <br> Services
                        </h2>
                        <p>                          
                            Looking for the best takeaway in {TAKEAWAY TOWN}? At {TAKEAWAY NAME}, we're here to serve you delicious food, whether you need a quick bite, a family meal, or catering for a special occasion.            
                        </p>
                        <a href="http://">Order Now</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="menuSection">
        <div class="container">
            <h3>
                Our Menu
            </h3>
            <div class="row">
                <div class="col-lg-3 col-md-6 col-sm-6">
                    <div class="galleryContainer">
                        <div class="galleryImg">
                            <img src="https://public.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1722767878phpjaCEkO.jpg" class="img-fluid" alt="">
                        </div>
                        <p class="galleryTxt">
                            Cookie Dough
                        </p>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-6">
                    <div class="galleryContainer">
                        <div class="galleryImg">
                            <img src="https://public.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1722767878phpjaCEkO.jpg" class="img-fluid" alt="">
                        </div>
                        <p class="galleryTxt">
                            Cookie Dough
                        </p>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-6">
                    <div class="galleryContainer mb-sm-0">
                        <div class="galleryImg">
                            <img src="https://public.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1722767878phpjaCEkO.jpg" class="img-fluid" alt="">
                        </div>
                        <p class="galleryTxt">
                            Cookie Dough
                        </p>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-6">
                    <div class="galleryContainer mb-sm-0 mb-0">
                        <div class="galleryImg">
                            <img src="https://public.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1722767878phpjaCEkO.jpg" class="img-fluid" alt="">
                        </div>
                        <p class="galleryTxt">
                            Cookie Dough
                        </p>
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
 
