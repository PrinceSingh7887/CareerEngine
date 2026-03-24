<!DOCTYPE html>
<html>
<head>
<title>Career Engine</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">

<style>
body{
margin:0;
font-family:'Poppins', sans-serif;
background:url("76824.jpg") no-repeat center center fixed;
background-size:cover;
}

/* HEADER */
header{
background:#0f172a;
color:white;
padding:15px;
text-align:center;
font-size:26px;
position:sticky;
top:0;
z-index:1000;
}

/* LOGO */
#logo{
position:absolute;
left:10px;
top:10px;
width:40px;
border-radius:50%;
}

/* MENU BUTTON */
.menu-btn{
position:absolute;
right:20px;
top:15px;
cursor:pointer;
font-size:22px;
}

/* SIDEBAR */
#menu{
position:fixed;
right:-280px;
top:0;
width:280px;
height:100vh;
background:linear-gradient(180deg,#0f172a,#1e293b);
color:white;
padding:25px;
transition:0.4s;
z-index:1000;
box-shadow:-5px 0 20px rgba(0,0,0,0.5);
}

/* NAVBAR */
nav{
background:#1e293b;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:10px;
text-decoration:none;
padding:6px 10px;
}

nav a:hover{
background:#2563eb;
border-radius:6px;
}

/* TOP ICON LINKS */
.top-links{
display:flex;
justify-content:center;
gap:12px;
padding:10px;
flex-wrap:wrap;
background:rgba(0,0,0,0.4);
}

.top-links img{
width:55px;
height:55px;
border-radius:50%;
border:2px solid white;
transition:0.3s;
}

.top-links img:hover{
transform:scale(1.2);
}

/* SECTION */
.section{
padding:30px;
text-align:center;
max-width:900px;
margin:auto;
}

/* CARD */
.card{
background:white;
margin:15px auto;
padding:20px;
border-radius:12px;
box-shadow:0 8px 20px rgba(0,0,0,0.2);
max-width:600px;
}

/* BUTTON */
.btn{
background:#2563eb;
color:white;
padding:8px 15px;
border-radius:6px;
text-decoration:none;
display:inline-block;
margin:5px;
}

/* APPLY BUTTON */
.apply-btn{
background:red;
color:white;
padding:8px 15px;
border-radius:6px;
text-decoration:none;
animation:blink 1s infinite;
}

@keyframes blink{
0%{opacity:1;}
50%{opacity:0.5;}
100%{opacity:1;}
}

/* CIVIL SECTION */
.ce-section{
background:white;
width:90%;
margin:auto;
padding:25px;
border-radius:10px;
margin-top:30px;
}

/* FOOTER */
footer{
background:#0f172a;
color:white;
padding:15px;
text-align:center;
margin-top:30px;
}
</style>
</head>

<body>

<!-- HEADER -->
<header>
<img id="logo" src="mylogo.png">
Career Engine 🚀
<p style="font-size:14px">Latest Government Job Updates</p>
<span class="menu-btn" onclick="toggleMenu()">☰</span>
</header>

<!-- SIDEBAR -->
<div id="menu">
<h3>Menu</h3>
<p><b>About</b><br>Prince Raj<br>Civil Engineering</p>
<p><b>Connect</b><br>📧 princeraj788778@gmail.com</p>
</div>

<!-- TOP ICON LINKS -->
<div class="top-links">

<a href="https://jobstep.in/elementor-1224/" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png">
</a>

<a href="https://dlrs.bihar.gov.in/SurveyStatused.aspx?did=21" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/684/684908.png">
</a>

<a href="https://www.npci.org.in/" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/1041/1041884.png">
</a>

<a href="https://imageresizer.com/" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/1828/1828919.png">
</a>

<a href="https://www.remove.bg/" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/1828/1828970.png">
</a>

<a href="important.html">
<img src="https://cdn-icons-png.flaticon.com/512/1828/1828817.png">
</a>

</div>

<!-- NAVBAR -->
<nav>
<a href="#">Home</a>
<a href="#">Latest Jobs</a>
<a href="important.html">Important Websites</a>
<a href="#civil">Civil</a>
</nav>

<!-- CONTENT -->
<div class="section">
<h2>Latest Jobs</h2>

<div class="card">
<h3>🚆 Railway RRB Group D Recruitment 2026</h3>
<a href="https://www.rrbapply.gov.in/" target="_blank" class="apply-btn">Apply Now</a>
</div>

<div class="card">
<h3>📚 SSC JE Notification</h3>
<a href="https://ssc.gov.in/" target="_blank" class="apply-btn">Apply Now</a>
</div>
  <div class="card">
<h3>🎓 RGPV University Updates</h3>
<a href="https://www.rgpv.ac.in/" target="_blank" class="btn">Official</a>
<a href="https://result.rgpv.ac.in/" target="_blank" class="btn">Result</a>
</div>
  
</div>

<div class="ce-section" id="civil">
<h2>🏗 Civil Engineering Knowledge</h2>
<p>Download study materials & AutoCAD files</p>

<img src="https://images.unsplash.com/photo-1581092580497-e0d23cbdf1dc">
<img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e">
<img src="https://images.unsplash.com/photo-1504307651254-35680f356dfd">

<br><br>

<a href="COMPLETE 3D FILE.dwg" class="btn" download> 📐 AutoCAD Drawing </a>
<a href="Unit-01 ,(CEMENT).pdf" class="btn" download> 📘 Cement Notes </a>
</div>

<section style="padding:30px;text-align:center">
<h2>Results</h2>
<div class="card">RRB JE Result</div>
<div class="card">SSC JE Result</div>
<div class="card">Railway Result</div>
</section>


<!-- FOOTER -->
<footer>
<p>📧 princeraj788778@gmail.com</p>
<p>© 2026 Career Engine</p>
</footer>

<script>
function toggleMenu(){
let menu = document.getElementById("menu");

if(menu.style.right === "0px"){
menu.style.right = "-280px";
}else{
menu.style.right = "0px";
}
}
</script>

</body>
</html>
