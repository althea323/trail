<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - E-Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <h1>STENVALL</h1>
            <nav>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about" class="section">
        <h2>Good at Swimming</h2>
    <section id="skills" class="section">
        <h2>Skills</h2>
        <ul>
            <li>HTML & CSS</li>
            <li>JavaScript & jQuery</li>
            <li>React.js</li>
            <li>Node.js</li>
            <li>Git & GitHub</li>
            <li>Responsive Design</li>
        </ul>
    </section>

    <section id="projects" class="section">
        <h2>Researches </h2>
        <div class="project-card">
    <section id="contact" class="section">
        <h2>Contact</h2>
        <p>If you'd like to get in touch, feel free to send me a message!</p>
        <form action="mailto:your.email@example.com" method="get">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Your Name</p>
    </footer>

</body>
</html>
