# Cloud-
#a basic front-end blog/website using HTML, CSS5 and bootstrap
<!DOCTYPE HTML>
<html lang="en">
<head>
	<title>Cloud</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<style>
	.bg-1{
		background-image: url("http://www.adobewordpress.com/duvar-kagitlari/wallpaper-37.jpg");
		color: #ffffff;
		height: 100%;
		width: 100%;
		background-size: cover;
		font-family: Avenir;

	}
	h2, h3, h4{
		font-family: avenir;
	}
	.bg-2{
		background-image:url("http://cdn.wanderlust.co.uk/contentimages/wanderlust/photos-cable-car-san-francisco-california.jpg?maxwidth=900");
		color: #ffffff;
		font-family: avenir;
		height: 100%;
		width: 100%;
		background-size: cover;
	}
	.bg-3{
		background-image: url("http://wallpapercave.com/wp/7uw5sUQ.jpg");
		color: #ffffff;
		font-family: avenir;
		background-size: cover;
	}
	.container-fluid {
		padding-top: 70px;
		padding-bottom: 70px;
}
.bg4{
	background-color: #ffffff;
	color: #000000;
	font-family: avenir;
}
body {
    font: 20px "Karma", sans-serif;
    line-height: 1.8;
    color: #f5f6f7;
}
img{
	padding-top: 17px;
	padding-bottom: 17px;
	padding-right: 7px;
	padding-right: 7px;
}

p {font-size: 18px;}
.navbar {
    padding-top: 15px;
    padding-bottom: 15px;
    border: 0;
    border-radius: 0;
    margin-bottom: 0;
    font-size: 12px;
    letter-spacing: 5px;
}

.navbar-nav li a:hover {
    color: #1abc9c !important;
}
.bg5{
	background-color: #2f2f2f;
    color: #ffffff;
}
.bg6{
	background-color: #006080;
	color: #ffffff; 
}
.bg7{
	background-color: #ffffff;
	color: #000000;
	background-size: cover;
	font-family: avenir;
}
footer{
	background-color: #ffffff;
	color: #000000;
	font-family: avenir;
	height: 350px;
}
</style>
</head>
<body>
	<nav class="navbar navbar-default">
		<div class="container">
		<div class="navbar-header">
		<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
			<span class="icon-bar"></span>
			<span class="icon-bar"></span>
			<span class="icon-bar"></span>
			
		</button>
			<a class="navbar-brand" 
			href="#">Me</a>
		</div>
			<div class="collapse navbar-collapse" id="myNavbar">
				<ul class="nav navbar-nav navbar-right">
					<li><a href="#demo7">WHAT</a></li>
					<li><a href="#demo8">WORKS</a></li>
					<li><a href="#demo9">CONTACT</a></li>
				</ul>
			</div>
		</div>
	</nav>
	<div class="container-fluid bg-1 text-center">		
			<h2>Who Are we?</h2>
			<img src="https://t4.ftcdn.net/jpg/00/97/32/15/240_F_97321527_7pd7aPn2nHFdRfYu5jgaWupTYRbRmPdk.jpg" class="img-circle" height="300px" width="300px" alt="image">
			<h3>Lorem Ipsum dolor sit, amet</h3>
	</div>
	<div class="container-fluid bg-2 text-center" id="demo7">
		<h2>What we do?</h2>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
	</div>
	<div class="container-fluid bg-3 text-center">
		<h2>Where to find us?</h2>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
	</div>
	<div class="container-fluid bg4 text-center w3-row-padding w3-padding-16 w3-center" id="demo8">
	<h2> Our Journeys</h2>
	<p>We share some of our expeditions around the world. </p>
	<div class="w3-quarter">
		<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRw-LCTHQBmVOE9YwuN8uIwjucvn_8qHxwT7Z8SCBPt31urce96kw" alt="Venice" style="width: 100%" height="400px">
		<h3>Memories of Venice</h3>
		<p>Lorem ipsum text praesent tincidunt ipsum lipsum</p>
	</div>	
	<div class="w3-quarter">
		<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQsut61Gmhg415rMyNnQXtUnJNII5M3yGf_-w4pxjbFdGcAzAw" alt="Prague" style="width: 100%" height="400px">
		<h3> The beautiful Prague</h3>
		<p>Lorem ipsum dolor sit amet tincidunt ipsum lipsum</p>
	</div>
	<div class="w3-quarter">
		<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1XUiGwIEspsSw89MCzkp9zvjP-_vX-KQaZMqmyh0dTYVfcIg-" alt="New York" style="width: 100%" height="400px">
		<h3>The Big Apple</h3>
		<p>Lorem ipsum dolor sit amet boom boomer toom toomer amy schumer</p>
	</div>
	<div class="w3-quarter">
		<img src="https://s-media-cache-ak0.pinimg.com/736x/3f/fd/52/3ffd52c111cf85802825d3bd74f204b9.jpg" alt="Ireland" style="width: 100%" height="400px">
		<h3>Fields of Ireland</h3>
		<p>Lorem ipsum dolor sit amet linda pinda tinda tun tun </p>
	</div>
	<div class="w3-row-padding w3-padding-16 w3-center">
		<div class="w3-quarter">
			<img src="https://lonelyplanetimages.imgix.net/mastheads/stock-photo-roman-sunset-77415821.jpg?sharp=10&vib=20&w=1200" alt="Rome" style="width: 100%" height="400px">
			<h3>Mesmerising Rome</h3>
			<p>lorem ipsum dolor da. Seth Meyers la la la </p>
		</div>
		<div class="w3-quarter">
			<img src="https://media-cdn.tripadvisor.com/media/photo-s/06/8d/1f/6a/linda-playa.jpg" alt="Ibiza" style="width: 100%" height="400px">
			<h3>Beaches of Ibiza</h3>
			<p>Lorem ipsum dolor sit amet George R. R. Martin ping pong.</p>
		</div>
		<div class="w3-quarter">
			<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSw-NC1-jxdBR10hB9cLq-k6vCpf5R3ftfdfY8HNJLTnAYB78jz" alt="Amsterdam" style="width: 100%" height="400px" width="310px">
			<h3>Amsterdam Lights</h3>
			<p> Lorem Ipsum dolor sitt amet ittu bittu jhim batoota</p>
		</div>
		<div class="w3-quarter">
			<img src="https://cache3.travelfish.org/b/assets/2015/gallery/thumbR/gallery_country_thumbR__1481189025.jpg" alt="Vietnam" style="width: 100%" height="400px" width="310px;">
			<h3> Vietnam Wonders</h3>
			<p>lorem ipsum dolor sit amet tilda linda carter parker peter.</p>
		</div>
	</div>
    </div>
