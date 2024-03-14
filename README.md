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
