<!DOCTYPE html>
<html>
<head>
<title>NITHIN weds STELLA</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h2{font-family: "Raleway", sans-serif;}
body, html {height: 100%}
p {line-height: 2}
.bgimg, .bgimg2 {
  min-height: 150%;
  background-position: center;
  background-size: cover;
}
.bgimg {background-image: url("LCS04720.jpg")}
.bgimg2 {background-image: url("LCS05338.jpg")}
</style>
</head>
<body>

<!-- Header / Home-->
<header class="w3-display-container w3-wide bgimg w3-grayscale-min" id="home">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo" style="color: #FFC0CB">Stella & Nithin</h1>  
    <h2 style="color: black;">Wedding Reception</h2>
    <h2 style="color: black;"><b>22.06.2024</b></h2>
  </div>
</header>

<!-- Navbar (sticky bottom) -->
<div class="w3-bottom w3-hide-small">
  <div class="w3-bar w3-white w3-center w3-padding w3-opacity-min w3-hover-opacity-off">
    <a href="#home" style="width:25%" class="w3-bar-item w3-button">Home</a>
    <a href="#us" style="width:25%" class="w3-bar-item w3-button">Stella & Nithin</a>
    <a href="#wedding" style="width:25%" class="w3-bar-item w3-button">Wedding</a>
    <a href="#rsvp" style="width:25%" class="w3-bar-item w3-button w3-hover-black">RSVP</a>
  </div>
</div>

<!-- About / Jane And John -->
<div class="w3-container w3-padding-64 w3-pale-red w3-grayscale-min" id="us">
  <div class="w3-content">
    <h1 class="w3-center w3-text-grey"><b>Stella & Nithin</b></h1>
    <p><i>You all know us. And we all know you. <br>
      Celebrate love, laughter, and breathtaking scenery with Stella and Nithin! <br>
      Join us for an outdoor wedding ceremony followed by heartfelt prayers, joyful greetings, and a delicious lunch prepared by a renowned chef. <br>Kids will love exploring the park while you take in the beauty and celebrate with the happy couple.</i>
    </p><br>
    <p class="w3-center"><a href="#wedding" class="w3-button w3-black w3-round w3-padding-large w3-large">Reception Details</a></p>
  </div>
</div>

<!-- Background photo -->
<div class="w3-display-container bgimg2">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo" style="color: whitesmoke;">You Are Invited</h1><br>
    <h2 style="color: whitesmoke;">Of course..</h2>
  </div>
</div>

<!-- Wedding information -->
<div class="w3-container w3-padding-64 w3-pale-red w3-grayscale-min w3-center" id="wedding">
  <div class="w3-content">
    <h1 class="w3-text-grey"><b>THE WEDDING RECEPTION</b></h1>
    <img class="w3-round-large w3-grayscale-min" src="LCS04569.jpg" style="width:80%;margin:64px 0">
    <div class="w3-row">
      <div class="w3-half">
        <h2>When</h2>
        <p>Saturday, 22 June 2024 - 11:30am</p>
        <p>Followed by lunch - 1:00pm</p>
      </div>
      <div class="w3-half">
        <h2>Where</h2>
        <p><a href="https://maps.app.goo.gl/7Esfwe6oEcix7VfFA">The Salvation Army</a></p>
        <p><a href="https://maps.app.goo.gl/7Esfwe6oEcix7VfFA">Orange Grove Road, Coonoor</a></p>
      </div>
    </div>
  </div>
</div>

<!-- RSVP section -->
<div class="w3-container w3-padding-64 w3-pale-red w3-center w3-wide" id="rsvp">
  <h1>HOPE YOU CAN MAKE IT!</h1>
  <p class="w3-large">Kindly Respond By June 21, 2024</p>
  <p class="w3-xlarge">
    <button onclick="document.getElementById('id01').style.display='block'" class="w3-button w3-round w3-red w3-opacity w3-hover-opacity-off" style="padding:8px 60px">RSVP</button>
  </p>
</div>

<div id="id01" class="w3-modal">
  <div class="w3-modal-content w3-card-4 w3-animate-zoom" style="padding:32px;max-width:600px">
    <div class="w3-container w3-white w3-center">
      <h3 class="w3-wide">Tennyson Paul and Family</h1>
      <p>We really hope you can make it.</p>
      <p> PRADIV : +(91) 9944672077</p>
      <p> TENNYSON : +(91) 7010912841</p>
        <p><i>Sincerely,<br> Stella & Nithin</i></p>
        <div class="w3-row">
          <div class="w3-half">
            <button onclick="submitRSVP()" type="button" class="w3-button w3-block w3-green">Going</button>
          </div>
          <div class="w3-half">
            <button onclick="document.getElementById('id01').style.display='none'" type="button" class="w3-button w3-block w3-red">Close</button>
          </div>
        </div>
      </form>
      <p id="confirmationMessage" style="display: none;">Thank you for your RSVP! We look forward to celebrating with you.</p>
    </div>
  </div>
</div>



<!-- Footer -->
<footer class="w3-center w3-black w3-padding-16">
  <p>Developed and Hosted By <a href="https://www.controlshiftcareer.com" title="W3.CSS" target="_blank" class="w3-hover-text-green">ControlShiftCareer</a></p>
  <p>Photography By <a href="www.lenscrewstudio.co.in" title="W3.CSS" target="_blank" class="w3-hover-text-green">Lens Crew Studio</a></p>
</footer>
<div class="w3-hide-small" style="margin-bottom:32px"> </div>

</body>
<script>
function submitRSVP() {
  // Simulate form submission (no actual data sent)
  document.getElementById("confirmationMessage").style.display = "block";
}
</script>

</html>
