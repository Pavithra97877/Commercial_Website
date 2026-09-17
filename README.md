# Ex02 Commercial Website
# NAME : PAVITHRA S
# REG NO : 212223220072

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
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>NOVA | Modern Store</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- NAVIGATION BAR -->

    <header>

        <div class="logo">
            NOVA
        </div>

        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>

        <a href="#products" class="nav-button">
            Shop Now
        </a>

    </header>


    <!-- HERO SECTION -->

    <section id="home" class="hero">

        <div class="hero-content">

            <p class="hero-label">
                NEW COLLECTION 2026
            </p>

            <h1>
                Technology
                <span>Made Simple.</span>
            </h1>

            <p class="hero-description">
                Discover modern technology products designed to make
                your everyday life smarter, faster and more connected.
            </p>

            <div class="hero-buttons">

                <a href="#products" class="primary-button">
                    Explore Products
                </a>

                <a href="#about" class="secondary-button">
                    Learn More
                </a>

            </div>

        </div>


        <div class="hero-card">

            <div class="hero-circle">
                NOVA
            </div>

            <p>
                Innovation for
                everyday life.
            </p>

        </div>

    </section>


    <!-- PRODUCTS -->

    <section id="products" class="products-section">

        <div class="section-heading">

            <div>
                <p class="section-label">
                    FEATURED PRODUCTS
                </p>

                <h2>
                    Explore Our Products
                </h2>
            </div>

            <p class="section-description">
                Carefully selected products combining
                quality, performance and modern design.
            </p>

        </div>


        <div class="product-container">


            <!-- PRODUCT 1 -->

            <div class="product-card">

                <div class="product-image headphone">
                    HEADPHONES
                </div>

                <div class="product-info">

                    <p class="product-category">
                        AUDIO
                    </p>

                    <h3>
                        Nova Pro Headphones
                    </h3>

                    <p>
                        Wireless noise-cancelling headphones
                        with immersive audio.
                    </p>

                    <div class="product-bottom">

                        <strong>
                            ₹7,999
                        </strong>

                        <button>
                            Add to Cart
                        </button>

                    </div>

                </div>

            </div>


            <!-- PRODUCT 2 -->

            <div class="product-card">

                <div class="product-image smartwatch">
                    SMARTWATCH
                </div>

                <div class="product-info">

                    <p class="product-category">
                        WEARABLES
                    </p>

                    <h3>
                        Nova Watch X
                    </h3>

                    <p>
                        Smart fitness tracking with a
                        premium AMOLED display.
                    </p>

                    <div class="product-bottom">

                        <strong>
                            ₹5,499
                        </strong>

                        <button>
                            Add to Cart
                        </button>

                    </div>

                </div>

            </div>


            <!-- PRODUCT 3 -->

            <div class="product-card">

                <div class="product-image keyboard">
                    KEYBOARD
                </div>

                <div class="product-info">

                    <p class="product-category">
                        ACCESSORIES
                    </p>

                    <h3>
                        Nova Mechanical Keyboard
                    </h3>

                    <p>
                        Compact mechanical keyboard
                        designed for productivity.
                    </p>

                    <div class="product-bottom">

                        <strong>
                            ₹3,999
                        </strong>

                        <button>
                            Add to Cart
                        </button>

                    </div>

                </div>

            </div>


            <!-- PRODUCT 4 -->

            <div class="product-card">

                <div class="product-image speaker">
                    SPEAKER
                </div>

                <div class="product-info">

                    <p class="product-category">
                        AUDIO
                    </p>

                    <h3>
                        Nova Sound Mini
                    </h3>

                    <p>
                        Portable wireless speaker with
                        powerful sound and long battery life.
                    </p>

                    <div class="product-bottom">

                        <strong>
                            ₹2,999
                        </strong>

                        <button>
                            Add to Cart
                        </button>

                    </div>

                </div>

            </div>

        </div>

    </section>


    <!-- SERVICES -->

    <section id="services" class="services-section">

        <p class="section-label">
            WHY CHOOSE NOVA
        </p>

        <h2>
            Built Around You
        </h2>


        <div class="services-container">

            <div class="service">

                <div class="service-icon">
                    ✓
                </div>

                <div>

                    <h3>
                        Quality Products
                    </h3>

                    <p>
                        Every product is selected with
                        quality and reliability in mind.
                    </p>

                </div>

            </div>


            <div class="service">

                <div class="service-icon">
                    ⚡
                </div>

                <div>

                    <h3>
                        Fast Delivery
                    </h3>

                    <p>
                        Get your products delivered quickly
                        and safely to your doorstep.
                    </p>

                </div>

            </div>


            <div class="service">

                <div class="service-icon">
                    ★
                </div>

                <div>

                    <h3>
                        Customer Support
                    </h3>

                    <p>
                        Our support team is always available
                        to help with your questions.
                    </p>

                </div>

            </div>

        </div>

    </section>


    <!-- ABOUT -->

    <section id="about" class="about-section">

        <div class="about-content">

            <p class="section-label">
                ABOUT NOVA
            </p>

            <h2>
                Technology that fits
                your lifestyle.
            </h2>

            <p>
                NOVA is a modern technology-focused commercial
                brand offering carefully selected products for
                everyday digital life.
            </p>

            <p>
                From audio devices and wearables to productivity
                accessories, our goal is to provide products
                that combine useful technology with simple design.
            </p>

        </div>


        <div class="about-statistics">

            <div>
                <strong>
                    10K+
                </strong>

                <span>
                    Customers
                </span>
            </div>

            <div>
                <strong>
                    50+
                </strong>

                <span>
                    Products
                </span>
            </div>

            <div>
                <strong>
                    4.8/5
                </strong>

                <span>
                    Average Rating
                </span>
            </div>

        </div>

    </section>


    <!-- CONTACT -->

    <section id="contact" class="contact-section">

        <p class="section-label">
            GET IN TOUCH
        </p>

        <h2>
            Have a question?
        </h2>

        <p>
            Our team is ready to help you find the right product.
        </p>

        <a
            href="mailto:sndpnmx@gmail.com"
            class="primary-button">
            Contact Us
        </a>

    </section>


    <!-- FOOTER -->

    <footer>

        <div class="footer-brand">

            <h3>
                NOVA
            </h3>

            <p>
                Technology made simple.
            </p>

        </div>


        <div class="footer-links">

            <h4>
                Quick Links
            </h4>

            <a href="#home">
                Home
            </a>

            <a href="#products">
                Products
            </a>

            <a href="#services">
                Services
            </a>

            <a href="#contact">
                Contact
            </a>

        </div>


        <div class="footer-contact">

            <h4>
                Contact
            </h4>

            <p>
                sndpnmx@gmail.com
            </p>

            <p>
                GitHub: NyomXD
            </p>

        </div>


        <div class="student-details">

            <h4>
                Student Details
            </h4>

            <p>
                Name: Sandeep V
            </p>

            <p>
                Register No: 212223040179
            </p>

            <p>
                B.E. Computer Science and Engineering
            </p>

        </div>

    </footer>


    <div class="copyright">

        © 2026 NOVA. All Rights Reserved.
        | Designed by Sandeep V

    </div>

