<!DOCTYPE html>

<html>

<head>

<title>Career Engine</title>

<style>

body{
margin:0;
font-family:Arial;
text-align:center;
background:url("https://images.unsplash.com/photo-1474487548417-781cb71495f3") center/cover no-repeat fixed;
}

header{
background:rgba(26,115,232,0.9);
color:white;
padding:25px;
font-size:32px;
}

nav{
background:#0d47a1;
padding:12px;
}

nav a:hover{
background:#1565c0;
padding:8px 15px;
border-radius:5px;
}

.section{
padding:40px;
}

.jobs{
background:white;
width:65%;
margin:auto;
padding:25px;
border-radius:10px;
box-shadow:0 0 10px #ccc;
}

.ce-section{
background:white;
width:70%;
margin:auto;
padding:30px;
border-radius:10px;
box-shadow:0 0 10px #bbb;
margin-top:40px;
}

.download-btn{
background:#ff9800;
color:white;
padding:12px 25px;
text-decoration:none;
border-radius:6px;
display:inline-block;
margin:10px;
}

footer{
background:#222;
color:white;
padding:20px;
margin-top:40px;
}

img{
width:140px;
margin:10px;
}

#kalam{
position:fixed;
top:15px;
left:15px;
width:90px;
border-radius:50%;
border:3px solid white;
box-shadow:0 0 12px rgba(0,0,0,0.5);
z-index:999;
}
#telegramPopup{
position:fixed;
bottom:20px;
right:20px;
background:white;
padding:20px;
width:260px;
border-radius:10px;
box-shadow:0 0 15px rgba(0,0,0,0.3);
z-index:9999;
}

#telegramPopup h3{
margin-top:0;
color:#0088cc;
}

#telegramPopup a{
display:inline-block;
background:#0088cc;
color:white;
padding:10px 20px;
border-radius:6px;
text-decoration:none;
margin-top:10px;
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

</style>

</head>

<body>

<img id="kalam" src="https://upload.wikimedia.org/wikipedia/commons/9/99/A._P._J._Abdul_Kalam.jpg">

<header>

Welcome to Career Engine 🚀

<p style="font-size:16px">
Latest Government Job Updates
</p>

</header>

<nav>

<a href="#">Home</a> <a href="#">Latest Jobs</a> <a href="#">Results</a> <a href="#">Admit Card</a> <a href="#civil">Civil Engineering</a>

</nav>

<div class="section">

<h2>Latest Jobs</h2>

<a href="https://ssc.gov.in/" target="_blank" class="download-btn">
SSC Official Website
</a>

<a href="https://www.rrbapply.gov.in/#/auth/home" target="_blank" class="download-btn">
Railway Apply Portal
</a>

<div class="jobs">

<p>🚆 Railway RRB Group D Recruitment 2026</p>
<p>📚 SSC JE Notification 2026</p>
<p>👮 Bihar Police Vacancy 2026</p>

</div>

</div>

<div class="ce-section" id="civil">

<h2>🏗 Civil Engineering Knowledge</h2>

<p>
Download useful Civil Engineering Study Materials and AutoCAD Drawings
</p>

<img src="https://images.unsplash.com/photo-1581092580497-e0d23cbdf1dc">
<img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e">
<img src="https://images.unsplash.com/photo-1504307651254-35680f356dfd">

<h3>AutoCAD Files</h3>

<a href="COMPLETE 3D FILE.dwg" class="download-btn" download>
📐 Download AutoCAD Drawing
</a>

<br>

<a href="Unit-01 ,(CEMENT).pdf" class="download-btn" download>
📘 Download Cement Notes
</a>

</div>

<section style="padding:40px;background:#f1f1f1">

<h2>Sarkari Results</h2>

<ul style="list-style:none;font-size:18px">

<li><a href="#">RRB JE Result</a></li>
<li><a href="#">SSC JE Result</a></li>
<li><a href="#">Railway Group D Result</a></li>
<li><a href="#">SSC GD Result</a></li>

</ul>

</section>

<footer>

<p>Contact Us</p>

<p>📧 princeraj788778@gmail.com</p>

<p>© 2026 Career Engine</p>

</footer>

<div id="telegramPopup">

<h3>Join Our Telegram 📢</h3>

<p>Latest Govt Jobs & Updates</p>

<a href="https://t.me/careerengine" target="_blank">
Join Telegram
</a>

<br><br>

<button onclick="closePopup()">Close</button>

</div>

<script>

function closePopup(){
document.getElementById("telegramPopup").style.display="none";
}

</script>

</body>

</html>
