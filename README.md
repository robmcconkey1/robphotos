# photosbyrob
Rob McConkey Photography

<!DOCTYPE HTML>
<html>
<head> 
  <meta charset="UTF-8">
<title>Rob McConkey's photography</title>

<link rel="icon" 
      type="image/png" 
      href="10.jpg">

</head>
</head>
<link href="stylesheet.css" rel="stylesheet">   
<h1><a href="https://fontmeme.com/calligraphy-fonts/"><img src="https://fontmeme.com/permalink/200702/21d053a3edad8431171efe39d6fe218c.png" alt="calligraphy-fonts" border="0"></a></h1>




<main>
<nav id="mainMenu">
<ul>

 <li><a href="rmc1.html" >Home</a></li>
 <li><a href="travels.html" >Travel</a></li>
  <li><a href="cities.html" >Cities</a></li>
  <li><a href="weddings.html" >Weddings</a></li>
  <li><a href="https://www.instagram.com/rob_mcconkey/?hl=en" >Instagram</a></li>
  <li><a href="contactme.html">Contact</a></li>
</ul>
</nav>
</main>


  <br>
  <br>



<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <div class="numbertext">1 / 4</div>
    <img src="6.1.jpg" width="100%" />
    <div class="centered">Rob McConkey Photography</div>
  </div>
 <div class="mySlides fade">
    <div class="numbertext">4 / 4</div>
    <img src="4.1.jpg" width="100%" />
    <div class="centered">Rob McConkey Photography</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">2 / 4</div>
    <img src="3.1.jpg" width="100%">
    <div class="centered">Rob McConkey Photography</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 4</div>
    <img src="98.1.jpg" width="100%">
    <div class="centered">Rob McConkey Photography</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">4 / 4</div>
    <img src="2.1.jpg" width="100%" />
    <div class="centered">Rob McConkey Photography</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center" "width:30%">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
</div>
<script type="text/javascript">
var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";

}

var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}
  slides[slideIndex-1].style.display = "block";
  setTimeout(showSlides, 5000); // Change image every 5 seconds
}
</script>



<body>

  <p> " </p>
<h4>


  Suddenly stripped of its usual hustle and bustle, cars and trucks, and the constant foot traffic of locals and tourists alike, Simon Norfolk unearthed a new side of London with the X1D II. Getting lost in the sharp lines and curves of the buildings that are usually concealed by the city’s hyperactivity, all its glorious architecture shone forth like never before. The only faces Simon met were those of the bronze sculptures of England’s past. The only sounds he heard in the normally busy Piccadilly Circus were the songs of blackbirds.

<br>
</h4>
 <p> " </p>

</body>


<div class="mygrid">  


  <div><img src="10.jpg" alt="me"/> </div> 
  <div><img src="1.jpg"></div>  
  <div><img src="2.jpg"></div>  
  <div><img src="3.jpg"></div>  
  <div><img src="1.1.jpg"></div>  
  <div><img src="2.1.jpg"></div>  
 
</div>

<script language=JavaScript>
//Disable right mouse click Script

var message="Sorry, right click has been disabled";

function clickIE4(){
if (event.button==2){
alert(message);
return false;
 }
}

function clickNS4(e){
if (document.layers||document.getElementById&&!document.all){
if (e.which==2||e.which==3){
alert(message);
return false;
}
}
}

if (document.layers){
document.captureEvents(Event.MOUSEDOWN);
document.onmousedown=clickNS4;
}
else if (document.all&&!document.getElementById){
document.onmousedown=clickIE4;
}

document.oncontextmenu=new Function("alert(message);return false")

</script>
  


</html>
© 2020 GitHub, Inc.
