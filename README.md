# timmyglynnv3.github.io
Personal Website


  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
   <!-- <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a> -->
    <a href="https://timmyglynnv3.github.io/software/" class="w3-bar-item w3-button" onclick="toggleFunction()">SOFTWARE</a>
    <a href="https://timmyglynnv3.github.io/contact/" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
    <a href="#" class="w3-bar-item w3-button">SEARCH</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
    * {box-sizing: border-box;}
    body {font-family: Verdana, sans-serif;}
    .mySlides {display: none;}
    img {vertical-align: middle;}
    
    /* Slideshow container */
    .slideshow-container {
      max-width: 100%;
      min-height: 100%;
      background-position: center;
      position: center;
      margin: auto;
      
    }
    
    /* Caption text */
    .text {
      color: #f2f2f2;
      font-size: 15px;
      padding: 8px 12px;
      position: absolute;
      bottom: 8px;
      width: 100%;
      text-align: center;
    }
    
    /* Number text (1/3 etc) */
    .numbertext {
      color: #f2f2f2;
      font-size: 12px;
      padding: 8px 12px;
      position: absolute;
      top: 0;
    }
    
    /* The dots/bullets/indicators */
    .dot {
      height: 15px;
      width: 15px;
      margin: 0 2px;
      background-color: #bbb;
      border-radius: 50%;
      display: inline-block;
      transition: background-color 0.6s ease;
    }
    
    .active {
      background-color: #717171;
    }
    
    /* Fading animation */
    .fade {
      -webkit-animation-name: fade;
      -webkit-animation-duration: 1.5s;
      animation-name: fade;
      animation-duration: 1.5s;
    }
    
    @-webkit-keyframes fade {
      from {opacity: .4} 
      to {opacity: 1}
    }
    
    @keyframes fade {
      from {opacity: .4} 
      to {opacity: 1}
    }
    
    /* On smaller screens, decrease text size */
    @media only screen and (max-width: 300px) {
      .text {font-size: 11px}
    }
    </style>
    </head>

    <body>
    
    <div class="slideshow-container">
    
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="https://cdn10.phillymag.com/wp-content/uploads/sites/3/2016/02/Image-by-R.-Kennedy-for-VISIT-PHILADELPHIA-940x540.jpg" style="w3-display-container">
      <div class="text"></div> 
    </div>
    
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="https://www.100resilientcities.org/wp-content/uploads/2017/06/Pittsburgh-hero-crop.jpg" style="w3-display-container">
      <div class="text"></div> 
    </div>
    
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="https://www.usnews.com/img/college-photo_18781.jpg" style="w3-display-container">
      <div class="text"></div> 
    </div>

    <div class="mySlides fade">
        <div class="numbertext"></div>
        <img src="http://static1.squarespace.com/static/54f60a07e4b08bcee808d8e8/54f63b4be4b0d44c8c944739/54f63bb5e4b0d44c8c946965/1425423285107/portrichmondplayground.jpg?format=original" style="w3-display-container">
        <div class="text"></div> 
      </div>
    
    </div>
    <br>
    
    <div style="text-align:center">
      <span class="dot"></span> 
      <span class="dot"></span> 
      <span class="dot"></span> 
      <span class="dot"></span>
    </div>
    
    <script>
    var slideIndex = 0;
    showSlides();
    
    function showSlides() {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        for (i = 0; i < slides.length; i++) {
           slides[i].style.display = "none";  
        }
        slideIndex++;
        if (slideIndex > slides.length) {slideIndex = 1}    
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex-1].style.display = "block";  
        dots[slideIndex-1].className += " active";
        setTimeout(showSlides, 3000); // Change image every 3 seconds
    }
    
    </script>
    
    </body>