</body>

</html>

style.css
/* =========================
   GLOBAL STYLES
========================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #080b12;
    color: #f8fafc;
    line-height: 1.6;
}


/* =========================
   HEADER
========================= */

header {
    display: flex;

    justify-content: space-between;

    align-items: center;

    padding: 20px 7%;

    background: #0d111b;

    border-bottom: 1px solid #202938;

    position: sticky;

    top: 0;

    z-index: 100;
}

.logo {
    font-size: 1.5rem;

    font-weight: 800;

    letter-spacing: 2px;

    color: #38bdf8;
}

nav {
    display: flex;

    gap: 30px;
}

nav a {
    text-decoration: none;

    color: #94a3b8;

    font-size: 0.9rem;

    transition: 0.3s;
}

nav a:hover {
    color: #38bdf8;
}

.nav-button {
    text-decoration: none;

    color: #06111c;

    background: #38bdf8;

    padding: 9px 18px;

    border-radius: 6px;

    font-size: 0.8rem;

    font-weight: bold;

    transition: 0.3s;
}

.nav-button:hover {
    background: #0ea5e9;

    transform: translateY(-2px);
}


/* =========================
   HERO
========================= */

.hero {
    min-height: 85vh;

    padding: 80px 7%;

    display: flex;

    justify-content: space-between;

    align-items: center;

    gap: 60px;

    background:
        radial-gradient(
            circle at 80% 40%,
            rgba(56, 189, 248, 0.12),
            transparent 35%
        );
}

