<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A basic webpage with text, images, and links for learning HTML structure.">
    <title>Basic Webpage Design</title>
</head>
<body>

    <!-- Header section -->
    <header>
        <h1>Welcome to My Basic Webpage</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main content section -->
    <main>
        <!-- About Section -->
        <section id="about">
            <h2>About This Webpage</h2>
            <p>This is a simple webpage designed to showcase how to use common HTML tags, including text, images, and links. It is also organized with semantic tags like <code>header</code>, <code>footer</code>, <code>nav</code>, <code>section</code>, and <code>article</code> for SEO and readability.</p>
        </section>

        <!-- Image Section -->
        <section id="images">
            <h2>Images</h2>
            <img src="https://via.placeholder.com/400x200" alt="Sample Image" />
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Our Services</h2>
            <article>
                <h3>Web Development</h3>
                <p>We provide high-quality web development services tailored to your needs.</p>
            </article>
            <article>
                <h3>SEO Optimization</h3>
                <p>Our SEO services will help improve your website's search engine rankings.</p>
            </article>
        </section>

        <!-- Links Section -->
        <section id="links">
            <h2>Useful Links</h2>
            <ul>
                <li><a href="https://www.w3schools.com" target="_blank">W3Schools</a></li>
                <li><a href="https://www.mozilla.org/en-US/docs/Web/HTML" target="_blank">MDN Web Docs</a></li>
                <li><a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a></li>
            </ul>
        </section>
    </main>

    <!-- Footer section -->
    <footer>
        <p>&copy; 2024 My Basic Webpage. All Rights Reserved.</p>
        <p>Follow us on <a href="https://twitter.com" target="_blank">Twitter</a> and <a href="https://facebook.com" target="_blank">Facebook</a>.</p>
    </footer>

</body>
</html>


