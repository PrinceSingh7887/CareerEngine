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
padding:20px;
text-align:center;
font-size:28px;
position:relative;
z-index:1001;
}

/* MENU BUTTON */
.menu-btn{
position:absolute;
right:20px;
top:20px;
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
padding:12px;
text-align:center;
}

nav a{
color:white;
margin:10px;
text-decoration:none;
font-size:16px;
font-weight:500;
padding:6px 10px;
}

nav a:hover{
background:#2563eb;
border-radius:6px;
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
width:100%;
max-width:600px;
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
}

/* NORMAL BUTTON */
.btn{
background:#2563eb;
color:white;
padding:8px 15px;
border-radius:6px;
text-decoration:none;
display:inline-block;
margin:5px;
}

/* RED APPLY BUTTON */
.apply-btn{
background:red;
color:white;
padding:8px 15px;
border-radius:6px;
text-decoration:none;
display:inline-block;
animation:blink 1s infinite;
margin-top:10px;
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
box-shadow:0 0 10px #ccc;
margin-top:30px;
text-align:center;
}

/* FOOTER */
footer{
background:#0f172a;
color:white;
padding:15px;
text-align:center;
margin-top:30px;
}

/* IMAGE */
img{
width:100px;
margin:8px;
border-radius:10px;
}

/* KALAM IMAGE */
#kalam{
position:fixed;
top:10px;
left:10px;
width:60px;
border-radius:50%;
border:2px solid white;
z-index:1002;
}

/* TELEGRAM POPUP */
#telegramPopup{
display:none;
position:fixed;
bottom:20px;
right:20px;
background:white;
padding:20px;
width:260px;
border-radius:10px;
box-shadow:0 0 15px rgba(0,0,0,0.3);
z-index:999;
}

#telegramPopup a{
background:#0088cc;
color:white;
padding:8px 15px;
border-radius:6px;
text-decoration:none;
display:inline-block;
}

#telegramPopup button{
margin-top:10px;
border:none;
background:red;
color:white;
padding:6px 10px;
border-radius:5px;
cursor:pointer;
}

/* FLOATING TELEGRAM BUTTON */
.telegram-float{
position:fixed;
bottom:20px;
right:20px;
background:#0088cc;
color:white;
padding:12px 18px;
border-radius:30px;
text-decoration:none;
font-weight:bold;
box-shadow:0 4px 10px rgba(0,0,0,0.3);
animation:blink 1.5s infinite;
}
</style>
</head>

<body>

<img id="logo" src="mylogo.png">
<header>
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

<nav>
<a href="#">Home</a>
<a href="#">Latest Jobs</a>
<a href="#">Results</a>
<a href="#">Admit Card</a>
<a href="#civil">Civil</a>
</nav>

<div class="section">
<h2>Latest Jobs</h2>

<div class="card">
<h3>🚆 Railway RRB Group D Recruitment 2026</h3>
<a href="https://www.rrbapply.gov.in/#/auth/home" target="_blank" class="apply-btn">Apply Now</a>
</div>

<div class="card">
<h3>📚 SSC JE Notification 2026</h3>
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

<footer>
<p>📧 princeraj788778@gmail.com</p>
<p>© 2026 Career Engine</p>
</footer>

<!-- TELEGRAM POPUP -->
<div id="telegramPopup">
<h3>Join Telegram 📢</h3>
<p>Latest Job Updates</p>
<a href="https://t.me/careerengine" target="_blank">Join Now</a>
<br><br>
<button onclick="closePopup()">Close</button>
</div>

<!-- FLOATING BUTTON -->
<a href="https://t.me/careerengine" target="_blank" class="telegram-float">
📢 Join Telegram
</a>

<script>
function closePopup(){
document.getElementById("telegramPopup").style.display="none";
}

function toggleMenu(){
let menu = document.getElementById("menu");

if(menu.style.right === "0px"){
menu.style.right = "-260px";
}else{
menu.style.right = "0px";
}
}

setTimeout(function(){
document.getElementById("telegramPopup").style.display="block";
},3000);
</script>

</body>
</html>
