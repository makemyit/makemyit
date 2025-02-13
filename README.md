<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Make My IT Returns - Tax Consultancy Services in India">
    <title>Make My IT Returns - Tax Consultancy</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header -->
    <header>
        <div class="logo">
            <h1>Make My IT Returns</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h2>Simplify Your Taxes with Expert Consultancy</h2>
        <a href="#services" class="cta-button">Get Started</a>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>Our Services</h2>
        <div class="service-item">
            <h3>Income Tax Filing</h3>
            <p>We help you file your taxes with ease and ensure you get maximum returns.</p>
        </div>
        <div class="service-item">
            <h3>GST Filing</h3>
            <p>Let us handle your GST filing and keep you compliant with the law.</p>
        </div>
        <!-- Add more services here -->
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>We are a team of expert tax consultants offering professional tax services for individuals and businesses in India.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Make My IT Returns. All rights reserved.</p>
    </footer>

</body>
</html>
/* Basic Styling for the Website */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #1a73e8;
    padding: 20px;
    color: white;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    background-color: #2d9cdb;
    color: white;
    text-align: center;
    padding: 50px 0;
}

.cta-button {
    background-color: #f39c12;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.cta-button:hover {
    background-color: #e67e22;
}

#services {
    background-color: white;
    padding: 50px 20px;
    text-align: center;
}

.service-item {
    margin: 20px;
    padding: 20px;
    background-color: #ececec;
    border-radius: 8px;
}

#about, #contact {
    padding: 50px 20px;
    text-align: center;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
}

form button {
    padding: 10px 20px;
    background-color: #1a73e8;
    color: white;
    border: none;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

footer p {
    margin: 0;
}
