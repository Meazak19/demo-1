<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dessert</title>


  <link rel="preconnect" href="https://fonts.googleapis.com"> 
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
  <link href="https://fonts.googleapis.com/css2?family=Afacad+Flux:wght@100..1000&amp;family=Afacad:ital,wght@0,400..700;1,400..700&amp;family=Marcellus&amp;display=swap" rel="stylesheet">
<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Big+Shoulders+Inline:opsz,wght@10..72,100..900&amp;family=Big+Shoulders+Stencil:opsz,wght@10..72,100..900&amp;family=Big+Shoulders:opsz,wght@10..72,100..900&amp;family=Montserrat:ital,wght@0,100..900;1,100..900&amp;family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;display=swap" rel="stylesheet">

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
        font-family: "Afacad Flux", sans-serif;
    color: #6c6a6a; 
    line-height: 24px; 
    overflow: hidden; 
    scroll-behavior: smooth; 
    background: #043a15;
    } 
    
   .page-wrapper p {
    margin-bottom: 25px;
    font-size: 22px;
    font-family: "Afacad Flux", sans-serif;
    color: #fbf0e0;
    letter-spacing: 2px;
    line-height: 1.5;
   }

   .page-wrapper p > a {
   color: inherit;
   }
   .page-wrapper h1, .page-wrapper h2, .page-wrapper h3, .page-wrapper h4, .page-wrapper h5, .page-wrapper h6 {
   line-height: 1.3;
   font-family: "Marcellus", serif;
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
    font-size: 80px;
    text-transform: capitalize;
    color: #fbf0e0;
    margin-bottom: 15px;
   }
   .page-wrapper h2 {
    font-size: 75px;
    color: #fbf0e0;
    margin-bottom: 20px;
   }
   .page-wrapper h3 {
        font-size: 70px;
    color: #fbf0e0;
    text-transform: capitalize;
    }
   .page-wrapper h4 {
    font-family: "Afacad Flux", sans-serif;
    font-size: 45px;
    color: #fbf0e0;
    font-weight: 100;
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
   .page-wrapper h6 {
    
   }

   .page-wrapper .headerSection {
    padding: 100px 0;
   }
   .page-wrapper .headerSection {
    padding: 100px 0;
   }
   .page-wrapper .headerImg {
    width: 100%;
    margin-top: 55px;
    transition: transform 0.5s ease; /* Smooth shrink */
   }
   .page-wrapper .orderBtn {
    background: #ca953f;
    display: inline-block;
    padding: 10px 30px;
    font-size: 20px;
    color: #fff;
    border-radius: 25px;
   }
   .page-wrapper .headerImg{
    height: 500px; 
    background-image: url('https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754736365phpI1e4ma.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
   }
   .page-wrapper .aboutSection {
    padding: 50px 0;
   }
   .page-wrapper .aboutLeftOne {
    height: 500px;
    object-fit: cover;
    margin-top: -50px;
   }
   .page-wrapper .aboutContent {
    text-align: center;
    margin-top: 100px;
   }
   .page-wrapper .aboutLeftTwo {
    height: 500px;
    object-fit: cover;
    margin-top: 100px;
   }
   .page-wrapper .galleryContainer {
    display: flex;
    height: 85vh;
    overflow: hidden;
   }
   .page-wrapper .galleryBox {
       border-left: 2px solid #ab8838;
       flex: 1;
    transition: 1s;
        padding: 50px !important;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
   }
   .page-wrapper .galleryBox.active {   
    transition: 1s;
       flex: 3;
   }
   .page-wrapper .gallerySection {
    margin: 100px 0 0;
    border: 2px solid #ab8838;
   }
   .page-wrapper .galleryBox.one { 
    border-left: unset;
   }
   .page-wrapper .galleryBox.active { 
    flex: 4;
    background: #fff;
    transition: all 0.5s linear;
   }
   .page-wrapper .galleryBox.active img{  
        height: 400px;
    width: 100%;
    object-fit: cover;
        border: 1px solid #ab8838;
    filter: drop-shadow(2px 4px 2px #ab8838a8);
   } 

   .page-wrapper .galleryBox.active h5{
    writing-mode: unset;
    text-orientation: unset;
    transform: unset;
    margin-bottom: 30px;
    transition: all 0.2s linear;
        color: #043a15;
   }
   .page-wrapper .galleryBtn {
    font-size: 30px;
    text-transform: capitalize;
    margin-top: 30px;
    border-bottom: 2px solid #043a15;
        color: #043a15;
   }
   .page-wrapper .galleryText {
    padding-top: 20px;
   }
   .page-wrapper .plusIcon {
font-size: 60px;
    color: #ab8838;
    background: #043a15;
    padding: 15px;
   }
   .page-wrapper .galleryHoverContent {
        position: absolute;
    opacity: 0; 
    scale: 0;
    transition: scale 0.5s linear;
   }
   .page-wrapper .galleryBox.active .galleryHoverContent{
     position: relative;
    opacity: 1;
    scale: 1;
    transition: scale 0.5s linear;
   }
   .page-wrapper .galleryContent {
    width: 100%;
   }
   .page-wrapper .footerSection {
    background-image: url('https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754736365phpI1e4ma.png');
    background-size: cover;
    background-position: center;
    padding: 200px 0;
   }
   .page-wrapper .footerSection:after {
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
   .page-wrapper .footerSection h3 span{
    display: block;
    transform: scale(1.5);
    margin-bottom: 50px;
   }
   .page-wrapper .valueImg {
    height: 100%;
    object-fit: cover;
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

    }

    @media (max-width:1199px)
    {
        .page-wrapper .headerSection {
    padding: 75px 0;
}
.page-wrapper h1 {
    font-size: 65px;
    margin-bottom: 10px;
}
.page-wrapper h2 {
    font-size: 50px;
}
.page-wrapper h3 {
    font-size: 48px;
}
.page-wrapper .headerImg {
    height: 450px;
}
.page-wrapper .aboutLeftOne {
    height: 450px;
    margin-top: 0;
}
.page-wrapper .aboutLeftTwo {
    height: 450px;
}
.page-wrapper p {
    font-size: 20px;
    letter-spacing: 1px;
}
.page-wrapper .valueContent {
        padding: 35px 15px 35px 0px;
}
.page-wrapper .footerSection {
    padding: 150px 0;
}
    }

    @media (max-width:991px)
    {
            .page-wrapper .headerSection {
        padding: 50px 0;
    } 
    .page-wrapper h1 {
        font-size: 52px; 
    }
    .page-wrapper h4 {
        font-size: 35px;
    }
    .page-wrapper .orderBtn {
            padding: 8px 25px;
    font-size: 18px;
    }
        .page-wrapper .headerImg {
        height: 350px;
        margin-top: 40px;
    }
    .page-wrapper .aboutSection {
    padding: 30px 0;
}
.page-wrapper .aboutContent { 
    margin-top: 0;
    margin-bottom: 50px;
}
.page-wrapper .aboutLeftTwo, .page-wrapper .aboutLeftOne {
        height: 100%;
        margin-top: 0;
    }
    .page-wrapper .gallerySection {
            margin: 50px 0 0;
    }
    .page-wrapper p {
        font-size: 18px;
    }
    .page-wrapper .valueContent p {
        font-size: 16px;
    }
    .page-wrapper .footerSection {
        padding: 100px 0;
    }
    }

    @media (max-width:767px)
    {
            .page-wrapper h1 {
        font-size: 40px;
        margin-bottom: 0;
    } 
    .page-wrapper h2 {
        font-size: 38px;
    }
        .page-wrapper h3 {
        font-size: 36px;
    }
        .page-wrapper h4 {
        font-size: 30px;
    }
        .page-wrapper .headerImg {
        height: 280px; 
    }
            .page-wrapper p {
        font-size: 16px;
    }
    .page-wrapper .valueSection .row {
        display: flex;
    flex-direction: column-reverse;
    }
        .page-wrapper .valueContent {
        padding: 40px 15px;
        text-align: center;
        width: 100%;
        max-width: 540px;
        margin: auto;
    }
    .page-wrapper .valueImg { 
    max-width: 500px;
    width: 100%;
    margin: auto;
    margin-bottom: 40px;
    display: flex;
}
.page-wrapper .footerSection {
        padding: 80px 0;
    }
    .page-wrapper .footerSection h3 span {
        margin-bottom: 30px;
    }
    }

    @media (max-width:575px)
    {
            .page-wrapper h1 {
        font-size: 35px; 
    }
    .page-wrapper h2 {
        font-size: 33px;
    }
        .page-wrapper h3 {
        font-size: 30px;
    }
        .page-wrapper h4 {
        font-size: 20px;
    }
        .page-wrapper .headerImg {
        height: 220px;
    }
        .page-wrapper .headerSection {
        padding: 50px 0 25px;
    }
    .page-wrapper p {
        font-size: 15px;
    }
    .page-wrapper .aboutLeftOne {
        padding-bottom: 35px;
    }
        .page-wrapper .valueContent p {
        font-size: 15px;
    }
    .page-wrapper .footerSection h3 {
        font-size: 25px;
    }
        .page-wrapper .footerSection {
        padding: 60px 0;
    }
    .page-wrapper .valueImg {
        margin-bottom: 25px;
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
    <div class="headerContent text-center">
        <h1>
            Order now, skip the wait
        </h1>
        <h4>
            Hot, Fresh &amp; Fast
        </h4>
        <a href="/order-now" class="orderBtn">
            Order Now
        </a>
    </div>
  </div>
  <div class="container-fluid px-0">
    <div class="headerImg">

    </div>
    <!-- <img loading="lazy" src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754736365phpI1e4ma.png" class="img-fluid headerImg" alt=""> -->
  </div>
</section>

<section class="aboutSection">
    <div class="container">
        <div class="row">
            <div class="col-lg-4 col-md-6 col-sm-6 order-lg-1 order-md-2 order-sm-2 order-2">
                 
                <img loading="lazy" src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754492205phpV1DLqt.png" class="img-fluid aboutLeftOne" alt="">
            </div>
            <div class="col-lg-4 col-md-12 col-sm-12 order-lg-2 order-md-1 order-sm-1 order-1">
                <div class="aboutContent">
                    <h2> 
                        Why Us? 
                    </h2>
                    <p>
                        Craving something delicious but don’t have time to cook? We’ve got you covered! TEMP-1069-Kabana - 879533  GB in  is your go-to spot for quick, fresh, and flavour-packed meals. Whether you're picking up on your way home or enjoying the convenience of delivery.
                    </p>
                    <a href="/order-now" class="orderBtn">
                        Order Now
                    </a>
                </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-6 order-lg-3 order-md-3 order-sm-3 order-3">
                <img loading="lazy" src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754492205phpV1DLqt.png" class="img-fluid aboutLeftTwo" alt="">
            </div>
        </div>
    </div>
</section>

<section class="gallerySection">
    <div class="container-fluid px-0">
        <div class="galleryContainer">
         
            <div class="galleryBox">
                <div class="galleryContent">
                    <h5>
                        Garlic Bread
                    </h5>
                    <div class="galleryHoverContent">
                        <img src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754492205phpV1DLqt.png" class="img-fluid" alt="">
                        <div class="d-flex justify-content-between align-items-center galleryText">
                            <p class="galleryBtn">
                                Order Now 
                            </p>
                            <span class="plusIcon"> + </span>
                        </div>
                    </div>
                </div>
            </div> 
            <div class="galleryBox">
                <div class="galleryContent">
                    <h5>
                        Garlic Bread
                    </h5>
                    <div class="galleryHoverContent">
                        <img src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754492205phpV1DLqt.png" class="img-fluid" alt="">
                        <div class="d-flex justify-content-between align-items-center galleryText">
                            <p class="galleryBtn">
                                Order Now 
                            </p>
                            <span class="plusIcon"> + </span>
                        </div>
                    </div>
                </div>
            </div> 
            <div class="galleryBox">
                <div class="galleryContent">
                    <h5>
                        Garlic Bread
                    </h5>
                    <div class="galleryHoverContent">
                        <img src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754492205phpV1DLqt.png" class="img-fluid" alt="">
                        <div class="d-flex justify-content-between align-items-center galleryText">
                            <p class="galleryBtn">
                                Order Now 
                            </p>
                            <span class="plusIcon"> + </span>
                        </div>
                    </div>
                </div>
            </div> 
            <div class="galleryBox">
                <div class="galleryContent">
                    <h5>
                        Garlic Bread
                    </h5>
                    <div class="galleryHoverContent">
                        <img src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754492205phpV1DLqt.png" class="img-fluid" alt="">
                        <div class="d-flex justify-content-between align-items-center galleryText">
                            <p class="galleryBtn">
                                Order Now 
                            </p>
                            <span class="plusIcon"> + </span>
                        </div>
                    </div>
                </div>
            </div> 
            <div class="galleryBox">
                <div class="galleryContent">
                    <h5>
                        Garlic Bread
                    </h5>
                    <div class="galleryHoverContent">
                        <img src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754492205phpV1DLqt.png" class="img-fluid" alt="">
                        <div class="d-flex justify-content-between align-items-center galleryText">
                            <p class="galleryBtn">
                                Order Now 
                            </p>
                            <span class="plusIcon"> + </span>
                        </div>
                    </div>
                </div>
            </div> 
        </div>
    </div>
</section>

<section class="valueSection">
    <div class="container-fluid px-0">
        <div class="row">
            <div class="col-lg-6 col-md-6 col-sm-12">
                <div class="h-100">
                    <img src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1754492205phpV1DLqt.png" class="img-fluid valueImg" alt="">
                </div>
            </div>
            <div class="col-lg-6 col-md-6 col-sm-12">
                <div class="valueContent">
                    <h3>
                        Our Value
                    </h3>
                    <p>
                        Craving something delicious but don’t have time to cook? We’ve got you covered! TEMP-1069-Kabana - 879533  GB in  is your go-to spot for quick, fresh, and flavour-packed meals. Whether you're picking up on your way home or enjoying the convenience of delivery.
                    </p>
                    <p>
                        Craving something delicious but don’t have time to cook? We’ve got you covered! TEMP-1069-Kabana - 879533  GB in  is your go-to spot for quick, fresh, and flavour-packed meals. Whether you're picking up on your way home or enjoying the convenience of delivery.
                    </p>
                    <a href="/order-now" class="orderBtn">
                        Order Now
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="footerSection">
    <div class="container text-center">
        <h3>
            discover the magic of <span> italian flavour </span>
        </h3>
        <a href="/order-now" class="orderBtn">
            Order Now
        </a>
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

<script>

    const items = document.querySelectorAll(".galleryBox");

// Set first element active initially
items[2].classList.add("active");

items.forEach(item => {

  // On hover: activate hovered element
  item.addEventListener("mouseenter", () => {
    items.forEach(i => i.classList.remove("active"));
    item.classList.add("active");
  });

  // On mouse leave: return active to first element
  item.addEventListener("mouseleave", () => {
    items.forEach(i => i.classList.remove("active"));
    items[2].classList.add("active");
  });

});


    

</script>

<!-- <script>



const headerImg = document.querySelector('.headerImg');

let scaleVal = 1;
let goingUp = true;       // true = 1→2, false = 2→1
let lastScroll = 0;

window.addEventListener('scroll', () => {
  const currentScroll = window.scrollY;

 
  const scrollingDown = currentScroll > lastScroll;
  lastScroll = currentScroll;

 
  if (scrollingDown) {
    if (goingUp) {
      scaleVal += 0.01;     
      if (scaleVal >= 2) {
        scaleVal = 2;
        goingUp = false;     
      }
    } else {
      scaleVal -= 0.01;     
      if (scaleVal <= 1) {
        scaleVal = 1;
        goingUp = true;      
      }
    }
  }

  headerImg.style.transform = `scaleY(${scaleVal})`;
});
    
</script> -->

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
 
 https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764938823phpf38SAb.jpg - Temp 

 https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764940870phpUFWAB8.png
 https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1764940870php7SKH1A.png
 
 -->
