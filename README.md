<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Career Engine</title>

<style>
body{
margin:0;
font-family:Arial;
background:#f5f5f5;
}

/* HEADER */
header{
background:#b30000;
color:white;
padding:15px;
text-align:center;
font-size:24px;
font-weight:bold;
}

/* NAVBAR */
nav{
background:#000;
display:flex;
justify-content:center;
flex-wrap:wrap;
}

nav a{
color:white;
padding:10px 15px;
text-decoration:none;
}

nav a:hover{
background:#b30000;
}

/* BOX SECTION */
.container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
padding:20px;
}

.box{
background:white;
padding:15px;
border-radius:8px;
box-shadow:0 2px 5px rgba(0,0,0,0.2);
}

.box h3{
color:#b30000;
margin-top:0;
}

.box a{
display:block;
color:#000;
text-decoration:none;
margin:5px 0;
}

.box a:hover{
text-decoration:underline;
}

/* FOOTER */
footer{
background:#000;
color:white;
text-align:center;
padding:10px;
}
</style>
</head>

<body>

<header>
Career Engine 🚀
</header>

<nav>
<a href="#">Home</a>
<a href="#">Latest Jobs</a>
<a href="#">Results</a>
<a href="#">Admit Card</a>
<a href="#">Answer Key</a>
</nav>

<div class="container">

<div class="box">
<h3>Latest Jobs</h3>
<a href="#">SSC GD Recruitment 2026</a>
<a href="#">Railway Group D</a>
<a href="#">UP Police Vacancy</a>
</div>

<div class="box">
<h3>Results</h3>
<a href="#">SSC CGL Result</a>
<a href="#">UP Board Result</a>
<a href="#">Railway NTPC Result</a>
</div>

<div class="box">
<h3>Admit Card</h3>
<a href="#">SSC CHSL Admit Card</a>
<a href="#">UPSC Admit Card</a>
</div>

<div class="box">
<h3>Answer Key</h3>
<a href="#">SSC Answer Key</a>
<a href="#">Railway Answer Key</a>
</div>

</div>

<footer>
© 2026 Career Engine | Made by Prince ❤️
</footer>

</body>
</html>
