# Ex02 Commercial Website
## Date: 01/11/2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

<<<<<<< HEAD
### HTML Code (index.html)
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NEXORA | Ideas Into Impact</title>
    <link rel="stylesheet" href="style.css">

    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@400;600;700;800&display=swap" rel="stylesheet">
</head>

<body>

    <!-- HEADER -->
    <header>
        <nav class="navbar">
            <a href="#home" class="logo">
                <span class="logo-icon">N</span>
                NEXORA<span class="dot">.</span>
            </a>

            <input type="checkbox" id="menu-toggle">
            <label for="menu-toggle" class="menu-icon">☰</label>

            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#account" class="nav-button">My Account</a></li>
            </ul>
        </nav>
    </header>

    <!-- HOME SECTION -->
    <section id="home" class="hero">
        <div class="hero-content">
            <p class="tagline">THINK BIG. BUILD BETTER.</p>

            <h1>Ideas into <span>Impact.</span></h1>

            <p class="hero-description">
                Welcome to NEXORA. We transform creative ideas
                into meaningful digital experiences and innovative
                business solutions.
            </p>

            <a href="#services" class="main-button">
                Explore Services →
            </a>
        </div>

        <div class="hero-image">
            <img
                src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=1200&q=85"
                alt="Modern professional workspace">
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="about">
        <p class="section-tag">01 / ABOUT NEXORA</p>

        <h2>Where Innovation Meets <span>Purpose.</span></h2>

        <p>
            NEXORA is a forward-thinking brand focused on creating
            useful, intuitive and engaging experiences.
            Our goal is to connect ideas, creativity and technology
            to build better opportunities for everyone.
        </p>
    </section>

    <!-- SERVICES SECTION -->
    <section id="services" class="services">

        <div class="section-heading">
            <p class="section-tag">02 / OUR SERVICES</p>
            <h2>What We <span>Offer</span></h2>
            <p>Discover possibilities with NEXORA.</p>
        </div>

        <div class="service-container">

            <div class="service-card">
                <img
                    src="https://images.unsplash.com/photo-1558655146-9f40138edfeb?auto=format&fit=crop&w=800&q=80"
                    alt="Creative digital design">

                <div class="card-content">
                    <h3>Digital Solutions</h3>
                    <p>
                        Modern digital experiences designed
                        to make everyday interactions easier.
                    </p>
                    <a href="#contact">Learn More →</a>
                </div>
            </div>

            <div class="service-card">
                <img
                    src="https://images.unsplash.com/photo-1552664730-d307ca884978?auto=format&fit=crop&w=800&q=80"
                    alt="Business team collaboration">

                <div class="card-content">
                    <h3>Business Solutions</h3>
                    <p>
                        Smart and practical approaches
                        that help businesses grow.
                    </p>
                    <a href="#contact">Learn More →</a>
                </div>
            </div>

            <div class="service-card">
                <img
                    src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=800&q=80"
                    alt="Business analytics dashboard">

                <div class="card-content">
                    <h3>Innovation</h3>
                    <p>
                        Creative thinking and fresh ideas
                        for future opportunities.
                    </p>
                    <a href="#contact">Learn More →</a>
                </div>
            </div>

        </div>
    </section>

    <!-- ACCOUNT SECTION -->
    <section id="account" class="account">
        <div>
            <p class="section-tag">03 / USER ACCOUNT</p>
            <h2>Your Journey Starts <span>Here.</span></h2>
            <p>
                Become part of the NEXORA experience.
                Connect with us and explore new opportunities.
            </p>
            <a href="#contact" class="main-button">
                Get Started →
            </a>
        </div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="contact">

        <div class="contact-info">
            <p class="section-tag">04 / CONTACT US</p>
            <h2>Let's Start a <span>Conversation.</span></h2>

            <p>
                Have an idea or a question?
                We'd love to hear from you.
            </p>

            <p><strong>Email:</strong> hello@nexora.com</p>
            <p><strong>Location:</strong> India</p>
        </div>

        <form class="contact-form" action="#" method="get">

            <label for="name">Your Name</label>
            <input type="text" id="name" placeholder="Enter your name" required>

            <label for="email">Email Address</label>
            <input type="email" id="email" placeholder="Enter your email" required>

            <label for="message">Your Message</label>
            <textarea id="message" rows="5"
                placeholder="Write your message..." required></textarea>

            <button type="submit">Send Message →</button>

        </form>

    </section>

    <!-- FOOTER -->
    <footer>

        <div class="footer-content">

            <div>
                <a href="#home" class="logo">
                    <span class="logo-icon">N</span>
                    NEXORA<span class="dot">.</span>
                </a>

                <p>Ideas into Impact.</p>
            </div>

            <div class="footer-links">
                <h3>Quick Links</h3>
                <a href="#home">Home</a>
                <a href="#about">About Us</a>
                <a href="#services">Services</a>
                <a href="#contact">Contact</a>
            </div>

            <div class="social-links">
                <h3>Follow Us</h3>
                <a href="https://www.instagram.com/">Instagram ↗</a>
                <a href="https://www.linkedin.com/">LinkedIn ↗</a>
                <a href="https://www.youtube.com/">YouTube ↗</a>
            </div>

        </div>

        <div class="copyright">
            <p>© 2026 NEXORA. All Rights Reserved.</p>
            <p>Made for What's Next.</p>
        </div>

    </footer>

