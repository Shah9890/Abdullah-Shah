<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Standards - Premier Taxi Services in Dubai</title>
    <link rel="stylesheet" href="company.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Modern Standards</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#fleet">Our Fleet</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    * General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Navigation Bar */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #000;
    padding: 15px 50px;
}

nav .logo {
    font-size: 24px;
    color: #fff;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-size: 18px;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #ffcc00;
}

/* Hero Section */
.hero {
    background: url('images/taxi.jpg') no-repeat center center/cover;
    height: 90vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: white;
    text-align: center;
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 20px;
    margin-bottom: 20px;
}

.btn {
    background: #ffcc00;
    color: #000;
    padding: 12px 20px;
    font-size: 18px;
    border-radius: 5px;
    text-decoration: none;
    transition: 0.3s;
}

.btn:hover {
    background: #ff9900;
}

/* Sections */
section {
    padding: 60px;
    text-align: center;
    background: white;
    margin-bottom: 20px;
}

section:nth-child(even) {
    background: #ddd;
}

/* Services */
.service {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
}

.service img {
    width: 300px;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    margin-bottom: 10px;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #000;
    color: #fff;
}
/* Chatbot Container */
.chat-container {
    width: 350px;
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #fff;
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
    overflow: hidden;
    font-family: Arial, sans-serif;
}

/* Chat Header */
.chat-header {
    background: #007bff;
    color: white;
    padding: 10px;
    text-align: center;
    font-weight: bold;
}

/* Chat Box */
.chat-box {
    height: 300px;
    overflow-y: auto;
    padding: 10px;
    background: #f9f9f9;
}

/* Messages */
.bot-message, .user-message {
    padding: 8px;
    margin: 5px 0;
    border-radius: 5px;
    max-width: 80%;
}

.bot-message {
    background: #e1f5fe;
    align-self: flex-start;
}

.user-message {
    background: #dcf8c6;
    align-self: flex-end;
    text-align: right;
}

/* Chat Input */
.chat-input {
    display: flex;
    padding: 10px;
    border-top: 1px solid #ccc;
    background: #fff;
}

.chat-input input {
    flex: 1;
    padding: 8px;
    border: none;
    outline: none;
    border-radius: 5px;
    background: #f0f0f0;
}

.chat-input button {
    background: #007bff;
    color: white;
    border: none;
    padding: 8px 12px;
    margin-left: 5px;
    cursor: pointer;
    border-radius: 5px;
}

.chat-input button:hover {
    background: #0056b3;
}
    
    <section id="home" class="hero">
        <h1>Premium & Reliable Taxi Services in Dubai</h1>
        <p>Experience luxury and convenience with Modern Standards. Book your ride today!</p>
        <a href="#contact" class="btn">Book Now</a>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Modern Standards is a leading taxi service in Dubai, providing safe, reliable, and luxurious transportation solutions.</p>
        <img src="taxi.jpg" alt="Taxi in Dubai">
    </section>
    
    <section id="services">
        <h2>Our Services</h2>
        <div class="service">
            <img src="uber_bolt.jpg" alt="Uber and Bolt">
            <p>We collaborate with Uber and Bolt for premium ride-hailing services.</p>
        </div>
        <div class="service">
            <img src="luxury_taxi.jpg" alt="Luxury Taxi">
            <p>Experience luxury with our high-end taxi fleet.</p>
        </div>
        <div class="service">
            <img src="car.png" alt="Airport Transfers">
            <p>Reliable and on-time airport transfers.</p>
        </div>
    </section>
    
    <section id="fleet">
        <h2>Our Fleet</h2>
        <p>Choose from our range of standard, luxury, and electric vehicles.</p>
        <img src="delivery.png" alt="Modern Taxi Fleet">
    </section>
    
    <section id="testimonials">
        <h2>What Our Customers Say</h2>
        <blockquote>"Modern Standards provides the best taxi service in Dubai. Highly recommended!" - Ahmed R.</blockquote>
        <blockquote>"Luxury, comfort, and reliability - all in one. The best ride experience!" - Fatima S.</blockquote>
    </section>
    
    <section id="blog">
        <h2>Latest News & Updates</h2>
        <article>
            <h3>Top 5 Tourist Destinations to Visit in Dubai</h3>
            <p>Explore the best places to visit in Dubai with our premium taxi service.</p>
            <a href="#">Read More</a>
        </article>
    </section>
    
    <section id="app">
        <h2>Download Our App</h2>
        <p>Book rides instantly with our mobile app.</p>
        <a href="https://play.google.com" class="btn">Google Play</a>
        <a href="https://www.apple.com/app-store/" class="btn">App Store</a>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>📞 Phone: <a href="tel:92024042">92024042</a></p>
        <p>📧 Email: <a href="mailto:abdullahshah85436@gmail.com">abdullahshah85436@gmail.com</a></p>
        <p>📍 Address: Downtown Dubai, UAE</p>
    </section>
    
    <footer>
        <p>&copy; 2025 Modern Standards. All Rights Reserved.</p>
    </footer>
</body>
</html>
