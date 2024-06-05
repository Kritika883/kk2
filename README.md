<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Accessible Me</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;500&family=Stictitl+Bold:ital,wght@0,300;1,500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/main.css">
</head>
<body>
    <a href="#main-content" class="skip-link">Skip to main content</a>
    <header class="site-header">
        <h1>Cute Owl Studio</h1>
        <nav class="main-nav" role="navigation" aria-label="Main Navigation">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Reservation</a></li>
                <li><a href="#">Studio</a></li>
            </ul>
        </nav>
    </header>
    <main class="main-content" role="main" id="main-content">
        <h1>Welcome to Cute Owl</h1>
        <p>Treat your body to our luxurious Dreamy Feather-infused Body Scrub, with finely ground owl feathers and skin-loving oils to gently buff dry skin, revealing a softer, smoother, and more radiant complexion.</p>
        <p>Each product from "Cute Owl Studio" is thoughtfully crafted to provide a delightful skincare experience inspired by the beauty and wisdom of owls.</p>

<section class="Owner"
    <h1>Meet the Owner</h1>
    <ul>
        <li>Name: kritika</li>
        <li>Title: CEO</li>
        <li>Email: <a href="mailto:kritikadream@cuteowl.ca">kritikadream@cuteowl.ca</a></li>
        <li>Phone: <a href="tel:+4376698837">437-669-8837</a></li>
    </ul>
</section>
<section>
    <h1>Address</h1>
    <p>
        Cute Owl Studios<br>
        123 Main Road,<br>
        London, Ontario<br>
        L3V 4Q7
    </p>
</section>
<section class="contact-section">
    <h1>Contact Us</h1>
    <form action="thanks.html">
        <label for="fullName">Full Name</label>
        <input type="text" id="fullName" name="fullName" placeholder="Full Name" aria-label="Full Name" required>
        
        <label for="emailAddress">Email Address</label>
        <input type="email" id="emailAddress" name="emailAddress" placeholder="Email Address" aria-label="Email Address" required>
        
        <label for="subject">Subject</label>
        <input type="text" id="subject" name="subject" placeholder="Subject" aria-label="Subject" required>
        
        <label for="message">Your Message</label>
        <textarea id="message" name="message" placeholder="Your Message" aria-label="Your Message" required></textarea>
        
        <button type="submit">Send</button>
    </form>
</section>
</main>
<footer class="site-footer" role="contentinfo">
&copy; 2022 Cute Owl Studio
</footer>
</body>
</html>