</body>
</html>

```
### CSS Code (style.css)
```

/* GLOBAL STYLING */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

:root {
    --navy: #101b2b;
    --green: #c8f169;
    --white: #ffffff;
    --gray: #657184;
    --light: #f5f7f8;
}

body {
    font-family: 'DM Sans', sans-serif;
    color: var(--navy);
    background: var(--white);
}

h1, h2, h3 {
    font-family: 'Manrope', sans-serif;
}

a {
    text-decoration: none;
    color: inherit;
}

/* HEADER */

header {
    background: var(--navy);
    position: sticky;
    top: 0;
    z-index: 100;
}

.navbar {
    min-height: 80px;
    padding: 0 8%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;
    color: white;
    font-size: 25px;
    font-weight: 800;
}

.logo-icon {
    background: var(--green);
    color: var(--navy);
    padding: 5px 12px;
    border-radius: 8px;
}

.dot {
    color: var(--green);
}

.nav-links {
    display: flex;
    align-items: center;
    list-style: none;
    gap: 30px;
}

.nav-links a {
    color: white;
    font-size: 14px;
    transition: 0.3s;
}

.nav-links a:hover {
    color: var(--green);
}

.nav-button {
    background: var(--green);
    color: var(--navy) !important;
    padding: 12px 18px;
    border-radius: 5px;
}

#menu-toggle,
.menu-icon {
    display: none;
}

/* HOME */

.hero {
    min-height: 600px;
    background: var(--navy);
    color: white;
    padding: 80px 8%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 50px;
}

.hero-content {
    flex: 1;
}

.tagline,
.section-tag {
    color: #829b50;
    font-size: 13px;
    font-weight: bold;
    letter-spacing: 2px;
    margin-bottom: 25px;
}

.tagline {
    color: var(--green);
}

.hero h1 {
    font-size: clamp(50px, 7vw, 85px);
    line-height: 1.1;
    margin-bottom: 25px;
}

.hero h1 span {
    color: var(--green);
}

.hero-description {
    color: #c1cad5;
    line-height: 1.8;
    max-width: 480px;
    margin-bottom: 35px;
}

.main-button {
    display: inline-block;
    background: var(--green);
    color: var(--navy);
    padding: 15px 25px;
    border-radius: 5px;
    font-weight: bold;
    transition: 0.3s;
}

.main-button:hover {
    transform: translateY(-4px);
    background: white;
}

.hero-image {
    flex: 1;
    height: 420px;
}

.hero-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 8px;
}

/* ABOUT */

.about {
    padding: 110px 12%;
    text-align: center;
}

.about h2 {
    font-size: clamp(30px, 5vw, 50px);
    margin-bottom: 25px;
}

.about h2 span,
.contact h2 span {
    color: #829b50;
}

.about > p:last-child {
    max-width: 750px;
    margin: auto;
    color: var(--gray);
    line-height: 2;
}

/* SERVICES */

.services {
    background: var(--light);
    padding: 100px 8%;
}

.section-heading {
    text-align: center;
    margin-bottom: 50px;
}

.section-heading h2 {
    font-size: 45px;
    margin-bottom: 15px;
}

.section-heading h2 span {
    color: #829b50;
}

.section-heading > p:last-child {
    color: var(--gray);
}