<div class="container-fluid bg7" id="demo9">

	<h2 class="text-center">CONTACT US</h2><br>
		<div class="col-sm-5">
			<p>Contact us and we'll get back to you within 24 hours.</p>
			<p><span class="glyphicon glyphicon-map-marker"></span> Somewhere, Someplace</p>
			<p><span class="glyphicon glyphicon-map-marker"></span> +91 1515151515</p>
			<p><span class="glyphicon glyphicon-envelope"></span> someone@something.com</p>
		</div>
		<div class="col-sm-7">
			<div class="row">
				<div class="col-sm-6 form-group">
					<input  class="form-control" id="name" name="name" placeholder="Name" type="text-center" required>
				</div>
				<div class="col-sm-6 form-group">
					<input type="email" name="email" class="form-control" id="email" placeholder="Email" required>
				</div>	
			</div>
			<textarea class="form-control" id="comments" name="comments" placeholder="comments" rows="5"></textarea><br>
			<div class="row">
				<div class="col-sm-12 form-group">
					<button class="btn btn-default pull-right type="submit">Send</button>
				</div>
			</div>	
		</div>
</div>
<footer class="w3-row-padding w3-padding-32">
  <div class="w3-third">
  <h3>FOOTER</h3>
  	<p>Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p><br><br><br><br>
  	<p>Theme prepared by Navya Karnwal</p>
  </div>
  <div class="w3-third">
  	<h3>BLOG POSTS</h3>
      <ul class="w3-ul w3-hoverable">
        <li class="w3-padding-16">
          <img src="https://s-media-cache-ak0.pinimg.com/236x/8b/6b/13/8b6b13bc02e3766874a6a43e8a5f72e2.jpg" style="width:50px">
          <span class="w3-large">Lorem</span><br>
          <span>Sed mattis nunc</span>
        </li>
        <li class="w3-padding-16">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/Nizza-C%C3%B4te_d%27Azur.jpg/1200px-Nizza-C%C3%B4te_d%27Azur.jpg" style="width:50px">
          <span class="w3-large">Ipsum</span><br>
          <span>Praes tinci sed</span>
        </li> 
      </ul>
  </div>
  <div class="w3-third w3-serif">
      <h3>POPULAR TAGS</h3>
      <p>
        <span class="w3-tag w3-black w3-margin-bottom">Travel</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">New York</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Dinner</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Salmon</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">France</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Drinks</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Ideas</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Flavors</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Cuisine</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Chicken</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Dressing</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Fried</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Fish</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Duck</span>
        </p>
        </div>
</footer>	
</body>
</html>
