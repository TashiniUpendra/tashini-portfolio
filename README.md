<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tashini Upendra | Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#0d1b2a;
color:white;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#08131f;
}

nav h2{
color:white;
}

nav ul{
display:flex;
list-style:none;
gap:30px;
}

nav ul li a{
text-decoration:none;
color:white;
font-size:16px;
transition:0.3s;
}

nav ul li a:hover{
color:#ff6b4a;
}

.hero{
display:flex;
align-items:center;
justify-content:space-between;
padding:80px 10%;
}

.hero-text h1{
font-size:45px;
margin:10px 0;
}

.hero-text span{
color:#ff6b4a;
}

.hero-text p{
margin-bottom:25px;
}

.buttons{
display:flex;
gap:15px;
}

.btn1{
background:#ff6b4a;
padding:12px 25px;
border:none;
color:white;
cursor:pointer;
border-radius:6px;
transition:0.3s;
}

.btn1:hover{
background:#ff3b16;
}

.btn2{
background:transparent;
border:2px solid #ff6b4a;
padding:12px 25px;
color:white;
cursor:pointer;
border-radius:6px;
transition:0.3s;
}

.btn2:hover{
background:#ff6b4a;
}

/* PROFILE IMAGE */

.hero-img{
position:relative;
}

.hero-img img{
width:320px;
height:320px;
object-fit:cover;
border-radius:50%;
border:6px solid #ff6b4a;
box-shadow:0 0 40px rgba(255,107,74,0.5);
animation:float 4s ease-in-out infinite;
}

/* FLOAT ANIMATION */

@keyframes float{

0%{
transform:translateY(0px);
}

50%{
transform:translateY(-15px);
}

100%{
transform:translateY(0px);
}

}

.skills{
display:flex;
justify-content:center;
gap:40px;
padding:30px;
background:#08131f;
flex-wrap:wrap;
}

.skills span{
opacity:0.7;
transition:0.3s;
}

.skills span:hover{
color:#ff6b4a;
opacity:1;
}

section{
padding:80px 10%;
}

.about h2{
font-size:35px;
margin-bottom:20px;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
margin-top:30px;
}

.card{
background:#08131f;
padding:25px;
border-radius:10px;
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 10px 20px rgba(0,0,0,0.4);
}

footer{
text-align:center;
padding:20px;
background:#08131f;
margin-top:40px;
}

</style>
</head>

<body>

<nav>
<h2>Tashini</h2>

<ul>
<li><a href="#">Home</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Projects</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav>


<div class="hero">

<div class="hero-text">

<p>Hello.</p>

<h1>I'm <span>Tashini</span></h1>

<h1>Software Engineering Student</h1>

<p>I love building software, websites and learning new technologies.</p>

<div class="buttons">
<button class="btn1">Got a project?</button>
<button class="btn2">My Resume</button>
</div>

</div>

<div class="hero-img">
<img src="https://media.licdn.com/dms/image/v2/D4E03AQE1Vlr5k2QFZw/profile-displayphoto-scale_400_400/B4EZi1_bmiHoAg-/0/1755399962487?e=1774483200&v=beta&t=xxVNeOr6qGEnd9wpieWyihSlAw6AIsXhcr79PGuJDm4">
</div>

</div>


<div class="skills">

<span>HTML</span>
<span>CSS</span>
<span>Java</span>
<span>MySQL</span>
<span>Git</span>
<span>GitHub</span>

</div>


<section class="about">

<h2>About Me</h2>

<p>
I am a Software Engineering student passionate about building software solutions.
I enjoy learning programming, database systems, and modern web technologies.
My goal is to become a professional software developer and create useful applications.
</p>

</section>


<section>

<h2>Projects</h2>

<div class="projects">

<div class="card">
<h3>Java OOP Quiz Game</h3>
<p>GUI based quiz game built using Java Swing and Object-Oriented Programming concepts.</p>
</div>

<div class="card">
<h3>Hospital Database System</h3>
<p>Database project with ER diagrams, relational schema and SQL queries.</p>
</div>

<div class="card">
<h3>Smart Classroom System</h3>
<p>Automation system using sensors to control electricity usage.</p>
</div>

</div>

</section>


<footer>

<p>© 2026 Tashini Upendra</p>

</footer>

</body>
</html>
