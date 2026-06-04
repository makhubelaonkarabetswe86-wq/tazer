<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Artist Website</title>

<style>

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial;
}

body{
  background:#070707;
  color:white;
}

header{
  background:#111;
  padding:20px;
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.logo{
  font-size:28px;
  color:purple;
  font-weight:bold;
}

nav a{
  color:white;
  text-decoration:none;
  margin-left:20px;
}

.hero{
  text-align:center;
  padding:80px 20px;
}

.hero img{
  width:220px;
  height:220px;
  border-radius:50%;
  object-fit:cover;
  border:5px solid purple;
}

.hero h1{
  font-size:55px;
  margin-top:20px;
}

.hero p{
  color:#bbb;
  margin-top:15px;
  line-height:1.7;
}

.btn{
  display:inline-block;
  margin-top:25px;
  padding:15px 30px;
  background:purple;
  color:white;
  text-decoration:none;
  border-radius:10px;
}

.about{
  padding:60px 20px;
  text-align:center;
}

.about h2{
  margin-bottom:20px;
  color:purple;
}

.music{
  padding:60px 20px;
  text-align:center;
}

.music h2{
  color:purple;
  margin-bottom:20px;
}

.song{
  background:#151515;
  padding:20px;
  margin:15px auto;
  max-width:400px;
  border-radius:10px;
}

.socials{
  padding:60px 20px;
  text-align:center;
}

.socials h2{
  color:purple;
  margin-bottom:20px;
}

.socials a{
  display:inline-block;
  margin:10px;
  padding:15px 25px;
  background:#151515;
  color:white;
  text-decoration:none;
  border-radius:10px;
}

footer{
  text-align:center;
  padding:30px;
  background:#111;
  margin-top:40px;
}

</style>
</head>

<body>

<header>

<div class="logo">ARTIST NAME</div>

<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Music</a>
  <a href="#">Socials</a>
</nav>

</header>

<section class="hero">

<img src="artist.jpg" alt="Artist">

<h1>ARTIST NAME</h1>

<p>
Upcoming musician bringing powerful vibes,
good energy and unforgettable music.
</p>

<a href="#" class="btn">Listen Now</a>

</section>

<section class="about">

<h2>About The Artist</h2>

<p>
Write information about the artist here.
Talk about music journey, style, achievements,
and future goals.
</p>

</section>

<section class="music">

<h2>Popular Songs</h2>

<div class="song">
  Song Name 1
</div>

<div class="song">
  Song Name 2
</div>

<div class="song">
  Song Name 3
</div>

</section>

<section class="socials">

<h2>Follow Me</h2>

<a href="https://instagram.com/">Instagram</a>

<a href="https://tiktok.com/">TikTok</a>

<a href="https://youtube.com/">YouTube</a>

<a href="https://facebook.com/">Facebook</a>

</section>

<footer>
© 2026 Artist Website
</footer>

</body>
</html>