.service-container {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
}

.service-card {
    background: white;
    width: 31%;
    min-width: 250px;
    border: 1px solid #e5e8ec;
    transition: 0.3s;
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 35px #101b2b18;
}

.service-card img {
    width: 100%;
    height: 220px;
    object-fit: cover;
}

.card-content {
    padding: 25px;
}

.card-content h3 {
    margin-bottom: 15px;
    font-size: 22px;
}

.card-content p {
    color: var(--gray);
    font-size: 14px;
    line-height: 1.8;
    margin-bottom: 20px;
}

.card-content a {
    color: #779442;
    font-weight: bold;
}

/* ACCOUNT */

.account {
    background: var(--navy);
    color: white;
    padding: 100px 10%;
    text-align: center;
}

.account h2 {
    font-size: 45px;
    margin-bottom: 20px;
}

.account h2 span {
    color: var(--green);
}

.account p:not(.section-tag) {
    color: #b9c3d0;
    margin: 15px auto 30px;
    max-width: 600px;
    line-height: 1.8;
}

/* CONTACT */

.contact {
    padding: 100px 10%;
    display: flex;
    justify-content: space-between;
    gap: 60px;
}

.contact-info,
.contact-form {
    flex: 1;
}

.contact h2 {
    font-size: 40px;
    margin-bottom: 25px;
}

.contact-info > p:not(.section-tag) {
    color: var(--gray);
    margin-bottom: 20px;
    line-height: 1.8;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 12px;
    padding: 30px;
    background: var(--light);
}

.contact-form label {
    font-weight: bold;
    font-size: 14px;
}

.contact-form input,
.contact-form textarea {
    padding: 14px;
    border: 1px solid #dce1e7;
    border-radius: 5px;
    font-family: inherit;
    outline: none;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: #829b50;
}

.contact-form button {
    padding: 15px;
    border: none;
    border-radius: 5px;
    background: var(--green);
    color: var(--navy);
    font-size: 15px;
    font-weight: bold;
    cursor: pointer;
    transition: 0.3s;
}

.contact-form button:hover {
    background: var(--navy);
    color: white;
}

/* FOOTER */

footer {
    background: #0b1421;
    color: white;
    padding: 60px 8% 20px;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 40px;
    padding-bottom: 45px;
}

.footer-content p {
    color: #9ca9b9;
    margin-top: 15px;
}

.footer-links,
.social-links {
    display: flex;
    flex-direction: column;
    gap: 12px;
}

.footer-links h3,
.social-links h3 {
    margin-bottom: 10px;
    color: var(--green);
}

.footer-links a,
.social-links a {
    color: #bdc7d3;
    font-size: 14px;
    transition: 0.3s;
}

.footer-links a:hover,
.social-links a:hover {
    color: var(--green);
}

.copyright {
    border-top: 1px solid #ffffff25;
    padding-top: 20px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
    color: #8794a6;
    font-size: 13px;
}

/* RESPONSIVE DESIGN */

@media (max-width: 768px) {

    .navbar {
        padding: 15px 5%;
        flex-wrap: wrap;
    }

    .menu-icon {
        display: block;
        color: white;
        font-size: 25px;
        cursor: pointer;
    }

    .nav-links {
        display: none;
        width: 100%;
        flex-direction: column;
        align-items: flex-start;
        gap: 20px;
        padding: 20px 0;
    }

    #menu-toggle:checked ~ .nav-links {
        display: flex;
    }

    .hero {
        flex-direction: column;
        padding: 65px 6%;
    }

    .hero-image {
        width: 100%;
        height: 300px;
    }

    .about,
    .services,
    .contact {
        padding: 70px 6%;
    }

    .service-card {
        width: 100%;
    }

    .contact {
        flex-direction: column;
    }

    .account h2 {
        font-size: 32px;
    }

    .footer-content {
        flex-direction: column;
    }

    .copyright {
        flex-direction: column;
    }
}

/* ACCESSIBILITY */

@media (prefers-reduced-motion: reduce) {
    *,
    *::before,
    *::after {
        scroll-behavior: auto !important;
        transition: none !important;
    }
}
```
## OUTPUT
![Commercial Website Screenshot](./s-1.png)
=======

## OUTPUT

>>>>>>> 57b8893df594163faeeb67682afbd93c5bacc1bd

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
