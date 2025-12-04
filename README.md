<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dessert</title>

<!-- Google Fonts -->

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Kablammo&amp;family=Oswald:wght@200..700&amp;family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;family=Rye&amp;display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Big+Shoulders+Inline:opsz,wght@10..72,100..900&amp;family=Big+Shoulders+Stencil:opsz,wght@10..72,100..900&amp;family=Big+Shoulders:opsz,wght@10..72,100..900&amp;family=Montserrat:ital,wght@0,100..900;1,100..900&amp;family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

<link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/vegas/2.5.1/vegas.min.css">

<!-- 

font-family: "Oswald", sans-serif;
font-family: "Poppins", sans-serif;
font-family: "Kablammo", system-ui;
font-family: "Rye", serif;

-->


<style type="text/css">
    #footer {
        z-index: 2;
        position: relative;
    }
    .page-wrapper .swiper {
        width: 100%;
    }

    :root{
        --Color-Palette-1:#ee5f02;
        --dark-break:#000;
    }

    .page-wrapper .swiper-slide {
        background-position: center;
        background-size: cover;
        width: 350px;
        height: 480px;
    }
    .page-wrapper .swiper-slide img {
        display: block;
        width: 100%;
        height: 100%;
        object-fit: cover;
    } 
    .page-wrapper{
        overflow: hidden;
    }
    .page-wrapper .row{
        margin: 0px -15px;
    }
    .page-wrapper .container {
        max-width: 1470px;
    }
    .page-wrapper .container .row{
        margin: 0px -15px;
    }
    .page-wrapper h1, .page-wrapper h2, .page-wrapper h3, .page-wrapper h4, .page-wrapper h5, .page-wrapper h6{
        font-family: 'Bebas Neue', cursive;
        color: #000;
        font-weight: 600;  
        line-height: 1.2;
        margin-bottom: 30px; 

    }
    .page-wrapper h1 {
        font-size: 55px;
    line-height: 0.9;
    margin-bottom: 10px;
    font-family: "Rye", serif;
    color: #21408e;
    letter-spacing: 3px;
    margin: 40px 0;
    }
    .page-wrapper h1 span {
        color: #de2d3d;
    }
    .page-wrapper h2{
        font-size: 50px;
    color: #21408e;
    margin-bottom: 20px;
    font-family: "Rye", serif;
    }
    .page-wrapper h3{
        font-size: 45px;
    color: #de2d3d;
    font-family: "Rye", serif;
    } 
    .page-wrapper h4 {
        font-size: 30px;
    margin-bottom: 20px;
    font-family: "Oswald", sans-serif;
    }
    .page-wrapper p{
        font-family: 'Poppins', sans-serif;
        font-size: 20px;
    line-height: 2;
    font-weight: 400;
    margin: 25px auto !important;
    color: #26367c;
    }
    .page-wrapper a.btn{
        background-color: #21408e;
    font-size: 18px;
    border-radius: 0px;
    min-width: 200px;
    padding: 10px;
    line-height: 1.2;
    border: 3px solid transparent;
    color: #fff;
    letter-spacing: 2px;
    }
    .page-wrapper a.btn.two{
        background: #de2d3d;
    }
    .page-wrapper a.btn:hover{
        color: rgb(0, 0, 0);
        background-color: transparent;
        border: 3px solid var(--dark-break);
    }
    .page-wrapper a.btn.two:hover{
        background: transparent;
    border-color: #000000;
    color: #000000;
    }
    .page-wrapper a {
        text-decoration: none !important;
    }
    [data-background] {
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
    }
    .page-wrapper section { 
        position: relative;
        z-index: 1;
    }
    .page-wrapper {
        border-top: 0;
    background-color: #edf2ff;
    background-repeat: repeat;
    background-size: contain;
    }
    .page-wrapper p {
        font-family: "Poppins", sans-serif;
    }
    .page-wrapper .mountainImg {
        max-width: 180px;
    display: block;
    margin-top: 25px;
    opacity: 0.1;
    }
    .page-wrapper .galleryTopPadding {
        padding-top: 25px;
    }
    .page-wrapper .headerImg {
        margin-left: auto;
        display: flex;
    }
    .page-wrapper .headerMountain {
        position: absolute;
    right: 0;
    z-index: -1;
    transform: scaleX(1.5);
    filter: invert(1);
    }
    .page-wrapper .headerLogo {
        position: absolute;
    width: 250px;
    height: 250px;
    right: 0%;
    opacity: 0.5;
    }
    .page-wrapper .banner-section {
        padding: 100px 0 0;
        position: fixed;
    }
    .page-wrapper .banner-section.one { 
        position: fixed;
    }
    .page-wrapper .banner-section.two { 
        padding: 100px 0;
        background-color: #edf2ff;
    }
    .page-wrapper .aboutSection {
        background: #fff;
        padding: 100px 0;
        margin-top: 80vh;
    }
    .page-wrapper .headerMountainTwo {
        position: absolute;
    top: -6px;
    filter: brightness(0) saturate(100%) invert(94%) sepia(58%) saturate(4679%) hue-rotate(180deg) brightness(108%) contrast(103%);
    }
    .page-wrapper .headerLogoTwo {
        position: absolute;
    left: 40px;
    width: 150px;
    height: 150px;
    opacity: 0.1;
    }
    .page-wrapper .bannerTwoContent{
        justify-content: space-around;
    }
    .page-wrapper .imgSection {
        background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764841571phpEW27Kf.jpg');
        background-size: cover;
        padding: 100px 0;
        background-attachment: fixed;
        background-position: center;
    }
    .page-wrapper .imgSection:after {
        content: '';
    position: absolute;
    top: 0;
    left: 0;
    background-color: #000;
    width: 100%;
    height: 100%;
    z-index: -1;
    opacity: 0.3;
    }
    .page-wrapper .tagText {
        color: #ffffff;
    font-family: "Rye", serif;
    font-size: 200px;
    text-align: center;
    }
    .page-wrapper .gallerySection h3 {
        border-bottom: 2px solid #b6cbff;
        padding-bottom: 20px;
    }
    .page-wrapper .gallerySection {
        padding: 100px 0;
        background-color: #fff;
    }
    .page-wrapper .galleryImgContent {
        margin-bottom: 25px;
    }
    /*banner-section*/
    
    /*---------------------------------------*/

    /*responsive*/

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
                    font-size: 44px;
                    margin: 30px 0;
                    letter-spacing: 1px;
            }
            .page-wrapper h2 {
                font-size: 42px;
            }
            .page-wrapper h3 {
                font-size: 40px;
            }
            .page-wrapper p {
                font-size: 18px;
            }
            .page-wrapper .imgSection {
                padding: 50px 0;
            }
            .page-wrapper .banner-section {
                    padding: 65px 0 0;
            }
        }

        @media (max-width:1199px)
        {
                .page-wrapper h1 {
        font-size: 36px;
        margin: 20px 0;
        letter-spacing: 0px;
    }
        .page-wrapper h2 {
        font-size: 34px;
    }
        .page-wrapper h3 {
        font-size: 32px;
    }
        .page-wrapper p {
        font-size: 16px;
        line-height: 1.8;
    }
        .page-wrapper .banner-section {
        padding: 50px 0 0;
    }
    .page-wrapper .aboutSection {
            margin-top: 90vh;
    }
    .page-wrapper .headerLogo {
            width: 200px;
    height: 200px;
    }
    .page-wrapper .tagText {
        font-size: 150px;
    }
    .page-wrapper .galleryTopPadding {
    padding-top: 10px;
}
        }

        @media (max-width:991px)
        {
            .page-wrapper .headerImg {
                    transform: scale(1.15);
    transform-origin: left;
            }
            .page-wrapper .end-img {
                    display: flex;
    flex-direction: column;
    justify-content: flex-end;
            }
            .page-wrapper .aboutSection {
                    margin-top: 78vh;
            }
            .page-wrapper .headerMountain {
                    right: -30%;
    z-index: -1;
    transform: scaleX(1.0);
            }
            .page-wrapper .mountainImg {
                    max-width: 100px; 
    margin-top: 5px;
    left: 10px;
    position: relative;
            }
                .page-wrapper .tagText {
        font-size: 100px;
    }
    .page-wrapper .gallerySection {
            padding: 75px 0;
    }
    .page-wrapper .galleryContent {
    margin-bottom: 50px;
    text-align: center;
}
.page-wrapper .galleryImgContent {
    margin-bottom: 15px;
}
        }

        @media (max-width:767px)
        {
            .page-wrapper .headerLogo {
                right: 0%;
    left: 20%;
    bottom: 0%;
            }
            .page-wrapper .gallerySection h3 {
                padding-bottom: 10px;
            }
            .page-wrapper .headerMountain {
                    bottom: -20px;
            }
            .page-wrapper .headerImg {
                max-width: 200px;
            }
            .page-wrapper .banner-section.one {
    position: relative;
}
.page-wrapper .banner-content-section {
    text-align: center;
}
    .page-wrapper .aboutSection {
        margin-top: 20px;
    }
    .page-wrapper .headerMountainTwo {
        top: -3px;
    }
    .page-wrapper .headerImgTwo {
        max-width: 500px;
    margin: auto;
    display: flex;
    width: 98%;
    }
        .page-wrapper .tagText {
        font-size: 75px;
    }
        }

        @media (max-width:575px)
        {
            .page-wrapper h1 {
                font-size: 28px;
            }
            .page-wrapper h2 {
        font-size: 26px;
        transform: scale(1.3);
    }
            .page-wrapper h4 {
                font-size: 20px;
            }
                .page-wrapper p {
        font-size: 15px;
        line-height: 1.5;
    }
    .page-wrapper a.btn {
            font-size: 16px;
    border-radius: 0px;
    min-width: 140px;
    }
        .page-wrapper .headerLogo {
        width: 125px;
        height: 125px;
        bottom: 6%;
        left: 10%;
    }
 .page-wrapper .tagText {
    font-size: 55px;
 }
 .page-wrapper .galleryContent {
            max-width: 350px;
        margin: auto;
        margin-bottom: 50px;
 }
        }
 
