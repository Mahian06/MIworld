# MIworld
<!DOCTYPE HTML>
<html lang="en-US">
<head>
	<meta charset="UTF-8">
	<title>PSD TO HTML</title>
  <style>
    *{
	margin:0;
	padding:0;
}
body{
	font-family:Arial,sans-sarif !important;
	-webkit-transition: all 0.5s ease;
	transition: all 0.5s ease;
}
 h1, h2, h3, h4, h5, h6,a{
	text-decoration: none;
	font-weight: normal;
	margin-top: 10px;
}
p{
	line-height: 100px;
	margin-bottom: 2em;
}
.fix{
	overflow: hidden;
}
.container_ful{
	width: 100%;
}
.container{
	width: 980px;
	margin: 0 auto;
	display: block;
}
.header_bg{
	background-color: #292929;
}
#header .logo_left{
	float:left;
}
#header .logo_left h1{
	margin-top: 50px;
	font-family:leto;
	font-weight: bold;
	font-size: 40px;
	color: #a0a0a0;
}
#header nav{
	float: right;
}
#header nav ul{
	list-style: none;
}
#header nav ul li{
	float: left;
	border-left: 1px solid #000;
}
#header nav ul li:last-child{
	border-right: 1px solid #000;
}
#header nav ul li a{
	display: block;
	color: #fff;
	font-family:leto;
	font-weight: bold;
	font-size: 16px;
	padding: 50px 30px;
	border-bottom: 5px solid #000;
}
#header nav ul li a:hover{
	color: #36552e;
	border-bottom: 5px solid #36552e;
	transition:.5s;
}
#header nav ul li.active a{
	color: #36552e;
	border-bottom: 5px solid #36552e;
}
.container_wrapper {
    overflow: hidden;
    padding-top: 75px;
}
.left_contant{
	float:left;
	width: 75%;
	max-width: 620px;
	margin-right: 60px;
	margin-bottom: 80px;
	text-align: justify;
}
.fast_airticle{
	margin-bottom:50px;
}
.left_contant .single_post_wrapper h2{
	margin: 10px 10px 55px 25px;
	font-size:28px;
	font-weight: bold;
	color: #acacac;
}
.left_contant .single_post_wrapper p{
	font-size:16px;
	line-height:1.2em;
	color: #d9d9d9;
	margin: 0 10px 45px 25px;
}
.left_contant .single_post_wrapper .continue_button{
	border: 1px solid #eeeeee;
	border-radius: 20px;
	color: #eeeeee;
	padding:10px;
	font-size: 16px;
	font-weight: bold;
	margin-left: 25px;
}
.left_contant .single_post_wrapper a:hover{
	color:#fff;
	background: #509b3c;
	transition: .5s;
}
.side_bar{
	margin: 0 0 650px 25px;
	text-align: justify;
	float: right;
	max-width: 280px;
	width: 25%;
}
.single_aside_bar h2{
	background: #f8f8f8;
	border-left: 2px solid #55c237;
	color: #8b8b8b;
	font-size:16pt;
	font-weight: bold;
	padding: 15px;
	margin-bottom: 25px;
}
.single_aside_bar p{
	line-height:1.2em;
	font-size: 16px;
	color: #dedede;
	margin: 0 20px 70px 20px;
	text-align: justify;
}
.single_aside_bar .scerch_box{
	width: 91%;
	padding: 10px;
	color: #f4f4f4;
	border: 1px solid #dedede;
	margin-bottom: 80px;
}
.email_submit{
	position:relative;
}
.email_submit input{
	width:243px;
	height:50px;	
	border:1px solid #E1E0E0;
	background:#f0f0f0;	
}
.email_submit input[type="submit"]{
    float: right;
    background: url(img/search_icon.png) no-repeat;
    width: 24px;
    height: 24px;
    position: absolute;
    text-indent: -999999px;
    border: none;
    top: 15px;
    right: 20px;
	cursor:pointer;
	border:1px solid #000;
	border-radius: 50%;
}
.container_button{
	border-top: 1px solid #E1E0E0;
    border-left: 1px solid #E1E0E0;
    border-right: 1px solid #E1E0E0;
    padding: 25px 0;
    overflow: hidden;
    text-transform: uppercase;
	font-weight: bold;
}
.container_button .previous{
	float: left;
	margin-left: 20px;
	font-size: 16px;
	color: #E1E0E0;
}
.container_button .next{
	float: right;
	margin-right: 20px;
	font-size: 16px;
	color: #E1E0E0;
}
.container_button .previous:hover{
	color: #55c237;
	transition: .5s;
}
.container_button .next:hover{
	color: #55c237;
	transition: .5s;
}
.footer{
	background: #f8f8f8;
	border-top: 1px solid #E1E0E0;
	text-align: center;
}
.footer footer{
	margin-top: 70px;
}
.footer footer h1{
	margin-bottom: 5px;
}
footer .social_area ul li{
	display: inline-block;
}
footer .social_area ul li.facebook a{
	display: block;
	width: 40px;
	height: 40px;
	background: url( img/fb.png) no-repeat;
	border:10x solid rad;
}
  </style>
