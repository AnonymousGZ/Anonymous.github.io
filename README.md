<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="description"content="membuat layout website sederhana menggunakan HTML dan CSS">

	<title>Bambang Prayogo||
	membuat layout website sederhana menggunakan HTML dan CSS</title>
	<style type="text/css">
		body{
			background-color: white;
	margin:0;
	font-family: 'Open Sans', sans-serif;
}
 
hr {
	border:0;
	background:#dedede;
	height:1px;
}		
 
header{
	text-align: center;
	color: black;
}
 
header .judul{
	font-size: 21pt;
}
 
header .deskripsi{
	font-size: 19pt;
}
 
.wrap {
	width: 950px;
	margin:25px auto;
}
 
nav.menu ul {
	overflow:hidden;
	color:#fff;
	list-style: none;
	float:left;
	padding:0;
	width: 650px;
	margin:0 0 0;
	background: #1abc9c;
	-webkit-box-shadow: 1px 1px 1px 0px rgba(204,204,204,0.55);
	-moz-box-shadow: 1px 1px 1px 0px rgba(204,204,204,0.55);
	box-shadow: 1px 1px 1px 0px rgba(204,204,204,0.55);
}
 
nav.menu ul li {
	margin:0;
	float:left;
}
 
nav.menu ul a {
	padding:25px;
	display:block;
	font-weight:600;
	font-size: 16px;
	color:#fff;
	text-transform: uppercase;
	transition: all 0.5s ease;
	text-decoration: none;
}
 
nav.menu ul a:hover {
	text-decoration: underline;
	background:#16a085;
}
 
.sidebar {
	float:right;
	width:275px;
}
 
.sidebar .widget {
	padding:25px;
	margin:0 0 25px;
	background:#fff;
	border-bottom: 2px solid #fff;
	transition: all 0.5s ease;
}
 
.sidebar .widget:hover {
	border-bottom: 2px solid #3498db;
}
 
.sidebar .widget h2 {
	padding:0;
	margin:0 0 15px;
	color:#3498db;
	font-size: 18px;
	font-weight:800;
	text-transform: uppercase;
}
 
.sidebar .widget p {
	font-size: 14px;
}
 
.sidebar .widget p:last-child {
	margin:0;
}
 
.blog {
	float:left;
}
 
.conteudo {
	width:600px;
	padding:25px;
	margin:25px auto;
	background: silver;
	border:1px solid #dedede;
	-webkit-box-shadow: 1px 1px 1px 0px rgba(204,204,204,0.35);
	-moz-box-shadow: 1px 1px 1px 0px rgba(204,204,204,0.35);
	box-shadow: 1px 1px 1px 0px rgba(204,204,204,0.35);
}
 
.conteudo img {
	min-width: 650px;
	margin:0 0 25px -25px;
	max-width: 650px;
}
 
.conteudo h1 {
	padding:0;
	margin:0 0 15px;
	font-weight: normal;
	color: #666;
	font-family: Georgia;
}
 
.conteudo p:last-child {
	margin: 0;
}
 
.conteudo .continue-lendo {
	color:red;
	transition: all 0.5s ease;
	text-decoration: none;
	font-weight: 700; 
}
 
.conteudo .continue-lendo:hover {
	margin-left:10px;
}
 
.post-info {
	float: right;
	font-size: 12px;
	margin: -10px 0 15px;
	text-transform: uppercase;
}
 
@media screen and (max-width: 960px) {
 
	.header {
		position:inherit;
	}
 
	.wrap {
		width: 90%;
		margin:25px auto;
	}
	.sidebar {
		width:100%;
		margin:25px 0 0;
		float:right;
	}
</style>
	<head>
	<title>latihan pemrograman</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	
	<!-- bagian header template -->
	<header>
		<h1 class="judul">Belajar Ngoding</h1>
		<p class="deskripsi">Tutorial pemrograman web, mobile dan desktop lengkap berbahasa indonesia. dari dasar hingga mahir.</p>
	</header>
	<!-- akhir bagian header template -->
	
	<div class="wrap">
		<!-- bagian menu		 -->
		<nav class="menu">
			<ul>
				<li>
					<a href="#">Home</a>
				</li>
				<li>
					<a href="#">Tutorial</a>
				</li>
				<li>
					<a href="#">Kontak</a>
				</li>
			</ul>
		</nav>
		<!-- akhir bagian menu -->
 
		<!-- bagian sidebar website -->
		<aside class="sidebar">
			<div class="widget">
				<h2>Tutorial</h2>
				<p>Selamat datang di www.malasngoding.com, situs ini menyediakan tutorial pemrograman web, mobile & desktop.</p>
			</div>
			<div class="widget">
				<h2>Ebook Gratis</h2>
				<p>Teman-teman bisa mendapatkan ebook tutorial gratis di sini <a target="_blank" href="https://www.malasngoding.com">www.malasngoding.com</a>.</p>
			</div>
		</aside>
		<!-- akhir bagian sidebar website -->
 
		<!-- bagian konten Blog -->
		<div class="blog">
			<div class="conteudo">
				<div class="post-info">
					Di Posting Oleh <b>Aldi Mustofa Pranata</b>
				</div>
				<img src="https://www.malasngoding.com/wp-content/uploads/2016/02/tutorial-css-bahasa-indonesia.png">
				<h1> pengertian html</h1>
				<hr>
				<p>
					HTML adalah singkatan dari Hypertext Markup Language, HTML merupakan salah satu bahasa pengkodean atau pemograman yang digunakan untuk membuat halaman website yang ditampilkan pada web browser.
				</p>				
				<a href="#" class="continue-lendo">Selengkapnya →</a>
			</div>
			<div class="conteudo">
				<div class="post-info">
					Di Posting Oleh <b>Aldi Mustofa Pranata</b>
				</div>
				<img src="https://www.malasngoding.com/wp-content/uploads/2016/02/tutorial-html-bahasa-indonesia.png">
				<h1> pengertian css </h1>
				<hr>
				<p>
					CSS merupakan singkatan dari Cascading Style Sheets, CSS digunakan untuk menentukan gaya dari tampilan website yang akan kamu buat seperti tata letak halaman, warna , dan font. Semuanya dapat ditentukan oleh CSS, CSS bertujuan agar website terlihat lebih menarik.
				</p>				
				<a href="#" class="continue-lendo">Selengkapnya →</a>
			</div>
		</div>
		<!-- akhir bagian konten Blog -->
	</div>
 
</body>
</html>
