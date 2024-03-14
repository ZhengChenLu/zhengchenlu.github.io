<!doctype html>
<html lang="en-US">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>ZHENG CHEN LU  -  Home</title>
<script src="https://cdn.bootcss.com/jquery/3.4.1/jquery.min.js"></script>
<link href="css/singlePageTemplate.css" rel="stylesheet" type="text/css">
<!--The following script tag downloads a font from the Adobe Edge Web Fonts server for use within the web page. We recommend that you do not modify it.-->
</head>
<body>
<div class="container"> 
  <!-- Navigation -->
  <header> <a href="">
    <h4 class="logo">ADT1809018 ZHENG CHEN LU</h4>
    </a>
    <nav>
      <ul>
        <li><a href=".\index.html" target="_self">HOME</a></li>
        <li><a href=".\about.html" target="_self">ABOUT</a></li>
        <li><a href=".\contact.html" target="_self">CONTACT</a></li>
      </ul>
    </nav>
  </header>
	
	
  <!-- Hero Section -->
  <section class="hero" id="hero">
	  <div id='bannerHtml'>
		  <video autoplay="autoplay" loop="loop" playsinline="true" preload="auto" class="banner1 video" qk-data="video"><source src="./images/video.MP4" type="video/mp4"></video>
	  	<img  src="./images/title.jpg" class="banner1"/>
		  <img  src="./images/all.jpg" class="banner1"/>
	  </div>
	  <div>
	  	<div class="button" onClick="picclick('ab')">A Block</div>
	  	<div class="button" onClick="picclick('bb')">B block</div>
	  	<div class="button" onClick="picclick('cc')">D4</div>
	  	<div class="button" onClick="picclick('dd')">sculpture</div>
	  	<div class="button" onClick="picclick('ee')">bridge</div>
	  	<div class="button" onClick="picclick('ff')">Cafe</div>
	  </div>
  </section>
  <!-- Copyrights Section -->
  <div class="copyright">&copy;2024- <strong>ADT1809018</strong></div>
</div>
	<script language="javascript">
		$(document).ready(function(){
			//alert(1);
			//$(".video").play();
		});
function picclick(val){
	//alert(1);
	var path='',content='';
	switch(val){
		case 'ab':
			path='./images/A.jpg?'+Math.random();
			//alert(path);
			content='1.View of A Block at night<br />Place for classes and studies<br />';
			break;
		case 'bb':
			path='./images/b1.jpg?'+Math.random();
			//alert(path);
			content='2.View of B block<br />The first classrooms and offices';
			break;
		case 'cc':
			path='./images/D.jpg?'+Math.random();
			//alert(path);
			content='3.View of D4 at night<br />Canteen';
			break;
		case 'dd':
			path='./images/S.jpg?'+Math.random();
			//alert(path);
			content='4.View of Mr. Chen at night<br />The founder of the school——"school master"';
			break;
		case 'ee':
			path='./images/b.jpg?'+Math.random();
			//alert(path);
			content='5.View of FuRong Bridge at night';
			break;
		case 'ff':
			path='./images/O.jpg?'+Math.random();
			//alert(path);
			content='6.View of Cafe/Water Honcert hall at night';
			break;
	}
	//alert(path);
	//alert($('#img1'));
	//alert($('#img1')[0].src);
	//$('#bannerHtml').html("<img  src=".\images/imagvaleA3.jpeg" class="banner1" />");
	
	$('#bannerHtml').html('<img src="'+path+'" class="banner2" /><br /><div style="text-align:center;margin-left:50px;font-size:19px">'+content+'</div>');
}
		//alert('opened');
	</script>
</body>
</html>
.banner1{
}@charset "UTF-8";
/* Body */
body {
	font-family: source-sans-pro;
	background-color: #FFFFFF;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	font-style: normal;
	font-weight: 200;
}
.banner1{
	}
