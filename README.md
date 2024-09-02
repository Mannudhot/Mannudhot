<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Welcome to My Blog</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <div class="container">
            <section id="home">
                <h2>Latest Posts</h2>
                <!-- Example of a blog post -->
                <article class="post">
                    <h3>Blog Post Title</h3>
                    <p class="post-date">Published on: September 2, 2024</p>
                    <p>This is a sample blog post content. You can write about any topic here.</p>
                    <a href="#" class="read-more">Read More</a>
                </article>
            </section>

            <!-- About Section -->
            <section id="about">
                <h2>About Me</h2>
                <p>Hi, I'm [Your Name]. Welcome to my blog where I share insights and thoughts on various topics.</p>
            </section>

            <!-- Contact Section -->
            <section id="contact">
                <h2>Contact Me</h2>
                <form>
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>

                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>

                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="5" required></textarea>

                    <button type="submit">Send</button>
                </form>
            </section>
        </div>
    </main>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 My Blog. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script> <!-- Link to your JavaScript file -->
</body>
</html>
/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

/* Header */
header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 10px 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Main Content */
main {
    padding: 20px 0;
}

section {
    margin-bottom: 40px;
}

.post {
    background-color: #fff;
    padding: 15px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
}

.post h3 {
    margin-top: 0;
}

.read-more {
    color: #333;
    text-decoration: none;
    font-weight: bold;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
// Example: Form validation or interactive behavior
document.addEventListener("DOMContentLoaded", function() {
    const form = document.querySelector('form');

    form.addEventListener('submit', function(event) {
        alert("Form submitted successfully!");
        event.preventDefault(); // Prevent the default form submission behavior
    });
});