.hero-content {
    max-width: 650px;
}

.hero-label,
.section-label {
    color: #38bdf8;

    font-size: 0.7rem;

    font-weight: bold;

    letter-spacing: 3px;

    margin-bottom: 15px;
}

.hero h1 {
    font-size: clamp(3rem, 7vw, 6rem);

    line-height: 1;

    margin-bottom: 25px;

    letter-spacing: -4px;
}

.hero h1 span {
    display: block;

    color: #38bdf8;
}

.hero-description {
    max-width: 580px;

    color: #94a3b8;

    font-size: 1rem;

    margin-bottom: 30px;
}

.hero-buttons {
    display: flex;

    gap: 12px;

    flex-wrap: wrap;
}

.primary-button,
.secondary-button {
    display: inline-block;

    text-decoration: none;

    padding: 12px 22px;

    border-radius: 6px;

    font-size: 0.85rem;

    font-weight: bold;

    transition: 0.3s;
}

.primary-button {
    background: #38bdf8;

    color: #06111c;
}

.primary-button:hover {
    background: #0ea5e9;

    transform: translateY(-3px);
}

.secondary-button {
    border: 1px solid #334155;

    color: #e2e8f0;
}

.secondary-button:hover {
    border-color: #38bdf8;

    color: #38bdf8;
}


/* HERO CARD */

.hero-card {
    width: 350px;

    height: 350px;

    flex-shrink: 0;

    border: 1px solid #1e293b;

    border-radius: 20px;

    background: #101827;

    display: flex;

    flex-direction: column;

    justify-content: center;

    align-items: center;

    box-shadow: 0 25px 60px rgba(0, 0, 0, 0.4);
}

.hero-circle {
    width: 190px;

    height: 190px;

    border-radius: 50%;

    display: flex;

    align-items: center;

    justify-content: center;

    border: 2px solid #38bdf8;

    color: #38bdf8;

    font-size: 2rem;

    font-weight: bold;

    letter-spacing: 4px;

    box-shadow:
        0 0 30px rgba(56, 189, 248, 0.2);
}

.hero-card p {
    margin-top: 25px;

    color: #94a3b8;

    font-size: 0.8rem;
}


/* =========================
   PRODUCTS
========================= */

.products-section {
    padding: 100px 7%;
}

.section-heading {
    display: flex;

    justify-content: space-between;

    align-items: flex-end;

    gap: 30px;

    margin-bottom: 45px;
}

.section-heading h2,
.services-section h2,
.about-section h2,
.contact-section h2 {
    font-size: 2.4rem;

    line-height: 1.2;
}

.section-description {
    max-width: 400px;

    color: #64748b;

    font-size: 0.85rem;
}


/* FLEXBOX PRODUCT CONTAINER */

.product-container {
    display: flex;

    flex-wrap: wrap;

    gap: 22px;
}


/* PRODUCT CARD */

