# PORTFOLIO
portfolio/
│── index.html
│── style.css
│── script.js

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Python Programmer</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a developer skilled in Python, web development, and problem-solving.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="card">
            <h3>Snake Game</h3>
            <p>Built using Python with improved graphics.</p>
        </div>
        <div class="card">
            <h3>E-commerce Website</h3>
            <p>Full-featured shopping platform with login & cart.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: your@email.com</p>
    </section>

    <footer>
        <p>© 2026 Your Name</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f4f4f4;
}

header {
    background: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

nav {
    background: #555;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}

section {
    padding: 20px;
}

.card {
    background: white;
    padding: 15px;
    margin: 10px 0;
    border-radius: 8px;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
console.log("Portfolio loaded successfully!");
