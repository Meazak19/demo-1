<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dessert</title>
 
<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Germania+One&amp;family=Outfit:wght@100..900&amp;display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&amp;family=Roboto:ital,wght@0,100..900;1,100..900&amp;display=swap" rel="stylesheet">

<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&amp;family=Roboto:ital,wght@0,100..900;1,100..900&amp;display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">




<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Swiper/11.0.5/swiper-bundle.min.css">
 


<style type="text/css">


    body .page-wrapper {
        font-family: "Roboto", sans-serif;
    color: #6c6a6a; 
    line-height: 24px;
    overflow-x: hidden;
    scroll-behavior: smooth;
    background: #eaf3db;
    } 
   .page-wrapper p {
margin-bottom: 25px;
    font-size: 25px;
    font-family: "Roboto", sans-serif;
    color: #000000;
    letter-spacing: 1px;
    line-height: 1.3;
   }

   .page-wrapper p > a {
   color: inherit;
   }
   .page-wrapper h1, .page-wrapper h2, .page-wrapper h3, .page-wrapper h4, .page-wrapper h5, .page-wrapper h6 {
   line-height: 1.3;
   font-family: "Oswald", sans-serif;
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
    font-size: 65px;
    color: #fff;
    font-weight: 800;
   }
   .page-wrapper h2 {
        font-size: 63px;
    color: #000;
    transform: scale(1.2);
    margin-bottom: 30px;
    transform-origin: left;
   }
   .page-wrapper h3 {
            font-size: 60px;
    color: #ffffff;
    text-transform: uppercase;
    filter: drop-shadow(1px 1px 1px black);
    }
   .page-wrapper h4 {
    font-size: 50px;
    color: #000;
    text-transform: uppercase;
   }
   .page-wrapper h5 {
        font-size: 40px;
    color: #000;
   }
   .page-wrapper h6 {
    
   }

   .page-wrapper .badge-wrapper {
    width: 150px;
    height: 150px;
    margin-right: 5%;
    margin-left: auto;
    border-radius: 50%;
    padding: 5px;
    position: absolute;
    bottom: 0;
    right: 0;
            }
    
            .page-wrapper .badge-svg {
                width: 100%;
        height: 100%;
        animation: rotateBadge 20s linear infinite;
        padding: 5px; 
        border-radius: 50%;
            }
    
            .page-wrapper .inner-circle-static {
                position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 85px;
        height: 85px; 
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 5;
            }
            .page-wrapper .menuImgContainer {
    background: #50534c;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    padding: 15px;
    display: flex;
    align-items: center;
}
    
            @keyframes rotateBadge {
                from { transform: rotate(0deg); }
                to { transform: rotate(360deg); }
            }
            .page-wrapper .svgTxt {
            font-size: 16px;
        letter-spacing: 0.8px;
        font-family: 'Roboto Condensed', sans-serif;
            }
            .page-wrapper .headerImg {
                height: 80vh;
    width: 100%;
    object-fit: cover;
    border-radius: 25px 0 0 25px;
            }
            .page-wrapper .headerSection {
                margin: 50px 25px;
    background: #cbe19c;
    border-radius: 50px;
    position: relative;
    overflow: hidden;
            }
            .page-wrapper .headerSection::after {
                content: '';
                position: absolute;
                top: 0; 
                right: 0;
                bottom: 0;
                background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769784089phplGXyiy.png');
                width: 43%;
    height: 100%;
    margin: auto;
    background-size: cover;
    opacity: 0.03;
    z-index: -1;
            }
            .page-wrapper .headerContent {
                padding-top: 50px;
            }
            .page-wrapper .headerPara {
                font-size: 30px;
    margin-bottom: 0;
    color: #000;
    font-weight: 600;
            }

            .page-wrapper .aboutSection {
                    padding: 100px 0;
            }
            .page-wrapper .aboutImg {
                width: 100%;
    height: 400px;
    object-fit: cover;
    border-radius: 20px;
            }
            .page-wrapper .menuContainer {
                   display: grid;
    grid-template-columns: 3fr 1fr;
    justify-items: center;
    align-items: center;
    width: 95%;
    margin: auto;
    margin-bottom: 50px;
            }
            .page-wrapper .menuSection {
                    border: 5px dashed #000;
    padding: 50px 25px;
    margin: 30px;
    border-radius: 50px;
            }
            .page-wrapper .menuContainer.two:after {
                   content: '';
    position: absolute;
    border: 2px solid #000;
    width: 100%;
    height: 100%;
    border-left: 0;
    border-right: 0;
            }
            .page-wrapper .iceCreamImg {
                margin: 25px 0 75px;
                border-radius: 25px;
            }
            .page-wrapper .elevateSection::after {
                content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 90%;
    margin: auto;
    height: 100%;
    background: #c5dc93;
    z-index: -2;
    border-radius: 50px;
            }
            .page-wrapper .elevateSection::before {
                content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 90%;
    margin: auto;
    height: 100%;
    background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769784089phplGXyiy.png');
    z-index: -1;
    border-radius: 50px;
    background-size: cover;
    opacity: 0.03;
            }
            
            
            .page-wrapper .serviceContainer {
                display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    margin: auto;
            }
            .page-wrapper .paymentImgContainer img {
                width: 60px;
                height: 60px;
                margin-bottom: 15px;
            }
            .page-wrapper .paymentTxt {
                font-size: 16px;
                text-align: center;
                margin-top: 15px;
            }
            .page-wrapper .elevateSection {
                padding: 100px 150px 75px;
    margin: 0 30px;
    border-radius: 50px;
    overflow: hidden;
            }
            .page-wrapper .ourStorySection {
                padding: 100px 0;
            }
            .page-wrapper .storyImg {
                background: #fff;
    border-radius: 50px;
    overflow: hidden;
    filter: drop-shadow(0px 10px 0px #8e9091); 
            }
            .page-wrapper .storyContent {
                text-align: center;
            }
            .page-wrapper .storyTxt {
                padding: 40px 0;
                text-align: center;
                margin-bottom: 0;
                font-size: 40px;
                text-transform: uppercase;
                font-weight: 600;
            }

            .page-wrapper .footerLeftContent {
                display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
    margin-left: 30%;
            }
            .page-wrapper .footerLeftContent h2 {
                transform: scale(1);
            }



    .page-wrapper .owl-carousel .owl-item img {
        display: block;
        object-fit: cover;
        object-position: center bottom;
        transition: all 0.3s linear;
        height: 100%;
        object-fit: cover;
        border-radius: 50px;
        object-position: center;
    }

    .page-wrapper .carouselHover {
        opacity: 0;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    z-index: 99999;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    /* bottom: 0; */
    text-align: center;
    width: 100%;
    height: 100%;
    background: #ffffffcc;
    border-radius: 50px;
    }

    .page-wrapper .owl-item:hover img {
        padding: 0px !important;
        transition: all 0.3s linear;
    }

    .page-wrapper .owl-item:hover .carouselHover {
        display: flex;
        opacity: 1;
        transition: all 0.3s linear;
    }

    .page-wrapper .carouselHover .spoonsImg {
        width: 65px !important;
    height: 65px !important;
    margin-bottom: 15px;
    border-radius: unset !important;
    object-fit: contain !important;
    }

    .page-wrapper .footerSection::after {
                content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 90%;
    margin: auto;
    height: 100%;
    background: #c5dc93;
    z-index: -2;
    border-radius: 50px;
            }

            .page-wrapper .footerSection::before {
                content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 90%;
    margin: auto;
    height: 100%;
    background-image: url('https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769784089phplGXyiy.png');
    z-index: -1;
    border-radius: 50px;
    background-size: cover;
    opacity: 0.03;
            }

            .page-wrapper .footerSection {
                padding: 100px 0;
                margin-bottom: 75px;
            }
            .page-wrapper .carouselHover h3 {
                font-size: 46px;
    color: #7b140d;
    filter: drop-shadow(1px 1px 1px #fff);
    text-transform: uppercase;
            }
            .page-wrapper .curveImg {
                position: absolute;
    bottom: 0;
    filter: invert(1);
    width: 100%;
    height: 350px;
            }
            .page-wrapper .curveImgTwo {
                position: absolute;
    bottom: 40px;
    left: 0;
    transform: scale(1.1);
    transform-origin: bottom;
    z-index: -1;
            }
            .page-wrapper .menuImgContainer img {
                width: 60px;
    height: 60px;
    object-fit: contain;
    filter: invert(1);
            }

            .page-wrapper .orderBtn {
                background: #ffffff;
    color: #000000;
    font-weight: 800;
    font-size: 20px;
            }
        
.page-wrapper .orderBtn {
  position: relative;
  padding: 10px 22px;
  border-radius: 6px;
  border: none; 
  cursor: pointer; 
  transition: all 0.2s ease;
  display: inline-block;
}

.page-wrapper .orderBtn:active {
  transform: scale(0.96);
}

.page-wrapper .orderBtn:before,
.page-wrapper .orderBtn:after {
  position: absolute;
  content: "";
  width: 150%;
  left: 50%;
  height: 100%;
  transform: translateX(-50%);
  z-index: -1;
  background-repeat: no-repeat;
  opacity: 0;
}

.page-wrapper .orderBtn:hover:before {
  top: -70%;
  background-image: radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, transparent 20%, #7d2ae8 20%, transparent 30%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, transparent 10%, #7d2ae8 15%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%);
  background-size: 10% 10%, 20% 20%, 15% 15%, 20% 20%, 18% 18%, 10% 10%, 15% 15%,
    10% 10%, 18% 18%;
  background-position: 50% 120%;
  animation: greentopBubbles 0.6s ease;
  opacity: 1;
}

@keyframes greentopBubbles {
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
  background-image: radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, transparent 10%, #7d2ae8 15%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%),
    radial-gradient(circle, #7d2ae8 20%, transparent 20%);
  background-size: 15% 15%, 20% 20%, 18% 18%, 20% 20%, 15% 15%, 20% 20%, 18% 18%;
  background-position: 50% 0%;
  animation: greenbottomBubbles 0.6s ease;
  opacity: 1;
}

@keyframes greenbottomBubbles {
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


    @media (max-width:1499px)
    {
        .page-wrapper h1 { 
            font-size: 52px;
        }
        .page-wrapper h2 {
            font-size: 50px;
        }
        .page-wrapper h3 {
            font-size: 48px;
        }
        .page-wrapper h4 {
            font-size: 46px;
        }
        .page-wrapper h5 {
            font-size: 34px;
        }
        .page-wrapper .headerImg {
            height: 70vh;
        }
        .page-wrapper .curveImg {
            height: 250px;
        }
        .page-wrapper .badge-wrapper {
            bottom: -25px;
            margin-right: 2%;
        }
        .page-wrapper p {
            font-size: 18px;
        }
        .page-wrapper .menuImgContainer img {
            width: 60px;
            height: 60px;
        }
        .page-wrapper .aboutImg {
            height: 350px;
        }
        .page-wrapper .aboutSection {
    padding: 50px 0 75px;
}
.page-wrapper .elevateSection {
    padding: 75px 100px 50px;
    margin: 0 0px;
}
.page-wrapper .serviceContainer {
    width: 100%;
}
.page-wrapper .storyTxt {
    padding: 20px 0;
    font-size: 35px;
}
.page-wrapper .curveImgTwo {
    bottom: 25px;
}
.page-wrapper .footerSection {
    padding: 80px 0;
    margin-bottom: 60px;
}
.page-wrapper .carouselHover h3 {
    font-size: 30px;
}
.page-wrapper .carouselHover .spoonsImg {
    width: 55px !important;
    height: 55px !important;
}
    }

    @media (max-width:1199px)
    {
        .page-wrapper h1 {
        font-size: 42px;
    }
    .page-wrapper h2 {
        font-size: 40px;
    }
    .page-wrapper h3 {
        font-size: 38px;
    }
    .page-wrapper h4 {
        font-size: 36px;
    }
    .page-wrapper h5 {
        font-size: 32px;
    }
        .page-wrapper .headerImg {
        height: 65vh;
    }
    .page-wrapper .headerPara {
        font-size: 22px;
    }
    .page-wrapper .inner-circle-static {
        width: 70px;
        height: 70px;
    }
    .page-wrapper .badge-wrapper {
        width: 130px;
        height: 130px;
    }
    .page-wrapper .aboutImg {
            height: 310px;
        }
        .page-wrapper p {
        font-size: 16px;
    }
    .page-wrapper h2 {
        margin-bottom: 25px;
    }
    .page-wrapper .menuSection {
    border: 3px dashed #000;
    padding: 35px 20px;
    margin: 10px;
    border-radius: 25px;
}
.page-wrapper .menuContainer {
    margin-bottom: 35px;
}
.page-wrapper .menuImgContainer img {
        width: 60px;
        height: 60px;
    }
    .page-wrapper .menuContainer.two:after {
        border-width: 1px;
    }
    .page-wrapper .elevateSection {
        padding: 65px 75px 25px; 
        border-radius: 25px;
    }
    .page-wrapper .elevateSection::before, .page-wrapper .elevateSection::after {
        border-radius: 25px;
        width: 100%;
    }
    .page-wrapper .iceCreamImg {
    margin: 25px 0 50px;
    border-radius: 15px;
}
.page-wrapper .paymentTxt {
    font-size: 14px; 
    margin-top: 0px;
}
.page-wrapper .storyImg {
    border-radius: 25px;
}
.page-wrapper .storyTxt {
        padding: 15px 0; 
    }
    .page-wrapper .ourStorySection {
    padding: 75px 0;
}
.page-wrapper .menuImgContainer {
    background: #50534c;
    width: 80px;
    height: 80px; 
}
    .page-wrapper .menuImgContainer img {
        width: 50px;
        height: 50px;
    }
    }

    @media (max-width:991px)
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
        font-size: 32px;
    }
    .page-wrapper h5 {
        font-size: 26px;
    }
        .page-wrapper .headerImg {
        height: 55vh;
    }
    .page-wrapper .headerPara {
        font-size: 20px;
    }
    .page-wrapper .curveImg {
        height: 200px;
    }
    .page-wrapper .badge-wrapper {
        width: 105px;
        height: 105px;
    }
    .page-wrapper .inner-circle-static {
        width: 55px;
        height: 55px;
    }
    .page-wrapper .menuImgContainer img {
        width: 50px;
        height: 50px;
    }
    .page-wrapper .menuContainer {
        margin-bottom: 35px;
    }
    .page-wrapper .aboutSection {
        padding: 35px 0 60px;
    }
    .page-wrapper .elevateSection {
        padding: 50px 50px 25px; 
        margin: 0 25px;
    }
    .page-wrapper .elevateSection::before, .page-wrapper .elevateSection::after, .page-wrapper .elevateSection {
        border-radius: 25px; 
    }
    .page-wrapper .curveImgTwo {
        display: none;
    }
    .page-wrapper .storyContent { 
    margin-bottom: 50px;
}
.page-wrapper .footerLeftContent {
    margin-left: unset;
    text-align: center;
    padding-bottom: 50px;
}
.page-wrapper .footerLeftContent h2 {
    transform: scale(1);
    transform-origin: center;
    text-align: center;
}
.page-wrapper .menuImgContainer { 
    width: 60px;
    height: 60px; 
    padding: 12px;
}
    }

    @media (max-width:767px)
    {
        .page-wrapper h1 {
        font-size: 36px;
    }
    .page-wrapper h2 {
        font-size: 34px;
        text-align: center;
        transform-origin: center;
    }
    .page-wrapper h3 {
        font-size: 32px;
    }
    .page-wrapper h4 {
        font-size: 30px;
    }
    .page-wrapper h5 {
        font-size: 28px;
    }
        .page-wrapper .headerSection {
            margin: 30px 10px;
            border-radius: 20px;
        }
        .page-wrapper .headerImg {
        height: 350px;
    }
    .page-wrapper .headerContent { 
    padding: 20px 0;
}
.page-wrapper .headerPara {
        font-size: 16px;
    }
    .page-wrapper .badge-wrapper {
        bottom: -10px;
        margin-right: 5%;
    }
    .page-wrapper p {
        text-align: center;
    }
    .page-wrapper .aboutImg {
        height: 300px;
    }
    .page-wrapper .menuSection {
        margin-top: 50px;
    }
    .page-wrapper .menuTxtContainer p {
        text-align: left;
    }
    .page-wrapper .menuImgContainer img {
        width: 70px;
        height: 70px;
    }
    .page-wrapper .elevateSection {
        padding: 50px 15px 25px;
        margin: 0 10px;
    }
    .page-wrapper .iceCreamImg {
        margin: 20px 0 35px;
        border-radius: 10px;
    }
    .page-wrapper .storyTxt {
        padding: 10px 0;
        font-size: 26px;
    } 
    .page-wrapper .footerSection::before, .page-wrapper .footerSection::after, .page-wrapper .footerSection {
        width: 100%;
        border-radius: 25px;
    }
    .page-wrapper .footerSection {
        padding: 80px 0;
        margin: 0 auto 60px;
        overflow: hidden;
        width: 95%;
    }
    .page-wrapper .owl-carousel .owl-item img, .page-wrapper .owl-item:hover .carouselHover {
        border-radius: 25px;
    }
    .page-wrapper .carouselHover .spoonsImg {
        width: 45px !important;
        height: 45px !important;
    }
    .page-wrapper .carouselHover h3 {
        font-size: 25px;
    }
    }

    @media (max-width:575px)
    {
        .page-wrapper h1 {
        font-size: 35px;
        font-weight: 500;
    }
    .page-wrapper h2 {
        transform: scale(1.0);
        margin-bottom: 15px;
    }
    .page-wrapper h5 {
        font-size: 24px;
    }
    .page-wrapper h1 br{
        display: none;
    }
        .page-wrapper .headerSection { 
            border-radius: 15px;
            max-width: 350px;
    width: 95%;
    margin: 30px auto; 
        }
        .page-wrapper .badge-wrapper {
        bottom: -50px;
    }
        .page-wrapper .curveImg {
            display: none;
        }
        .page-wrapper .headerContent {
        padding: 20px 15px 40px;
        text-align: center;
    }
    .page-wrapper .headerSection {
        overflow: visible;
    }
    .page-wrapper .headerImg {
        height: 100%;
        border-radius: 15px 15px 0 0px;
    }
    .page-wrapper p {
        font-size: 15px;
    }
    .page-wrapper .aboutImg {
        height: 250px;
        max-width: 350px;
        margin: auto;
        display: flex;
    }
    .page-wrapper .menuSection {
        border: 2px dashed #000;
        padding: 25px 15px;
        border-radius: 10px;
        max-width: 350px;
        margin: 0px auto;
        margin-top: 40px;
    }
    .page-wrapper .menuTxtContainer p { 
        margin-bottom: 0;
    }
    .page-wrapper .menuImgContainer img {
        width: 50px;
        height: 50px;
    }
    .page-wrapper .elevateSection::before, .page-wrapper .elevateSection::after, .page-wrapper .elevateSection {
        border-radius: 10px;
    }
    .page-wrapper .textContent {
        flex-direction: column;
        text-align: center;
    }
    .page-wrapper .elevateSection {
        padding: 30px 0px 25px;
        margin: 0 10px;
    }
    .page-wrapper .iceCreamImg {
        margin: 20px 0 20px;
        border-radius: 15px;
        min-height: 200px;
        object-fit: cover;
    }
    .page-wrapper .serviceContainer.two {
        margin-top: 50px;
    }
    .page-wrapper .ourStorySection {
        padding: 50px 0;
    }
    .page-wrapper .storyContent {
        margin-bottom: 25px;
    }
    .page-wrapper .storyImg {
        position: relative;
    width: 100%;
    max-width: 350px;
    margin: auto;
    margin-bottom: 50px;
    }
    .page-wrapper .footerSection {
        padding: 35px 15px;
        margin: 25px auto 40px;
        overflow: hidden;
        max-width: 375px;
        width: 95%;
    }
        .page-wrapper .menuImgContainer {
        width: 50px;
        height: 50px;
        padding: 10px;
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

    <!-- Hero Section -->
        <section class="headerSection">
            <div class="container-fluid px-0">
                <div class="row">
                    
                    <div class="col-lg-7 col-md-6 col-sm-6 position-relative">
                        <img loading="lazy" src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1760091508phpVudq9q.png" class="img-fluid headerImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Waffle">
                    </div>
        
                    <div class="col-lg-5 col-md-6 col-sm-6">
                        <div class="headerContent">
                            <div>
                                <p class="headerPara">Freshly Baked &amp; Full of Flavour</p>
                                <h1>
                                    HANDMADE <br> DESSERTS, <br> CRAFTED WITH LOVE!
                                </h1>
                            </div>
         
                            <div class="badge-wrapper mb-md-4 mb-sm-2">
                                <svg class="badge-svg" viewBox="0 0 200 200">
                                    <defs>
                                        <path id="circlePath" d="M 100, 100 m -75, 0 a 75,75 0 1,1 150,0 a 75,75 0 1,1 -150,0"></path>
                                    </defs>
                                    <text fill="black" class="svgTxt">
                                        <textPath href="#circlePath">
                                            • SATISFY YOUR CRAVINGS • SATISFY YOUR CRAVINGS •
                                        </textPath>
                                    </text>
                                </svg>
                                <div class="inner-circle-static">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769792825phpy3kSZM.png" class="img-fluid spoonImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Waffle">
                                </div>
                            </div> 
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpVJ286w.png" class="img-fluid curveImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Vector">
                        </div>
                    </div>
        
                </div>
            </div>
        </section>
    
        <section class="aboutSection">
            <div class="container">
                <div class="row">
                    <div class="col-lg-6 col-md-6 col-sm-12">
                        <h2>
                            Sweet Treats That <br> Melt In Your Mouth!
                        </h2>
                        <p>
                            Enjoy the finest desserts on the go! At Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 in LEEDS, we make it easy to take home a taste of indulgence. From rich {dessert 1} to refreshing {dessert 2}.
                        </p>
                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769788991phpfclmIk.png" class="img-fluid aboutImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Crepes">
                    </div>
                    <div class="col-lg-6 col-md-6 col-sm-12">
                        <div class="menuSection">
                             <div class="row justify-content-center">
                <div class="col-lg-12 col-md-12 col-sm-12">
                    <div class="menuContainer">
                       
                        <div class="menuTxtContainer">
                            <h5>
                                Order in Seconds
                            </h5>
                            <p class="">
                                Choose your go-to meal from the menu
                            </p>
                        </div>
    
                         <div class="menuImgContainer">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769792619phpZLxZWE.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Search Icon" class="img-fluid">  
                        </div>
                    </div>
                </div>
                <div class="col-lg-12 col-md-12  col-sm-12">
                    <div class="menuContainer two">
                       
                        <div class="menuTxtContainer">
                            <h5>
                                Secure Checkout
                            </h5>
                            <p class="">
                                Paying is effortless, so you can focus on the food.
                            </p>
                        </div>
    
                         <div class="menuImgContainer">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769792619phpDbQH8z.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Payment Icon" class="img-fluid">  
                        </div>
    
                    </div>
                </div>
                <div class="col-lg-12 col-md-12  col-sm-12">
                    <div class="menuContainer three mb-0">
                        
                         <div class="menuTxtContainer">
                             <h5>
                                 Served Fresh
                             </h5>
                             <p class="">
                                 Freshly made and good to go when you are.
                             </p>
                         </div>
                         
                         <div class="menuImgContainer"> 
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769792619phpRTyqkv.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Receive food" class="img-fluid">  
                        </div>
    
                    </div>
                </div>
            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    
        <section class="elevateSection">
            <div class="container-fluid">
                <div class="textContent d-flex justify-content-between align-items-center">
                    <div>
                        <h3>
                            Elevate Your Sweet Tooth
                        </h3>
                    </div>
                    <div> 
                            <a href="/order-now" class="orderBtn btn">Order Now</a> 
                    </div>
                </div>
                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769788814phpN42zUA.jpg" class="img-fluid iceCreamImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Ice Cream">
    
                <div class="row justify-content-center serviceBorder">
                
                <div class="col-lg-4 col-md-6  col-sm-6">
                    <div class="serviceContainer two active">
                        <div class="paymentImgContainer">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769791693phppfRvwM.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Menu Icon" class="img-fluid">  
                        </div>
                            <h5>
                                Our Menu
                            </h5>
                            <p class="paymentTxt">
                                We bring you the best food in , made from the freshest ingredients. Our menu is always evolving with new dishes and customer favourites.
                            </p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6  col-sm-6">
                    <div class="serviceContainer">
                        <div class="paymentImgContainer">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769791693phpZlLdy9.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Hygiene food" class="img-fluid">  
                        </div>
                            <h5>
                                Our Hygiene
                            </h5>
                            <p class="paymentTxt">
                                At Domain545 - Loaded Burgers And Kebabs - 882534  GB June25, we maintain strict food safety standards to ensure your meal is freshly prepared in a clean environment.
                            </p>
                    </div>
                </div>

                <div class="col-lg-4 col-md-6  col-sm-6">
                    <div class="serviceContainer">
                        <div class="paymentImgContainer">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769791693phpv7rOup.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Price Icon" class="img-fluid">  
                        </div>
                            <h5>
                                Our Price
                            </h5>
                            <p class="paymentTxt">
                                Great food doesn’t have to break the bank! At Domain545 - Loaded Burgers And Kebabs - 882534  GB June25, we keep our prices low while maintaining top quality.
                            </p>
                    </div>
                </div>

            </div>
            </div>
        </section>

        <section class="ourStorySection">

            <div class="container">
                <div class="row">
                    <div class="col-lg-3 col-md-6 col-sm-6 order-lg-1 order-md-2 order-sm-2 order-2">
                        <div class="storyImg">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789081phpmCnCr4.jpg" class="img-fluid" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Cake">
                            <p class="storyTxt">
                                Cake
                            </p>
                        </div>
                    </div>

                    <div class="col-lg-6 col-md-12 col-sm-12 order-lg-2 order-md-1 order-sm-1 order-1">
                        <div class="storyContent">
                            <h4>
                                Our Story
                            </h4>
                            <p>
                                Why wait to satisfy your cravings? At Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 in LEEDS, we offer freshly made desserts that you can enjoy on the go. Whether it's a comforting {dessert 1} or a refreshing {dessert 2}, each treat is designed to bring pure bliss to your day.
                            </p>
                        </div>
                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpLAkQJ3.png" class="img-fluid curveImgTwo" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Vector">
                    </div>

                    <div class="col-lg-3 col-md-6 col-sm-6 order-lg-3 order-md-3 order-sm-3 order-3">
                        <div class="storyImg mb-0">
                            <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789082phpFwFYk9.jpg" class="img-fluid" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Brownie">
                            <p class="storyTxt">
                                Brownie
                            </p>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <section class="footerSection">
            <div class="container-fluid px-0">
                <div class="row">
                    <div class="col-lg-4">
                        <div class="footerLeftContent">
                            <div>
                                <h2>
                                    The Sweetest Treats You’ll Ever Taste!
                                </h2>
                            </div>
                            <div> 
                                <a href="/order-now" class="orderBtn btn">Order Now</a> 
                            </div>
                        </div>    
                    </div>
                    <div class="col-lg-8">
                        <div class="carouselCenter">
                            <div class="owl-carousel owl-theme owl-loaded owl-drag">
                                
                                
                                
                                
                                
                            <div class="owl-stage-outer"><div class="owl-stage" style="transform: translate3d(-812px, 0px, 0px); transition: all; width: 2981px;"><div class="owl-item cloned" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789145phpz7o8Na.jpg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Milkshakes">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Milkshakes
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div><div class="owl-item cloned" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1733164941php1y6C8w.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Churros">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Churros
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div><div class="owl-item cloned" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1745513418phpB5opk8.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Sundae">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Sundae
                                            </h3>
                                        </a>
                                    </div>
                                </div></div><div class="owl-item active" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789145phpryPIV8.jpg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Cookie Dough">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Cookie Dough
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div><div class="owl-item active" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789145php1jFTR9.jpg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Ice Cream">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Ice Cream
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div><div class="owl-item active" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789145phpz7o8Na.jpg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Milkshakes">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Milkshakes
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div><div class="owl-item" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1733164941php1y6C8w.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Churros">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Churros
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div><div class="owl-item" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/c5da8c3b32b8cc9fc8d76de87e85ec0a/img/1745513418phpB5opk8.png" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Sundae">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Sundae
                                            </h3>
                                        </a>
                                    </div>
                                </div></div><div class="owl-item cloned" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789145phpryPIV8.jpg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Cookie Dough">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Cookie Dough
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div><div class="owl-item cloned" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789145php1jFTR9.jpg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Ice Cream">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Ice Cream
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div><div class="owl-item cloned" style="width: 245.96px; margin-right: 25px;"><div class="item hovercontent">
                                    <a href="/order-now">
                                        <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769789145phpz7o8Na.jpg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 Milkshakes">
                                    </a>
                                    <div class="carouselHover"><a href="/order-now">
                                            <div>
                                                <img loading="lazy" src="https://assets.touch2success.com/static/b1cb275a788a9c10f60a93682b1e7039/img/1769783739phpzjvsu0.png" class="img-fluid spoonsImg" alt="Domain545 - Loaded Burgers And Kebabs - 882534  GB June25 icon">
                                            </div>
                                        </a>
                                        <a href="/order-now">
                                            <h3>
                                                Milkshakes
                                            </h3>
                                        </a>
                                    </div>
        
                                </div></div></div></div><div class="owl-nav disabled"><button type="button" role="presentation" class="owl-prev"><span aria-label="Previous">‹</span></button><button type="button" role="presentation" class="owl-next"><span aria-label="Next">›</span></button></div><div class="owl-dots disabled"></div></div>
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
 <script src="https://cdnjs.cloudflare.com/ajax/libs/Swiper/11.0.5/swiper-bundle.min.js" type="text/javascript"></script>




 <script>
  $.getScript("https://cdnjs.cloudflare.com/ajax/libs/Swiper/11.0.5/swiper-bundle.min.js", function() {	
      var swiper = new Swiper(".mySwiper", {
          effect: "coverflow",
          grabCursor: true,
          centeredSlides: true,
          slidesPerView: "auto",
          loop:true,
          coverflowEffect: {
            rotate: 0,
            stretch: 0,
            depth: 0,
            modifier: 0,
            slideShadows: false,
          },
          pagination:false,
          breakpoints: {
              0: {
                  slidesPerView: "1",
              },
              600: {
                  slidesPerView: "auto",
                  spaceBetween: 0,
              },
              992: {
                  slidesPerView: "3",
                  spaceBetween: 0,
                  
              },
              1200: {
                  slidesPerView: "5",
                  spaceBetween: 0,
              },
          },
          loop: true,
          autoplay:false,
       autoplayTimeout:3000,
      });
  });
  
</script>

</body>
</html>