/* Container */
.container {
	.banner1{
	}
	width: 90%;
	margin-left: auto;
	margin-right: auto;
	.banner1{
		}
	height: 1000px;
	background-color: #ffffff;
}
/* Navigation */
header {
	width: 100%;
	height: 5%;
	background-color: #FFFFFF;
	border-bottom: 1px solid #F0F1F8;
}
.qrcode{
	width: 1000px
}
.contact{
	float: center;
	width:400px
}
.mylogo{
	width: 1000px
}
.logo {
	color: #000000;
	.banner1{
	}
	font-weight: bold;
	text-align: undefined;
	width: 30%;
	float: left;
	margin-top: 15px;
	margin-left: 25px;
	letter-spacing: 4px;
}
nav {
	float: right;
	width: 50%;
	text-align: right;
	margin-right: 25px;
}
header nav ul {
	list-style: none;
	float: right;
}
nav ul li {
	float: left;
	color: #000000;
	font-size: 14px;
	text-align: left;
	margin-right: 25px;
	letter-spacing: 2px;
	font-weight: bold;
	transition: all 0.3s linear;
}
ul li a {
	color: #000000;
	text-decoration: none;
}
ul li:hover a {
	color: #000000;
}
.hero_header {
	color: #000000;
	text-align: center;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	letter-spacing: 5px;
}
.banner1{
	width: 100%;
	height: auto;
	}
.banner2{
	
	width: 50%;
	height: 50%;
	float: center;
	}
/* Hero Section */
.hero {
	background-color: #FFFFFF;
	padding-top: 10px;
	padding-bottom: 150px;
}
.light {
	font-weight: bold;
	color: #000000;bu
}
.tagline {
	text-align: center;
	color: #000000;
	margin-top: 4px;
	font-weight: lighter;
	text-transform: uppercase;
	letter-spacing: 1px;
}
/* About Section */
.text_column {
	width: 29%;
	text-align: justify;
	font-weight: lighter;
	line-height: 25px;
	float: left;
	padding-left: 20px;
	padding-right: 20px;
	color: #000000;
}
.about {
	padding-left: 25px;
	padding-right: 25px;
	padding-top: 35px;
	display: inline-block;
	background-color: #000000;
	margin-top: 0px;
}
/* Stats Gallery */
.stats {
	color: #717070;
	margin-bottom: 5px;
}
.gallery {
	clear: both;
	display: inline-block;
	width: 100%;
	background-color: #000000;
	/* [disabled]min-width: 400px;
*/
	padding-bottom: 35px;
	padding-top: 0px;
	margin-top: -5px;
	margin-bottom: 0px;
}
.thumbnail {
	width: 25%;
	text-align: center;
	float: left;
	margin-top: 35px;
}
.gallery .thumbnail h4 {
	margin-top: 5px;
	margin-right: 5px;
	margin-bottom: 5px;
	margin-left: 5px;
	color: #F9F4DC;
}
.gallery .thumbnail p {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	color: #F9F4DC;
}
/* Parallax Section */
.banner {
	background-color: #FFFFFF;
	background-image: url(../images/parallax.png);
	height: 400px;
	background-attachment: fixed;
	background-size: cover;
	background-repeat: no-repeat;
}
.parallax {
	color: #000000;
	text-align: right;
	padding-right: 100px;
	padding-top: 110px;
	letter-spacing: 2px;
	margin-top: 0px;
}
.parallax_description {
	color: #000000;
	text-align: right;
	padding-right: 100px;
	width: 30%;
	float: right;
	font-weight: lighter;
	line-height: 23px;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
}
/* More info */
footer {
	background-color: #000000;
	padding-bottom: 35px;
}
.footer_column {
	width: 50%;
	text-align: center;
	padding-top: 30px;
	float: left;
}
footer .footer_column h3 {
	color: #F9F4DC;
	text-align: center;
}
footer .footer_column busp {
	color: #F9F4DC;
	background-color: #000000;
}
.cards {
	width: 100%;
	height: auto;
	max-width: 400px;
	max-height: 200px;
}
footer .footer_column p {
	padding-left: 30px;
	padding-right: 30px;
	text-align: justify;
	line-height: 25px;
	font-weight: lighter;
	margin-left: 20px;
	margin-right: 20px;
}
.button {
    width: 120;
    margin-top: 40px;
    margin-right: auto;
    margin-bottom: auto;
    margin-left: 20px;
    padding-top: 20px;
    padding-right: 18px;
    padding-bottom: 20px;
    padding-left: 18px;
    text-align: center;
    vertical-align: middle;
    border-radius: 0px;
    text-transform: uppercase;
    font-weight: bold;
    letter-spacing: 2px;
    border: 3px solid #000000;
    color: #000000;
    transition: all 0.3s linear;
    float: left;
    width: 12%;
}
.button:hover {
	background-color: #000000;
	color: #FFFFFF;
	cursor: pointer;
}
.copyright {
	text-align: center;
	padding-top: 20px;
	padding-bottom: 20px;
	background-color: #FFFFFF;
	color: #000000;
	text-transform: uppercase;
	font-weight: lighter;
	letter-spacing: 2px;
	border-top-width: 2px;
}
.footer_banner {
	background-color: #F9F4DC;
	padding-top: 60px;
	padding-bottom: 60PX;
	margin-bottom: 0px;
	background-image: url(../images/pattern.png);
	background-repeat: repeat;
}
footer {
	display: inline-block;
}
.hidden {
	display: none;
}

