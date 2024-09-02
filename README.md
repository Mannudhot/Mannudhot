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
