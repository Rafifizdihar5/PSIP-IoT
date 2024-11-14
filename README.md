<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PSIP-IoT - Modul, Quiz Games, Jelajah Budaya</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navbar -->
    <header>
        <nav>
            <div class="logo">
                <h1>PSIP-IoT</h1>
            </div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#modul">Modul</a></li>
                <li><a href="#quiz-games">Quiz Games</a></li>
                <li><a href="#jelajah-budaya">Jelajah Budaya</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Learning Made Fun and Interactive</h2>
            <p>Explore educational modules, challenge your mind with quiz games, and discover new cultures!</p>
            <a href="#modul" class="btn">Get Started</a>
        </div>
    </section>

    <!-- Modul Section -->
    <section id="modul" class="feature-section">
        <h2>Modul Pembelajaran</h2>
        <div class="feature-container">
            <div class="feature-card">
                <h3>Interactive Learning Modules</h3>
                <p>Access a variety of educational modules designed to enhance your knowledge in different subjects.</p>
            </div>
            <div class="feature-card">
                <h3>Self-Paced Learning</h3>
                <p>Learn at your own pace with detailed explanations and step-by-step guides in each module.</p>
            </div>
        </div>
    </section>

    <!-- Quiz Games Section -->
    <section id="quiz-games" class="feature-section">
        <h2>Quiz Games</h2>
        <div class="feature-container">
            <div class="feature-card">
                <h3>Challenge Your Knowledge</h3>
                <p>Test your skills and knowledge through fun and interactive quizzes on various topics.</p>
            </div>
            <div class="feature-card">
                <h3>Compete with Friends</h3>
                <p>Invite friends and compete in real-time quiz games to see who comes out on top!</p>
            </div>
        </div>
    </section>

    <!-- Jelajah Budaya Section -->
    <section id="jelajah-budaya" class="feature-section">
        <h2>Jelajah Budaya</h2>
        <div class="feature-container">
            <div class="feature-card">
                <h3>Explore Global Cultures</h3>
                <p>Embark on a journey to explore the diverse cultures around the world with interactive content and videos.</p>
            </div>
            <div class="feature-card">
                <h3>Virtual Cultural Tours</h3>
                <p>Take virtual tours to different countries and learn about their traditions, art, and history.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <h3>EduHub</h3>
            <p>Stay connected for more exciting learning experiences.</p>
            <div class="socials">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">Instagram</a>
            </div>
        </div>
    </footer>
</body>
</html>
<style>
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    line-height: 1.6;
}

/* Navbar */
header {
    background: #333;
    padding: 10px 0;
    color: #fff;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

.nav-links {
    list-style: none;
}

.nav-links li {
    display: inline;
    margin-right: 15px;
}

.nav-links a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background: url('hero-bg.jpg') no-repeat center center/cover;
    height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
}

.hero h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero p {
    font-size: 20px;
    margin-bottom: 20px;
}

.btn {
    padding: 10px 20px;
    background-color: #ff6f61;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #ff3d3d;
}

/* Feature Sections */
.feature-section {
    padding: 40px 20px;
    text-align: center;
    background-color: #fff;
}

.feature-section:nth-of-type(even) {
    background-color: #f1f1f1;
}

.feature-section h2 {
    font-size: 36px;
    margin-bottom: 30px;
}

.feature-container {
    display: flex;
    justify-content: space-around;
    margin-top: 20px;
}

.feature-card {
    background-color: #f9f9f9;
    padding: 20px;
    border-radius: 8px;
    width: 30%;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.feature-card h3 {
    margin-bottom: 10px;
    font-size: 24px;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

.footer-content h3 {
    margin-bottom: 10px;
}

.footer-content p {
    margin-bottom: 20px;
}

.socials a {
    color: #fff;
    margin-right: 10px;
    text-decoration: none;
}

.socials a:hover {
    color: #ff6f61;
}

</style>
