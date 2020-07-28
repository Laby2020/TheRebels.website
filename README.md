<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="/w3css/3/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css">
<body>

<!-- Navigation -->
<nav class="w3-bar w3-purple">
  <a href="#home" class="w3-button w3-bar-item">Home</a>
  <a href="#band" class="w3-button w3-bar-item">Band</a>
  <a href="#tour" class="w3-button w3-bar-item">Tour</a>
  <a href="#contact" class="w3-button w3-bar-item">Contact</a>
</nav>

<!-- Slide Show -->
<section>
  <img class="mySlides" src="img_band_la.jpg"
  style="width:100%">
  <img class="mySlides" src="img_band_ny.jpg"
  style="width:100%">
  <img class="mySlides" src="img_band_chicago.jpg"
  style="width:100%">
</section>

<!-- Band Description -->
<section class="w3-container w3-center w3-content" style="max-width:600px">
  <h2 class="w3-wide">THE BAND</h2>
  <p class="w3-opacity"><i>We love music</i></p>
  <p class="w3-justify">We have created a band website. Not just any band but a band that sings and preforms for charities and wildlife centers, majority of the bands earnings go towards these organizations to help provide for the people and animals in need.</p>
</section>

<!-- Band Members -->
<section class="w3-row-padding w3-center w3-light-grey">
  <article class="w3-third">
    <p>Jesse</p>
    <img src="img_bandmember.jpg" alt="Jesse" style="width:100%">
    <p>A natural born leader, the head singer of the band.</p>
  </article>
  <article class="w3-third">
    <p>Terence</p>
    <img src="img_bandmember.jpg" alt="Terence" style="width:100%">
    <p>The party animal, we're pretty sure he's more animal than man.</p>
  </article>
  <article class="w3-third">
    <p>Will</p>
    <img src="img_bandmember.jpg" alt="Will" style="width:100%">
    <p>Will is the funniest and the shortest member of the group, he stands around to be at least 5ft.</p>
  </article>
</section>

<caption>Order Your Tickets Here!<p>

<form action="http://www.learningwebdesign.com/contest.php" method="post">

<li>Name: <input type="text" name="username"></li>
<li>Email:<input type="text" name="email"></li>
<li>Phone Number:<input type="text" name="phone number"><li>
<li>Address:<input type="text" name="address"><li>

<li>What do you hope to listen to?<br>
<textarea name="story" rows="4" cols="60" maxlength="300" placeholder="No more than 300 characters long"></textarea></li>


<p>How many tickets?</p>
<select number="none">
   <option>1</option>
   <option>2</option>
   <option>3</option>
   <option>4</option>
   <option value="5-6">5-6</option>
   <option>7-8</option>
   <option>9-10</option>
 </select>
 </p>

</form>

<p><input type="submit" value="Enjoy the concert!">
<input type="reset"></p>
</form>


<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-black w3-xlarge">
  <a href="#"><i class="fa fa-facebook-official"></i></a>
  <a href="#"><i class="fa fa-pinterest-p"></i></a>
  <a href="#"><i class="fa fa-twitter"></i></a>
  <a href="#"><i class="fa fa-flickr"></i></a>
  <a href="#"><i class="fa fa-linkedin"></i></a>
  <p class="w3-medium">
  </p>
</footer>

<script>
// Automatic Slideshow - change image every 3 seconds
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}
  x[myIndex-1].style.display = "block";
  setTimeout(carousel, 3000);
}

 
