<!DOCTYPE html>
<html lang="en">
<head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Science Student Portfolio</title>
    <style>
        /* Import Google Font */
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #faf0e6;
            color: #333;
            display: flex;
        }

        /* Sidebar Navigation */
        .sidebar {
            position: fixed;
            top: 0;
            left: 0;
            width: 200px;
            height: 100vh;
            background: #333;
            padding-top: 20px;
        }

        .sidebar ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        .sidebar ul li {
            padding: 15px 0;
        }

        .sidebar ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
            display: block;
            transition: background 0.3s;
            padding: 10px;
        }

        .sidebar ul li a:hover {
            background: #444;
        }

        /* Main Content */
        .main-content {
            margin-left: 220px; /* Adjusted for sidebar */
            padding: 40px;
            width: calc(100% - 220px);
        }

        /* Header (Hero Section) */
        .hero {
            background: url('https://virtual-bg.com/wp-content/uploads/2020/06/peppa-pig.png') no-repeat center center/cover;
            height: 50vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 20px;
            position: relative;
        }

        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        .hero h1 {
            font-size: 6.5rem;
            font-weight: 600;
        }

        .hero p {
            font-size: 1.5rem;
            font-weight: 300;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            max-width: 800px;
            margin: auto;
            text-align: center;
        }

        h2 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        /* Projects */
        .project {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px 0;
        }

        .project h3 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .project p {
            font-size: 1.2rem;
        }

        .btn {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #0056b3;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <!-- Sidebar Navigation -->
    <nav class="sidebar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#activities">Activities</a></li>
            <li><a href="#student-outcomes">Student Outcomes</a></li>
        </ul>
    </nav>

    <!-- Main Content -->
    <div class="main-content">
        <header id="home" class="hero">
            <div class="hero-content">
                <h1>Computer Science <br> Student Portfolio</h1>
                <p>Welcome to my e-portfolio!</p>
            </div>
        </header>

        <section id="about">
            <h2>About Me</h2>
            <p>This portfolio displays the conceptual, aesthetic, and creative development of Computer Science students from Mapua University. <br><br>
Learning is a complex phenomenon, either vertical or horizontal advancement can be well represented by a student's learning. <br><br>
Hence, this portfolio acts as a collection of a student's academic progress.<br>
</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Experimental Research</h3>
                <p>Description of project 1.</p>
                <a href="https://link-to-your-project.com" target="_blank" class="btn">View Project</a>
            </div>
            <div class="project">
                <h3>Project Title 2</h3>
                <p>Description of project 2.</p>
                <a href="https://link-to-your-project.com" target="_blank" class="btn">View Project</a>
            </div>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>ML Player</li>
                <li>Mukbang</li>
                <li>Kumon</li>
            </ul>
        </section>

        <section id="activities">
            <h2>Activities</h2>
            <p>List of activities here...</p>
        </section>

        <section id="student-outcomes">
            <h2>Student Outcomes</h2>
            <p>Information about student outcomes...</p>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>Facebook: <a href="https://www.facebook.com/jp.ferrer.311" target="_blank">JP Ferrer</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" target="_blank">Your LinkedIn Profile</a></p>
        </section>

        <footer>
            <p>&copy; 2024 JP Ferrer. All rights reserved.</p>
        </footer>
    </div>

</body>
</html>
