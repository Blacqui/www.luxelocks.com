<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A premier hair salon offering beautiful African hairstyles and more for all hair types.">
    <title>African Hairstyles Salon</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="images/favicon.ico">
</head>

<body>
    <!-- Header Section -->
    <header>
        <nav>
            <div class="logo">
                <h1>African Hair Styles</h1>
            </div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h2>Transform Your Hair, Embrace Your Style</h2>
        <p>We specialize in African hairstyles, braids, twists, and more. But we're here for every hair type, creating unique looks just for you.</p>
        <a href="#services" class="cta-btn">Explore Our Services</a>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="service-cards">
            <div class="service-card">
                <img src="images/african-braids.jpg" alt="African Braids">
                <h3>African Braids</h3>
                <p>Beautiful and intricate braids, from box braids to cornrows, designed to suit all styles and personalities.</p>
            </div>
            <div class="service-card">
                <img src="images/afro-styling.jpg" alt="Afro Styling">
                <h3>Afro Styling</h3>
                <p>Classic and modern afro styles that emphasize the beauty and versatility of natural curls.</p>
            </div>
            <div class="service-card">
                <img src="images/wigs-haircuts.jpg" alt="Wigs and Haircuts">
                <h3>Wigs & Haircuts</h3>
                <p>Custom wigs, haircuts, and extensions to suit every occasion and personality.</p>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="gallery-grid">
            <div class="gallery-item"><img src="images/gallery1.jpg" alt="Hairstyle 1"></div>
            <div class="gallery-item"><img src="images/gallery2.jpg" alt="Hairstyle 2"></div>
            <div class="gallery-item"><img src="images/gallery3.jpg" alt="Hairstyle 3"></div>
            <div class="gallery-item"><img src="images/gallery4.jpg" alt="Hairstyle 4"></div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Ready for a new look? Book an appointment or ask a question.</p>
        <form id="appointment-form">
            <input type="text" id="name" placeholder="Your Name" required>
            <input type="email" id="email" placeholder="Your Email" required>
            <input type="text" id="phone" placeholder="Your Phone Number" required>
            <textarea id="message" placeholder="Tell us about your desired hairstyle" required></textarea>
            <button type="submit">Book Appointment</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 African Hairstyles Salon | Designed by YourName</p>
    </footer>

    <script src="script.js"></script>
</body>

</html>
/* Global Styles */
body, h1, h2, h3, p {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

body {
    background-color: #f4f4f4;
    color: #333;
}

a {
    text-decoration: none;
    color: inherit;
}

/* Header */
header {
    background-color: #2a2a2a;
    color: #fff;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style: none;
    display: flex;
}

header nav ul li {
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background-image: url('images/hero-background.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 80px 20px;
}

.hero h2 {
    font-size: 3em;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

.cta-btn {
    background-color: #fbbf24;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 1.2em;
}

/* Services Section */
.services {
    text-align: center;
    padding: 50px 20px;
    background-color: #fff;
}

.services h2 {
    font-size: 2.5em;
    margin-bottom: 40px;
}

.service-cards {
    display: flex;
    justify-content: center;
    gap: 30px;
}

.service-card {
    background-color: #f9f9f9;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
    width: 250px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.service-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
}

.service-card h3 {
    font-size: 1.5em;
    margin-top: 15px;
}

.service-card p {
    font-size: 1em;
    margin-top: 10px;
}

/* Gallery Section */
.gallery {
    padding: 50px 20px;
    text-align: center;
    background-color: #f4f4f4;
}

.gallery h2 {
    font-size: 2.5em;
    margin-bottom: 40px;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
}

.gallery-item img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 10px;
}

/* Contact Section */
.contact {
    padding: 50px 20px;
    background-color: #fff;
    text-align: center;
}

.contact h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
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
    background-color: #fbbf24;
    border: none;
    color: #fff;
    font-size: 1.2em;
    cursor: pointer;
}
form button:hover {
    background-color: #f59e0b;
}
/* Footer */
footer {
    background-color: #2a2a2a;
    color: #fff;
    text-align: center;
    padding: 20px;
}
document.getElementById('appointment-form').addEventListener('submit', function(event) {
    event.preventDefault();
   
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const phone = document.getElementById('phone').value;
    const message = document.getElementById('message').value;

    if (name && email && phone && message) {
        alert('Thank you for your submission! We will get back to you soon.');
    } else {
        alert('Please fill in all fields!');
    }
});