</head>
<body>
	<div class="container_ful header_bg">
		<div class="fix container">
			<header id="header">
				<div class="logo_left">
					<h1>Blogin</h1>
				</div>
				<nav>
					<ul>
						<li class="active"><a href="">Jurnal</a></li>
						<li><a href="">About</a></li>
						<li><a href="">Work</a></li>
						<li><a href="">Contact</a></li>
					</ul>
				</nav>
			</header>
		</div>
	</div>
	<div class="container_ful">
		<div class="fix container">
			<div class="container_wrapper">
				<section class="left_contant">
					<article class="single_post_wrapper fast_airticle">
						<img src="img/1st img.png" alt="" />
						<h2>Duis aute irure dolor in henderit in voluptate .</h2>
						<p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquipop ex ea commo doconsequat, sunt in culpa qui officia deserunt mollit anim id est laborum.<br><br>					
						Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur...</p>
						<a class="continue_button" href="">Continue Reading...</a>
					</article>
					<article class="single_post_wrapper">
						<img src="img/2nd img.png" alt="" />
						<h2>Duis aute irure dolor in henderit in voluptate</h2>
						<p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquipop ex ea commo doconsequat, sunt in culpa qui officia deserunt mollit anim id est laborum.<br><br>						
						Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur...</p>
						<a class="continue_button" href="">Continue Reading...</a>
					</article>
				</section>
				<div class="side_bar">
					<aside class="single_aside_bar">
						<h2>About Blogin.</h2>
						<p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
						<br><br>
						Excepteur sint occaecat sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
					</aside>
					<aside class="single_aside_bar">
						<h2>Scerch</h2>
						<input type="text" placeholder="What are you looking for?" class="scerch_box"/>
					</aside>
					<aside class="single_aside_bar">
						<h2>Stay Tuned.</h2>
						<div class="email_submit">
							<input type="email" placeholder="your email" class="email_box" />
							<input type="submit" id="scerchsubmit" />
						</div>
					</aside>
				</div>
			</div>
			<div class="container_button">
				<a href="" class="previous">&#8592;Previous</a>
				<a href="" class="next">Next&#8594;</a>
			</div>
		</div>
	</div>
	<div class="container_ful footer">
		<div class="fix container">
			<footer>
				<h1>Blogin</h1>
				<p>© 2014 Blogin.com  -  All Rights Reserved  -  Find more free Templates at Pixelhint.com</p>
				<div class="social_area">
					<ul>
						<li class="facebook"><a href=""></a></li>
						<li class="twt"><a href=""></a></li>
						<li class="behanse"><a href=""></a></li>
						<li class="g+"><a href=""></a></li>
					</ul>
				</div>
			</footer>
		</div>
	
	
</body>
</html>
