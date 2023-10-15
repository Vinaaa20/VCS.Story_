<!DOCTYPE html>
<html>
<head>
<title>VCS. Story</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h2{font-family: "Raleway", sans-serif}
body, html {height: 100%}
p {line-height: 2}
.bgimg, .bgimg2 {
  min-height: 100%;
  background-position: center;
  background-size: cover;
}
.bgimg {background-image: url("https://user-images.githubusercontent.com/147971445/275316284-57452cd7-f003-4c3c-8bc4-f7cbc6e6903f.jpeg")}
.bgimg2 {background-image: url("https://user-images.githubusercontent.com/147971445/275316197-5c39993e-cf26-4632-8b69-07f78f68053f.jpeg")}
</style>
</head>
<body>

<iframe hidden width="560" height="315" 
  src="https://www.youtube.com/embed/3-PFuVHaCYg?autoplay=1" 
  allow="autoplay" 
  title="YouTube video player" 
  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
  allowfullscreen>
</iframe>

<!-- Header / Home-->
<header class="w3-display-container w3-wide bgimg w3-grayscale-min" id="home">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">Java & Vanes </h1>
    <h2>Are getting married</h2>
    <h2><b>24.04.2024</b></h2>
  </div>
</header>

<!-- Navbar (sticky bottom) -->
<div class="w3-bottom w3-hide-small">
  <div class="w3-bar w3-white w3-center w3-padding w3-opacity-min w3-hover-opacity-off">
    <a href="#home" style="width:25%" class="w3-bar-item w3-button">Home</a>
    <a href="#us" style="width:25%" class="w3-bar-item w3-button">Java & Vanes</a>
    <a href="#wedding" style="width:25%" class="w3-bar-item w3-button">Wedding</a>
    <a href="#rsvp" style="width:25%" class="w3-bar-item w3-button w3-hover-black">RSVP</a>
  </div>
</div>

<!-- About / Java & Vanes -->
<div class="w3-container w3-padding-64 w3-pale-red w3-grayscale-min" id="us">
  <div class="w3-content">
    <h1 class="w3-center w3-text-grey"><b>Java & Vanes</b></h1>
    <img class="w3-round w3-grayscale-min" src="https://user-images.githubusercontent.com/147971445/275316535-3cb82540-912a-41f0-a9e9-510cbb847456.jpeg" style="width:100%;margin:32px 0">
    <p><i>Dear Best Partner in live

InsyaAllah you get what you deserve as you deserve the best in this world and in the hereafter. I thank Allah swt for creating you and always making me laugh and putting a smile on my face.

I pray Allah swt gives you 10 more reasons to have a smile on your face and always keep you in my dua. I always pray for only good for you and always be there for you. May Allah swt keep you safe and allow us to reunite when Allah wills in Jannatul Firdaus.
.</i>
    </p><br>
    <p class="w3-center"><a href="#wedding" class="w3-button w3-black w3-round w3-padding-large w3-large">Wedding Details</a></p>
  </div>
</div>

<!-- Background photo -->
<div class="w3-display-container bgimg2">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">You Are Invited</h1><br>
    <h2>Of course</h2>
  </div>
</div>

<!-- Wedding information -->
<div class="w3-container w3-padding-64 w3-pale-red w3-grayscale-min w3-center" id="wedding">
  <div class="w3-content">
    <h1 class="w3-text-grey"><b>THE WEDDING</b></h1>
    <img class="w3-round-large w3-grayscale-min" src="https://user-images.githubusercontent.com/147971445/275316390-b84779c8-0b9f-4f2b-8aca-332404d1901a.jpeg" style="width:100%;margin:64px 0">
    <div class="w3-row">
      <div class="w3-half">
        <h2>Akad Nikah</h2>
        <p>Sabtu 24-04-2024
08.00 s/d selesai
Rumah mempelai wanita Sungai penuh ,, Dusun Arga selebar daun jln R.A Kartini RT 01 Desa koto tinggi (dusun nek)</p></p>
      </div>
      <div class="w3-half">
        <h2>Resepsi</h2>
        <p>Sabtu 24-04-2024
11.00 s/d selesai
Rumah mempelai wanita Sungai penuh ,, Dusun Arga selebar daun jln R.A Kartini RT 01 Desa koto tinggi (dusun nek)</p>
      </div>
    </div>
  </div>
</div>

<!-- RSVP section -->
<div class="w3-container w3-padding-64 w3-pale-red w3-center w3-wide" id="rsvp">
  <h1>HOPE YOU CAN JOIN IN OUR HAPPY DAY!</h1>
  <p class="w3-large">Java & Vanes</p>
  <p class="w3-large">24-04-2024</p>
  <p class="w3-xlarge">
    <button onclick="document.getElementById('id01').style.display='block'" class="w3-button w3-round w3-red w3-opacity w3-hover-opacity-off" style="padding:8px 60px">RSVP</button>
  </p>
</div>

<!-- RSVP modal -->
<div id="id01" class="w3-modal">
  <div class="w3-modal-content w3-card-4 w3-animate-zoom" style="padding:32px;max-width:600px">
    <div class="w3-container w3-white w3-center">
      <h1 class="w3-wide">CAN YOU COME?</h1>
      <p>We really hope you can Join.</p>
      <form>
        <input class="w3-input w3-border" type="text" placeholder="Name(s)" name="name">
      </form>
      <p><i>Sincerely, Java & Vanes</i></p>
      <div class="w3-row">
        <div class="w3-half">
          <button onclick="document.getElementById('id01').style.display='none'" type="button" class="w3-button w3-block w3-green">Going</button>
        </div>
        <div class="w3-half">
          <button onclick="document.getElementById('id01').style.display='none'" type="button" class="w3-button w3-block w3-red">Can't come</button>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-16">
  <p>Powered by <a title="VcS.Story" target="_blank" class="w3-hover-text-green">VcS.Story</a></p>
</footer>
<div class="w3-hide-small" style="margin-bottom:32px"> </div>

</body>
</html>
