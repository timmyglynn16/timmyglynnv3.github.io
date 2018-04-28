# timmyglynnv3.github.io
Personal Website


<!DOCTYPE html>
<html>
<title>CONTACT</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
    height: 100%;
    color: #777;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url('https://cdn-images-1.medium.com/max/1600/0*QUqE4WGF8_cC9bIl.jpg');
    min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
    background-image: url("/w3images/parallax2.jpg");
    min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
    background-image: url("/w3images/parallax3.jpg");
    min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}
</style>
<body>


<!-- Navbar (sit on top) -->
<div class="w3-top">
        <div class="w3-bar" id="myNavbar">
          <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
            <i class="fa fa-bars"></i>
          </a>
          <a href="https://timmyglynnv3.github.io/" class="w3-bar-item w3-button w3-white">TIMMY GLYNN</a>
          <!-- <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> ABOUT</a> -->
          <a href="https://timmyglynnv3.github.io/software/" class="w3-bar-item w3-button w3-white w3-hide-small"><i class="fa fa-th"></i> SOFTWARE</a>
          <a href="https://timmyglynnv3.github.io/contact/" class="w3-bar-item w3-button w3-white w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>
          <a href="#" class="w3-bar-item w3-button w3-white w3-hide-small w3-right w3-hover-red">
            <i class="fa fa-search"></i>
          </a>
        </div>
      
        <!-- Navbar on small screens -->
        <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
         <!-- <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a> -->
          <a href="https://timmyglynnv3.github.io/software/" class="w3-bar-item w3-button" onclick="toggleFunction()">SOFTWARE</a>
          <a href="https://timmyglynnv3.github.io/contact/" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
          <a href="#" class="w3-bar-item w3-button">SEARCH</a>
        </div>
      </div>



<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="contact">
        <h3 class="w3-center">CONTACT ME</h3>
        <p class="w3-center"><em>I'd love your feedback!</em></p>
      
        <div class="w3-row w3-padding-32 w3-section">
          <div class="w3-col m4 w3-container">
            <!-- Add Google Maps -->
            <div id="googleMap" class="w3-round-large w3-greyscale" style="width:100%;height:400px;"></div>
          </div>
          <div class="w3-col m8 w3-panel">
            <div class="w3-large w3-margin-bottom">
              <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Pittsburgh, PA<br>
              <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Phone: +1 215-694-7564<br>
              <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Email: timmyglynnv3@gmail.com<br>
            </div>
            <p>Swing by for a cup of <i class="fa fa-coffee"></i>, or leave me a note:</p>
            <form action="/action_page.php" target="_blank">
              <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
                <div class="w3-half">
                  <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
                </div>
                <div class="w3-half">
                  <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
                </div>
              </div>
              <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
              <button class="w3-button w3-black w3-right w3-section" type="submit">
                <i class="fa fa-paper-plane"></i> SEND MESSAGE
              </button>
            </form>
          </div>
        </div>
      </div>




                  <body>
              <script>
                function initMap() {
                  var uluru = {lat: 40.4280292, lng: -79.9754504};
                  var map = new google.maps.Map(document.getElementById('map'), {
                    zoom: 10,
                    center: uluru
                  });
                  var marker = new google.maps.Marker({
                    position: uluru,
                    map: map
                  });
                }
              </script>
              <script async defer
              src="https://maps.googleapis.com/maps/api/js?key=AIzaSyC2n761R8ph9q5dDs5Zr-DrQiyZhJ6Xrko&callback=initMap">
              </script>
            </body>
            </div>


  <!---
              <body>
                  <script>
                      function myMap() {
                      var mapProp= {
                          center:new google.maps.LatLng(40.4280292,-79.9754504),
                          zoom:5,
                      };
                      var map=new google.maps.Map(document.getElementById("googleMap"),mapProp);
                      }
                      </script>
                      
                      <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyC2n761R8ph9q5dDs5Zr-DrQiyZhJ6Xrko&callback=myMap"></script>
        
                      </body> -->


          </div>


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