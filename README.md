!DOCTYPE html>
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
            <h1>Your Name</h1>
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
        <h2>About Me</h2>
        <p>Welcome to my e-portfolio! I'm a web developer passionate about building interactive websites and applications. Feel free to explore my projects and skills below!</p>
        <img src="profile.jpg" alt="Your Photo" width="150" height="150">
    </section>

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
        <h2>My Projects</h2>
        <div class="project-card">
            <h3>Project 1: Portfolio Website</h3>
            <p>A personal portfolio website built with HTML, CSS, and JavaScript to showcase my work and skills.</p>
            <a href="https://github.com/yourusername/portfolio" target="_blank">View Project</a>
        </div>
        <div class="project-card">
            <h3>Project 2: Task Manager App</h3>
            <p>A task management app built with React.js and Firebase for real-time data storage.</p>
            <a href="https://github.com/yourusername/task-manager" target="_blank">View Project</a>
        </div>
    </section>

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