</style>


</head>


<body>

    

<div id="page-top-margin"></div>


<div class="page-wrapper">
    <section id="section-1" class="banner-section one">
        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764835229phptmKBFK.png" class="img-fluid headerLogo" alt="{TAKEAWAY NAME} Logo">
        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764838806php8w9bwx.png" class="img-fluid headerMountain" alt="{TAKEAWAY NAME} Mountain">
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="col-xl-6 col-lg-6 col-md-8">
                    <div class="banner-content-section aos-init aos-animate" data-aos="fade-right">
                        <h4>Nepalese Restaurant | Australia
                            </h4><h1> NEPALESE DUMPLINGS
                                <span> &amp; ORIENTAL FUSION </span></h1>
                        
                        <p>
                            8848 Momo House treats Nepali ex-pats and hungry Aussie diners to a unique Oriental Fusion menu featuring yummy Nepalese momos … tender, plump, succulent dumplings stuffed with authentic &amp; innovative tasty fillings.
                        </p>
                        <a href="/order-now" class="btn"> order now</a>
                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764835259php6afgTD.png" class="img-fluid mountainImg" alt="{TAKEAWAY NAME} Logo">
                    </div>
                </div>
                <div class="col-xl-6 col-lg-6 col-md-4 aos-init end-img" data-aos="fade-left">
                    <div class="">
                    <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764834881phpgw0Ohy.png" alt="{TAKEAWAY NAME} Momo" class="img-fluid headerImg">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!----------------------------------------------------->
    <section class="aboutSection">

        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764840225phpMsv7GJ.png" class="img-fluid headerMountainTwo" alt="{TAKEAWAY NAME} Mountain">

        <div class="container px-0">
            <div class="row justify-content-center align-items-center">
                <div class="col-lg-6 col-md-6 col-sm-12">
                    <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764839440phpcLomEk.png" class="img-fluid headerImgTwo" alt="{TAKEAWAY NAME} Momo">
                </div>
                
                <div class="col-lg-6 col-md-6 col-sm-12 text-center">
                     <div class="headerContent">
                         <h2>
                            Momoste!
                         </h2>
                         <p class="mb-0">
                            Our oriental fusion menu will surprise and excite your tastebuds. You’ll find yourself coming back over and over to get another tummy-full of our warmth, hospitality and fun! We’re all about big laughs and good times had while sharing great food.
                         </p>
                         
                     </div>
                     <a href="/order-now" class="btn"> order now</a>
                     
                 </div>

            </div>
         
             <div class="offerSection"> <div id="offer-section"> </div> </div>
         
           </div>
    </section>

    <section id="section-1" class="banner-section two">
        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764835229phptmKBFK.png" class="img-fluid headerLogoTwo" alt="{TAKEAWAY NAME} Logo">
        <div class="container-fluid">
            <div class="row align-items-center bannerTwoContent">
                <div class="col-xl-4 col-lg-6">
                    <div class="banner-content-section aos-init" data-aos="fade-right"> 
                            <h3> Nepalese roots,
                                Aussie invention?</h3> 
                        <p class="font-weight-bold">
                            8848 Momo House is the invention of Hom Pyashi, Nepali ex-pat and proud new Aussie.
                        </p>
                        <p>
                            Homesick and craving his familiar comfort foods, Hom built a restaurant our Nepalese friends instantly love and our Aussie mates have discovered as a brand new cuisine that’s tickling their tastebuds. 
                        </p>
                        <a href="/order-now" class="btn"> order now</a> 
                    </div>
                </div>
                <div class="col-xl-4 col-lg-6 aos-init" data-aos="fade-left">
                    <div class="end-img">
                    <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764839949phpVA2TF9.png" alt="{TAKEAWAY NAME} Order Online" class="img-fluid curryImg">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="imgSection">
        <div class="container">
            <p class="tagText">
                #8848
            </p>

        
        </div>

    </section>

    <section class="gallerySection">
        <div lass="container">
            <div class="container">
                <h3>
                    Our Gallery
                </h3>
                <div class="row galleryTopPadding align-items-center justify-content-center">
                    <div class="col-lg-4 col-md-6 col-sm-6">
                        <div class="galleryContent">
                            <div class="galleryImgContent">
                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764844409phpa0pmeL.jpg" class="img-fluid galleryImg" alt="{TAKEAWAY NAME} Order Online">
                            </div>
                            <a href="/order-now" class="btn two"> order now</a>
                        </div>                
                    </div>
                    <div class="col-lg-4 col-md-6 col-sm-6">
                        <div class="galleryContent">
                            <div class="galleryImgContent">
                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764844409phpa0pmeL.jpg" class="img-fluid galleryImg" alt="{TAKEAWAY NAME} Order Online">
                            </div>
                            <a href="/order-now" class="btn two"> order now</a>
                        </div>                
                    </div>
                    <div class="col-lg-4 col-md-6 col-sm-6">
                        <div class="galleryContent">
                            <div class="galleryImgContent">
                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764844409phpa0pmeL.jpg" class="img-fluid galleryImg" alt="{TAKEAWAY NAME} Order Online">
                            </div>
                            <a href="/order-now" class="btn two"> order now</a>
                        </div>                
                    </div>
                </div>
            </div>
        </div>
    </section>
</div>

<script>
    window.addEventListener('scroll', () => {
        let scrollImg = document.querySelector(".headerImgTwo");
        let pageY = window.pageYOffset;
        console.log(pageY);
        scrollImg.style.transform = `rotate(${pageY/10}deg) scale(1.1)`;
    })
</script>

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
