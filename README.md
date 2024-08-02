<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Portfolio</title>
<style>
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
    }
    header {
        background-color: #333;
        color: #fff;
        text-align: center;
        padding: 1rem 0;
    }
    .container {
        max-width: 800px;
        margin: auto;
        padding: 2rem;
        background-color: #fff;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
        border-radius: 8px;
        margin-top: 20px;
    }
    h1, h2 {
        text-align: center;
    }
    .portfolio-item {
        margin-bottom: 1.5rem;
    }
    .portfolio-item img {
        max-width: 100%;
        height: auto;
        border-radius: 8px;
    }
    footer {
        text-align: center;
        padding: 1rem 0;
        background-color: #333;
        color: #fff;
        position: fixed;
        bottom: 0;
        width: 100%;
    }
</style>
</head>
<body>
    <header>
        <h1>Student Portfolio</h1>
    </header>
    <div class="container">
        <section class="portfolio-item">
            <h2>About Me</h2>
            <p>Hello! My name is John Doe. I am a passionate student interested in web development.</p>
        </section>
        <section class="portfolio-item">
            <h2>Projects</h2>
            <div>
                <h3>Project 1: Personal Website</h3>
                <p>A simple personal website showcasing my skills and interests.</p>
                <img src="project1.jpg" alt="Project 1 Screenshot">
            </div>
            <div>
                <h3>Project 2: Portfolio Redesign</h3>
                <p>Redesigned my portfolio website to improve usability and visual appeal.</p>
                <img src="project2.jpg" alt="Project 2 Screenshot">
            </div>
        </section>
        <section class="portfolio-item">
            <h2>Contact</h2>
            <p>Email: john.doe@example.com</p>
            <p>Phone: +1234567890</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Student Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
