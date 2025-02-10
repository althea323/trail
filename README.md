/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 20px;
}

.navbar h1 {
    display: inline;
    font-size: 2rem;
}

nav ul {
    list-style: none;
    float: right;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Section Styles */
.section {
    padding: 40px;
    margin: 20px 0;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    text-align: center;
    margin-bottom: 20px;
}

img {
    display: block;
    margin: 20px auto;
    width: 150px;
    height: 150px;
    border-radius: 50%;
}

ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

ul li {
    display: inline-block;
    margin: 10px 20px;
}

.project-card {
    background-color: #f9f9f9;
    padding: 20px;
    margin: 10px 0;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
}

.project-card h3 {
    margin: 0;
    color: #333;
}

.project-card a {
    color: #007BFF;
    text-decoration: none;
}

/* Contact Form Styles */
form {
    display: grid;
    grid-template-columns: 1fr;
    gap: 10px;
    width: 80%;
    margin: 0 auto;
}

input, textarea {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    width: 100%;
}

button {
    padding: 10px;
    background-color: #333;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}

/* Footer Styles */
footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}
