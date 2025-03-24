# BML-WEBSITE
"My personal website showcasing my work, skills, and projects."
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BML WEBSITE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to BML WEB SITE</h1>
        <nav>
            <a href="#HOME">HOME</a>
            <a href="#CONTENT">CONTENT</a>
            <a href="#contact">Contact</a>
            <a href="#ABOUT">ABOUT</a>
          
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>This is a simple website built using HTML, CSS, and JavaScript.</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Web Development</li>
                <li>SEO Optimization</li>
                <li>Graphic Design</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" required>

                <button type="submit">Send</button>
            </form>
            <p id="message"></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Website. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
