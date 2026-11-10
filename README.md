# AREZOU
Personal graphic design portfolio website showcasing creative projects, visual identity and branding.

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio | Graphic Designer</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: #f5f0e7;
    color: #302b26;
    font-family: 'DM Sans', sans-serif;
}

nav {
    display: flex;
    justify-content: space-between;
    padding: 28px 8%;
    border-bottom: 1px solid #ded5c8;
}

.logo {
    font-family: 'Playfair Display', serif;
    font-size: 23px;
}

nav a {
    color: #302b26;
    text-decoration: none;
    margin-left: 25px;
    font-size: 13px;
}

.hero {
    padding: 120px 10%;
    text-align: center;
}

.hero p {
    letter-spacing: 4px;
    font-size: 11px;
    color: #917b66;
}

h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(42px, 7vw, 85px);
    font-weight: 400;
    margin: 25px 0;
}

.hero h2 {
    font-weight: 300;
    font-size: 16px;
    color: #75675a;
}

section {
    padding: 65px 10%;
}

.section-title {
    font-family: 'Playfair Display', serif;
    font-size: 38px;
    font-weight: 400;
    margin-bottom: 35px;
}

.projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 25px;
}

.project {
    background: #e8dfd2;
    min-height: 250px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Playfair Display', serif;
    font-size: 24px;
    transition: 0.3s;
}

.project:hover {
    transform: translateY(-6px);
}

.project-info {
    margin-top: 13px;
    font-size: 13px;
}

.about {
    max-width: 650px;
    line-height: 2;
    color: #75675a;
}

.contact {
    text-align: center;
    background: #e8dfd2;
}

.contact a {
    color: #302b26;
}

footer {
    padding: 25px;
    text-align: center;
    font-size: 12px;
    color: #75675a;
}
</style>
</head>

<body>

<nav>
    <div class="logo">Portfolio.</div>
    <div>
        <a href="#about">About</a>
        <a href="#work">Work</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<header class="hero">
    <p>GRAPHIC DESIGNER & CREATIVE ARTIST</p>
    <h1>Design with<br>Purpose & Beauty.</h1>
    <h2>Creating timeless visuals through creativity.</h2>
</header>

<section id="about">
    <h2 class="section-title">About Me</h2>
    <p class="about">
        Hello! I am a graphic designer passionate about
        aesthetics, visual storytelling and creative ideas.
        I believe that simplicity is the ultimate form of elegance.
    </p>
</section>

<section id="work">
    <h2 class="section-title">Selected Works</h2>

    <div class="projects">
        <div>
            <div class="project">01</div>
            <p class="project-info">Brand Identity</p>
        </div>

        <div>
            <div class="project">02</div>
            <p class="project-info">Logo Design</p>
        </div>

        <div>
            <div class="project">03</div>
            <p class="project-info">Editorial Design</p>
        </div>

        <div>
            <div class="project">04</div>
            <p class="project-info">Social Media Design</p>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2 class="section-title">Let's Connect</h2>
    <p>Have a project in mind? Let's create something beautiful.</p>
    <br>
    <a href="mailto:your-email@example.com">
        your-email@example.com
    </a>
</section>

<footer>
    © 2026 My Portfolio | Designed with love.
</footer>

</body>
</html>