.product-card {
    flex: 1 1 240px;

    min-width: 230px;

    background: #101827;

    border: 1px solid #1e293b;

    border-radius: 12px;

    overflow: hidden;

    transition: 0.3s;
}

.product-card:hover {
    transform: translateY(-7px);

    border-color: #38bdf8;

    box-shadow:
        0 15px 35px rgba(0, 0, 0, 0.3);
}


/* PRODUCT IMAGE */

.product-image {
    height: 190px;

    display: flex;

    align-items: center;

    justify-content: center;

    font-size: 1.1rem;

    font-weight: bold;

    letter-spacing: 3px;

    color: #e2e8f0;
}

.headphone {
    background:
        linear-gradient(
            135deg,
            #164e63,
            #0f172a
        );
}

.smartwatch {
    background:
        linear-gradient(
            135deg,
            #312e81,
            #0f172a
        );
}

.keyboard {
    background:
        linear-gradient(
            135deg,
            #3f3f46,
            #0f172a
        );
}

.speaker {
    background:
        linear-gradient(
            135deg,
            #134e4a,
            #0f172a
        );
}


/* PRODUCT INFO */

.product-info {
    padding: 22px;
}

.product-category {
    color: #38bdf8;

    font-size: 0.6rem;

    font-weight: bold;

    letter-spacing: 2px;

    margin-bottom: 8px;
}

.product-info h3 {
    font-size: 1.05rem;

    margin-bottom: 10px;
}

.product-info p {
    color: #94a3b8;

    font-size: 0.78rem;

    margin-bottom: 20px;
}

.product-bottom {
    display: flex;

    justify-content: space-between;

    align-items: center;

    gap: 10px;
}

.product-bottom strong {
    color: #f8fafc;

    font-size: 1.1rem;
}

.product-bottom button {
    border: 1px solid #334155;

    background: transparent;

    color: #38bdf8;

    padding: 7px 12px;

    border-radius: 5px;

    cursor: pointer;

    font-size: 0.7rem;

    transition: 0.3s;
}

.product-bottom button:hover {
    background: #38bdf8;

    color: #06111c;
}


/* =========================
   SERVICES
========================= */

.services-section {
    padding: 100px 7%;

    background: #0d111b;
}

.services-section h2 {
    margin-bottom: 40px;
}


/* FLEXBOX */

.services-container {
    display: flex;

    flex-wrap: wrap;

    gap: 20px;
}

.service {
    flex: 1 1 280px;

    display: flex;

    align-items: flex-start;

    gap: 18px;

    padding: 25px;

    background: #101827;

    border: 1px solid #1e293b;

    border-radius: 10px;

    transition: 0.3s;
}

.service:hover {
    border-color: #38bdf8;

    transform: translateY(-4px);
}

.service-icon {
    width: 42px;

    height: 42px;

    flex-shrink: 0;

    display: flex;

    align-items: center;

    justify-content: center;

    border-radius: 7px;

    background: rgba(56, 189, 248, 0.1);

    color: #38bdf8;

    font-weight: bold;
}

.service h3 {
    font-size: 1rem;

    margin-bottom: 7px;
}

.service p {
    color: #94a3b8;

    font-size: 0.75rem;
}


/* =========================
   ABOUT
========================= */

.about-section {
    padding: 100px 7%;

    display: flex;

    justify-content: space-between;

    align-items: center;

    gap: 70px;
}

.about-content {
    max-width: 650px;
}

.about-content h2 {
    margin-bottom: 25px;
}

.about-content p {
    color: #94a3b8;

    font-size: 0.9rem;

    margin-bottom: 15px;
}


/* FLEXBOX STATS */

.about-statistics {
    display: flex;

    gap: 15px;

    flex-wrap: wrap;
}

.about-statistics div {
    min-width: 120px;

    padding: 25px 20px;

    background: #101827;

    border: 1px solid #1e293b;

    border-radius: 10px;

    text-align: center;
}