/* Mobile */
@media (max-width: 320px) {
.container header nav {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	float: none;
	display: none;
}
header nav ul {
}
nav ul li {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	text-align: center;
}
.text_column {
	width: 100%;
	text-align: justify;
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
}
.thumbnail {
	width: 100%;
}
.footer_column {
	width: 100%;
	margin-top: 0px;
}
.parallax {
	
	text-align: center;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	padding-top: 40%;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	width: 100%;
	font-size: 18px;
}
.parallax_description {
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	width: 90%;
	margin-top: 25px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 12px;
	float: none;
	text-align: center;
}
.banner {
	background-color: #F0F9F8;
	background-image: none;
}
.tagline {
	margin-top: 20px;
	line-height: 22px;
}
.hero_header {
	padding-left: 10px;
	padding-right: 10px;
	line-height: 22px;
	text-align: center;
}
}

/* Small Tablets */
@media (min-width: 321px)and (max-width: 767px) {
.logo {
	width: 100%;
	text-align: center;
	margin-top: 13px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	color: #043745;
}
.container header nav {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	float: none;
	overflow: auto;
	display: inline-block;
	background: #F0F9F8;
}
header nav ul {
	padding: 0px;
	float: none;
}
nav ul li {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	text-align: center;
	padding-top: 8px;
	padding-bottom: 8px;
}
.text_column {
	width: 100%;
	text-align: left;
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
}
.thumbnail {
	width: 100%;
}
.footer_column {
	width: 100%;
	margin-top: 0px;
}
.parallax {
	text-align: center;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	padding-top: 40%;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	width: 100%;
	font-size: 18px;
}
.parallax_description {
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	margin-top: 30%;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	float: none;
	width: 100%;
	text-align: center;
}
.thumbnail {
	width: 50%;
}
.parallax {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
	padding-top: 20%;
}
.parallax_description {
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	width: 100%;
	padding-top: 30px;
}
.banner {
	padding-left: 20px;
	padding-right: 20px;
}
.footer_column {
	width: 100%;
}
}

/* Small Desktops */
@media (min-width: 768px) and (max-width: 1096px) {
.text_column {
	width: 100%;
}
.thumbnail {
	width: 50%;
}
.text_column {
	width: 100%;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
	padding-top: 0px;
	padding-right: 0px;
	padding-bottom: 0px;
	padding-left: 0px;
}
.banner {
	margin-top: 0px;
	padding-top: 0px;
}
}

