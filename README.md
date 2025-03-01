<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student-Friendly Media Platform</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Student Media Platform</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#login">Login</a></li>
                <li><a href="#signup">Sign Up</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome to the Student Media Platform</h2>
            <p>Seamless video streaming and easy access to your favorite educational content.</p>
            <video id="videoPlayer" controls>
                <source src="video/sample.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Learn more about our mission to provide quality education through media.</p>
        </section>

        <section id="login">
            <h2>Login</h2>
            <form id="loginForm">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
                <button type="submit">Login</button>
            </form>
        </section>

        <section id="signup">
            <h2>Sign Up</h2>
            <form id="signupForm">
                <label for="new-username">Username:</label>
                <input type="text" id="new-username" name="new-username" required>
                <label for="new-password">Password:</label>
                <input type="password" id="new-password" name="new-password" required>
                <button type="submit">Sign Up</button>
            </form>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Have any questions? Feel free to reach out!</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Student Media Platform. All rights reserved.</p>
    </footer>

    <script src="app.js"></script>
</body>
</html># Online-Platform

/* styles.css */

/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
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

main {
    padding: 20px;
}

section {
    margin-bottom: 30px;
    background-color: white;
    padding: 15px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Home Section */
#home video {
    display: block;
    max-width: 100%;
    height: auto;
    margin-top: 10px;
}

#home p {
    font-size: 1.2em;
    color: #333;
}

/* About Section */
#about p {
    font-size: 1em;
    color: #666;
}

/* Forms */
form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-top: 10px;
}

form input {
    padding: 8px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    padding: 10px;
    margin-top: 15px;
    border: none;
    background-color: #4CAF50;
    color: white;
    font-size: 1em;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background-color: #45a049;
}

/* Contact Section */
#contact p {
    font-size: 1em;
    color: #666;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}