.about-statistics strong {
    display: block;

    color: #38bdf8;

    font-size: 1.5rem;

    margin-bottom: 5px;
}

.about-statistics span {
    color: #94a3b8;

    font-size: 0.7rem;
}


/* =========================
   CONTACT
========================= */

.contact-section {
    padding: 100px 7%;

    text-align: center;

    background:
        radial-gradient(
            circle,
            rgba(56, 189, 248, 0.08),
            transparent 45%
        );
}

.contact-section h2 {
    margin-bottom: 15px;
}

.contact-section > p:not(.section-label) {
    color: #94a3b8;

    margin-bottom: 25px;
}


/* =========================
   FOOTER
========================= */

footer {
    display: flex;

    flex-wrap: wrap;

    justify-content: space-between;

    gap: 40px;

    padding: 60px 7%;

    background: #050810;

    border-top: 1px solid #1e293b;
}

footer > div {
    flex: 1 1 180px;
}

.footer-brand h3 {
    color: #38bdf8;

    font-size: 1.3rem;

    margin-bottom: 8px;
}

.footer-brand p,
.footer-contact p,
.student-details p {
    color: #64748b;

    font-size: 0.75rem;

    margin-bottom: 5px;
}

footer h4 {
    font-size: 0.8rem;

    margin-bottom: 15px;

    color: #e2e8f0;
}

.footer-links {
    display: flex;

    flex-direction: column;

    align-items: flex-start;
}

.footer-links a {
    color: #64748b;

    text-decoration: none;

    font-size: 0.75rem;

    margin-bottom: 5px;
}

.footer-links a:hover {
    color: #38bdf8;
}

.copyright {
    text-align: center;

    padding: 20px;

    background: #050810;

    border-top: 1px solid #111827;

    color: #475569;

    font-size: 0.65rem;
}


/* =========================
   RESPONSIVE DESIGN
========================= */

@media (max-width: 900px) {

    header {
        flex-wrap: wrap;

        gap: 15px;
    }

    .hero {
        flex-direction: column;

        text-align: center;
    }

    .hero-content {
        display: flex;

        flex-direction: column;

        align-items: center;
    }

    .hero-card {
        width: 300px;

        height: 300px;
    }

    .section-heading {
        flex-direction: column;

        align-items: flex-start;
    }

    .about-section {
        flex-direction: column;

        align-items: flex-start;
    }

    .about-statistics {
        width: 100%;
    }

    .about-statistics div {
        flex: 1;
    }
}


@media (max-width: 600px) {

    header {
        flex-direction: column;

        padding: 18px 5%;
    }

    nav {
        gap: 12px;

        flex-wrap: wrap;

        justify-content: center;
    }

    nav a {
        font-size: 0.7rem;
    }

    .nav-button {
        display: none;
    }

    .hero {
        padding: 70px 6%;
    }

    .hero h1 {
        font-size: 3.5rem;

        letter-spacing: -2px;
    }

    .hero h2 {
        font-size: 1rem;
    }

    .hero-description {
        font-size: 0.85rem;
    }

    .hero-card {
        width: 250px;

        height: 250px;
    }

    .hero-circle {
        width: 140px;

        height: 140px;

        font-size: 1.5rem;
    }

    .products-section,
    .services-section,
    .about-section,
    .contact-section {
        padding: 70px 6%;
    }

    .section-heading h2,
    .services-section h2,
    .about-section h2,
    .contact-section h2 {
        font-size: 2rem;
    }

    .product-container {
        flex-direction: column;
    }

    .product-card {
        width: 100%;
    }

    .about-statistics {
        flex-direction: column;
    }

    footer {
        flex-direction: column;

        padding: 45px 6%;
    }
}
## OUTPUT
<img width="1305" height="1050" alt="638625620-fdc90b9d-fb72-4132-9c41-9c02814145f6" src="https://github.com/user-attachments/assets/04c7c200-2f01-4774-9ecd-a5a839d9dc35" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
