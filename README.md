<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>John Doe Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>John Doe Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#contact">Contact Me</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to My Portfolio!</h2>
        <p>I’m a software developer with a passion for creating impactful digital solutions. Check out my projects and get in touch!</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I’m John Doe, a software engineer with 3+ years of experience in web and mobile application development...</p>
        <h3>Key Skills:</h3>
        <ul>
            <li>Languages: JavaScript, Python, HTML, CSS</li>
            <li>Frameworks: React, Node.js, Django</li>
            <li>Tools: Git, Docker, AWS, Figma</li>
            <li>Soft Skills: Teamwork, Problem Solving, Agile Methodology</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>

        <div class="project">
            <h3>E-Commerce Web Application</h3>
            <p>Developed a full-stack e-commerce website that allows users to browse, purchase, and review products...</p>
        </div>

        <div class="project">
            <h3>Task Management Mobile App</h3>
            <p>A mobile task management app for teams to assign tasks, set deadlines, and track project progress...</p>
        </div>

        <div class="project">
            <h3>Portfolio Website</h3>
            <p>Designed and developed a personal portfolio website to showcase my projects...</p>
        </div>
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <h3>Software Engineer at ABC Technologies</h3>
        <p>Led the development of a large-scale SaaS platform for healthcare providers...</p>
    </section>

    <section id="contact">


    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px 0;
}

#home {
    background-color: #ddd;
    padding: 50px;
    text-align: center;
}

.project {
    background-color: #fff;
    padding: 15px;
    margin: 15px 0;
    border: 1px solid #ccc;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
        <h2>Contact Me</h2>
        <p>Email: john.doe@example.com</p>
        <p>LinkedIn: <a href="#">linkedin.com/in/johndoe</a></p>
        <p>GitHub: <a href="#">github.com/johndoe</a></p>
    </section>

    <footer>
        <p>© 2024 John Doe</p>
    </footer>
</body>
</html>
