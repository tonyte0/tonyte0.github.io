# tonyte0.github.io
<!DOCTYPE html>
<html lang="vi">
<head>
	<title>tonyteo.net</title>
	<meta charset="utf-8">
	<style>
    @import url('https://fonts.googleapis.com/css?family=Josefin+Sans:400,700');
*{
	box-sizing: border-box;
}
body {
	margin: 0;
	padding: 0;
}
section {
	width: 100%;
	height: 100vh;
}
section.sec1 {	
	position: relative;
	overflow: hidden;
	background: url(img11.jpg);
	background-attachment: fixed;
	background-size: cover;
	background-repeat: no-repeat;
}
.menu {
	position: absolute;
	top: 50%;
	left: 45%;
	width:350px;
	height: 100px;
	line-height: 100px;
	transform: translate(-50%,-50%);
	box-sizing: border-box;
	z-index: 1;
}
.menu ul {
	margin: 0;
	padding: 0 50px;
	display: flex;
}
.menu ul li {
	list-style: none;
}
.menu ul li a {
	text-decoration: none;
	padding: 5px 20px;
	display: block;
	font-family: 'Josefin Sans', sans-serif;
	font-size: 25px;
	color: #262626;
	text-shadow: 0 0 5px #ffff4d;
	transition: 1s;
}
.menu ul li a:hover {
	color: #00ff00;
}
/*----------------------MENU----------------------------------*/
.content {
	position: relative;
	margin: 0 auto;
	width: 1000px;
	height: 400px;
	box-sizing: border-box;
	background: #fff;
	font-family: sans-serif;
}
.content .ass {
	position: absolute;
	width: 1000px;
	height: 400px;
	padding: 10px 10px;
	border-bottom: 1px solid #cccccc;
}
.content .ass img {
	float: left;
	margin: 20px;
}
.content .ass .text {
	height: 400px;
	width: 400px;
	padding: 20px;
	float: right;
}
.content .ass .text a h1 {
	margin: 0;
	padding: 10px;
	text-align: center;
}
.content .ass .text p {
	padding: 10px;
	text-align: justify;
	font-size: 20px;
}
.content .ass .text a {
	text-decoration: none;
}
.content .ass .text .admin {
	margin: 0;
	height: 60px;
	line-height: 60px;
	border-bottom: 1px solid #262626;
}
.content .ass .text .admin img {
	margin: 0;
	padding: 0 10px;
	border-radius: 50%;
}
/*------------------------------------------------------------*/
.content2 {
	position: relative;
	margin: 0 auto;
	width: 1000px;
	height: 400px;
	box-sizing: border-box;
	background: #fff;
	font-family: sans-serif;
}
.content2 .ass2 {
	position: absolute;
	width: 1000px;
	height: 400px;
	padding: 10px 10px;
	border-bottom: 1px solid #cccccc;
}
.content2 .ass2 img {
	float: left;
	margin: 20px;
}
.content2 .ass2 .text2 {
	height: 400px;
	width: 400px;
	padding: 20px;
	float: right;
}
.content2 .ass2 .text2 a h1 {
	margin: 0;
	padding: 10px;
	text-align: center;
}
.content2 .ass2 .text2 p {
	padding: 10px;
	text-align: justify;
	font-size: 20px;
	text-decoration: none;
}
.content2 .ass2 .text2  a {
	text-decoration: none;
}
.content2 .ass2 .text2 .admin {
	margin: 0;
	height: 60px;
	line-height: 60px;
	border-bottom: 1px solid #262626;
}
.content2 .ass2 .text2 .admin img {
	margin: 0;
	padding: 0 10px;
	border-radius: 50%;
}
/*------------------------------------------------------------*/
#footer {
	position: absolute;
	width: 100%;
	height: 100px;
	line-height: 100px;
	padding: 0 100px;
	border-top: 1px solid #cccccc;
}
#footer img {
	margin: 10px;
	float: left;
}
#footer p {
	text-align: center;
	line-height: 100px;
	color: #262626;
	font-family: 'Josefin Sans', sans-serif;
	font-size: 20px;
	text-decoration: none;
}
  </style>
</head>
<body>
	<div class="menu">
		<ul>
			<li><a href="#">Home</a></li>
			<li><a href="#">About</a></li>
			<li><a href="#">Shoping</a></li>
			<li><a href="#">Photos</a></li>
		</ul>
	</div>
	<section class="sec1"></section>
	<div class="content">
		<div class="ass">
			<img src="woman-759688_960_720.jpg">
			<div class="text">
				<div class="admin">
					<img src="gai3.png">
					<p>Admin 2018/06/24</p>	
				</div>
				<a href="#"><h1> What is Ass</h1></a>
				<p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters.</p>
			</div>		
		</div>
	</div>
	<div class="content2">
		<div class="ass2">
			<img src="woman-759688_960_720.jpg">
			<div class="text2">
				<div class="admin">
					<img src="gai3.png">
					<p>Admin 2018/06/24</p>	
				</div>
				<a href="#"><h1> What is Ass</h1></a>
				<p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters.</p>
			</div>		
		</div>
	</div>
	<div id="footer">
		<img src="programmer.png">
		<p>Copyringht &copy; 2018 www.tonyteo.com</p>
	</div>
</body>
</html>
