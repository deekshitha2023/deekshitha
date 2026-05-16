# deekshitha

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Deeksha Portfolio</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#0f172a;
    color:white;
    overflow-x:hidden;
}

header{
    width:100%;
    padding:20px 10%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:fixed;
    top:0;
    background:rgba(15,23,42,0.9);
    backdrop-filter:blur(10px);
    z-index:1000;
}

.logo{
    font-size:28px;
    font-weight:700;
    color:#38bdf8;
}

nav a{
    text-decoration:none;
    color:white;
    margin-left:25px;
    transition:0.3s;
}

nav a:hover{
    color:#38bdf8;
}

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:120px 10%;
    gap:50px;
    flex-wrap:wrap;
}

.hero-text{
    flex:1;
}

.hero-text h1{
    font-size:55px;
    margin-bottom:15px;
}

.hero-text h1 span{
    color:#38bdf8;
}

.hero-text h3{
    font-size:28px;
    margin-bottom:20px;
    color:#cbd5e1;
}

.hero-text p{
    line-height:1.8;
    color:#cbd5e1;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:12px 28px;
    background:#38bdf8;
    color:#0f172a;
    text-decoration:none;
    border-radius:30px;
    font-weight:600;
    transition:0.3s;
}

.btn:hover{
    transform:scale(1.05);
}

.hero-image{
    flex:1;
    text-align:center;
}

.hero-image img{
    width:320px;
    border-radius:20px;
    box-shadow:0 0 30px rgba(56,189,248,0.5);
}

section{
    padding:80px 10%;
}

.section-title{
    font-size:40px;
    margin-bottom:40px;
    text-align:center;
    color:#38bdf8;
}

.about p{
    text-align:center;
    max-width:800px;
    margin:auto;
    line-height:1.8;
    color:#cbd5e1;
}

.skills-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.skill{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
    text-align:center;
    transition:0.3s;
}

.skill:hover{
    transform:translateY(-8px);
    background:#334155;
}

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.project-card{
    background:#1e293b;
    padding:20px;
    border-radius:18px;
    transition:0.3s;
}

.project-card:hover{
    transform:scale(1.03);
}

.project-card img{
    width:100%;
    border-radius:12px;
    margin-bottom:15px;
}

.project-card h3{
    margin-bottom:10px;
}

.contact{
    text-align:center;
}

.contact p{
    margin:10px 0;
    color:#cbd5e1;
}

footer{
    text-align:center;
    padding:20px;
    background:#020617;
    color:#94a3b8;
}

@media(max-width:768px){

.hero-text h1{
    font-size:40px;
}

.hero-text h3{
    font-size:22px;
}

.hero{
    text-align:center;
}

nav{
    display:none;
}

}
</style>
</head>

<body>

<header>
    <div class="logo">Deeksha.</div>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">

    <div class="hero-text">
        <h1>Hi, I'm <span>Deeksha</span></h1>
        <h3>Full Stack Developer</h3>

        <p>
            Passionate web developer creating modern,
            responsive and user-friendly websites.
            Skilled in HTML, CSS, JavaScript and Java.
        </p>

        <a href="#" class="btn">Download Resume</a>
    </div>

    <div class="hero-image">
        <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?q=80&w=687&auto=format&fit=crop" alt="">
    </div>
</section>

<section class="about" id="about">

    <h2 class="section-title">About Me</h2>
    <p>
        I am a creative and enthusiastic developer who loves
        building beautiful websites and applications.
        I enjoy learning new technologies and improving my
        programming skills every day.
    </p>

</section>

<section id="skills">

    <h2 class="section-title">Skills</h2>

    <div class="skills-container">

        <div class="skill">
            <h3>HTML</h3>
            <p>Responsive webpage design</p>
        </div>

        <div class="skill">
            <h3>CSS</h3>
            <p>Modern UI styling and animations</p>
        </div>

        <div class="skill">
            <h3>JavaScript</h3>
            <p>Interactive website features</p>
        </div>

        <div class="skill">
            <h3>Java</h3>
            <p>Object-oriented programming</p>
        </div>

    </div>

</section>

<section id="projects">

    <h2 class="section-title">Projects</h2>

    <div class="projects">

        <div class="project-card">
            <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?q=80&w=1170&auto=format&fit=crop">

            <h3>Food Ordering Website</h3>

            <p>
                Responsive food delivery webpage using HTML,
                CSS and JavaScript.
            </p>
        </div>

        <div class="project-card">
            <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?q=80&w=1170&auto=format&fit=crop">

            <h3>Student Management System</h3>

            <p>
                Java-based student record management mini project.
            </p>
        </div>

        <div class="project-card">
            <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1171&auto=format&fit=crop">

            <h3>Portfolio Website</h3>

            <p>
                Personal responsive portfolio with animations.
            </p>
        </div>

    </div>

</section>

<section class="contact" id="contact">

    <h2 class="section-title">Contact</h2>

    <p>Email: deeksha@example.com</p>
    <p>Phone: +91 6362334567</p>
    <p>Location: Karnataka, India</p>

</section>

<footer>
    © 2026 Deeksha Portfolio | All Rights Reserved
</footer>

</body>
</html>