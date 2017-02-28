# 555<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1 {font-family: "Montserrat", sans-serif}
img {margin-bottom: -7px}
.w3-row-padding img {margin-bottom: 12px}
</style>
<body>

<!-- Sidenav -->
<nav class="w3-sidenav w3-black w3-animate-top w3-center w3-xxlarge" style="display:none;padding-top:150px" id="mySidenav">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-closenav w3-jumbo w3-display-topright" style="padding:6px 24px">
    <i class="fa fa-remove"></i>
  </a>
  <a href="javascript:void(0)" class="w3-text-grey w3-hover-black">About</a>
  <a href="javascript:void(0)" class="w3-text-grey w3-hover-black">Photos</a>
  <a href="javascript:void(0)" class="w3-text-grey w3-hover-black">Shop</a>
  <a href="javascript:void(0)" class="w3-text-grey w3-hover-black">Contact</a>
</nav>

<!-- !PAGE CONTENT! -->
<div class="w3-content" style="max-width:1500px">

<!-- Header -->
<header class="w3-container w3-padding-32 w3-center w3-opacity w3-margin-bottom">
  <span class="w3-opennav w3-xxlarge w3-right w3-margin-right" onclick="w3_open()"><i class="fa fa-bars"></i></span> 
  <div class="w3-clear"></div>
  <h1><b>PHOTOLIO</b></h1>
  <p><b>Travel Pictures by Thitima.</b></p>
  <p class="w3-padding-16"><button class="w3-button w3-black" onclick="myFunction()">Toggle Grid Padding</button></p>
</header>

<!-- Photo Grid -->
<div class="w3-row" id="myGrid" style="margin-bottom:128px">
  <div class="w3-third">
    <img src="one.jpg" style="width:100%">
    <img src="two.jpg" style="width:100%">
    <img src="13.jpg" style="width:100%">
    <img src="three.jpg" style="width:100%">
    <img src="four.jpg" style="width:100%">
    <img src="five.jpg" style="width:100%">
    <img src="nine.jpg" style="width:100%">
    <img src="eight.jpg" style="width:100%">
  </div>

  <div class="w3-third">
    <img src="six.jpg" style="width:100%">
    <img src="seven.jpg" style="width:100%">
    <img src="ten.jpg" style="width:100%">
    <img src="18.jpg" style="width:100%">
    <img src="19.jpg" style="width:100%">
    <img src="14.jpg" style="width:100%">
   
  </div>

  <div class="w3-third">
    <img src="14.jpg" style="width:100%">
    <img src="20.jpg" style="width:100%">
    <img src="16.jpg" style="width:100%">
    <img src="15.jpg" style="width:100%">
    <img src="17.jpg" style="width:100%">
    <img src="eleven.jpg" style="width:100%">
    <img src="twelve.jpg" style="width:100%">
  </div>
</div>

<!-- End Page Content -->
</div>

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin-top:128px"> 
  <i class="fa fa-facebook-official w3-hover-text-indigo"></i>
   <i class="fa fa-instagram w3-hover-text-purple"></i>
  <i class="fa fa-snapchat w3-hover-text-yellow"></i>
  <i class="fa fa-pinterest-p w3-hover-text-red"></i>
  <i class="fa fa-twitter w3-hover-text-light-blue"></i>
  <i class="fa fa-linkedin w3-hover-text-indigo"></i>
  <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>
 
<script>
// Toggle grid padding
function myFunction() {
    var x = document.getElementById("myGrid");
    if (x.className === "w3-row") {
        x.className = "w3-row-padding";
    } else { 
        x.className = x.className.replace("w3-row-padding", "w3-row");
    }
}

// Open and close sidenav
function w3_open() {
    document.getElementById("mySidenav").style.width = "100%";
    document.getElementById("mySidenav").style.display = "block";
}

function w3_close() {
    document.getElementById("mySidenav").style.display = "none";
}
</script>

</body>
</html>
