<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beijing Brief - Latest News from China's Capital</title>
    <meta name="description" content="Beijing Brief is your go-to source for the latest news, insights, and updates from China’s capital. Stay informed on politics, business, culture, and daily life.">
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <h1>Beijing Brief</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="#politics">Politics</a></li>
                <li><a href="#business">Business</a></li>
                <li><a href="#culture">Culture</a></li>
                <li><a href="#dailylife">Daily Life</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Your Source for Beijing's Latest News</h2>
        <p>Stay informed on politics, business, culture, and daily life in China's capital.</p>
        <a href="#latest-news" class="btn">Read Latest News</a>
    </section>

    <!-- News Section -->
    <section id="latest-news" class="news-section">
        <h2>Latest News</h2>
        <div class="news-grid">
            <article class="news-card">
                <img src="https://via.placeholder.com/300x200" alt="News Image">
                <h3>Political Summit in Beijing</h3>
                <p>Leaders discuss key policies for 2025 at annual summit...</p>
                <a href="#" class="read-more">Read More</a>
            </article>
            <article class="news-card">
                <img src="https://via.placeholder.com/300x200" alt="News Image">
                <h3>Tech Boom in Beijing</h3>
                <p>New startups drive innovation in China's capital...</p>
                <a href="#" class="read-more">Read More</a>
            </article>
            <article class="news-card">
                <img src="https://via.placeholder.com/300x200" alt="News Image">
                <h3>Cultural Festival Highlights</h3>
                <p>Beijing's annual cultural festival draws thousands...</p>
                <a href="#" class="read-more">Read More</a>
            </article>
        </div>
    </section>

    <!-- Categories Section -->
    <section id="categories" class="categories">
        <h2>Explore Categories</h2>
        <div class="category-grid">
            <div class="category-card" id="politics">
                <h3>Politics</h3>
                <p>Insights into Beijing's political landscape.</p>
                <a href="#" class="btn">Explore</a>
            </div>
            <div class="category-card" id="business">
                <h3>Business</h3>
                <p>Updates on Beijing's economic and startup scene.</p>
                <a href="#" class="btn">Explore</a>
            </div>
            <div class="category-card" id="culture">
                <h3>Culture</h3>
                <p>Discover Beijing's rich cultural heritage.</p>
                <a href="#" class="btn">Explore</a>
            </div>
            <div class="category-card" id="dailylife">
                <h3>Daily Life</h3>
                <p>Stories from the streets of Beijing.</p>
                <a href="#" class="btn">Explore</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>Beijing Brief</h3>
                <p>Your go-to source for news from China's capital.</p>
            </div>
            <div class="footer-section">
                <h3>Follow Us</h3>
                <div class="social-links">
                    <a href="#">Twitter</a>
                    <a href="#">Facebook</a>
                    <a href="#">Instagram</a>
                </div>
            </div>
            <div class="footer-section">
                <h3>Subscribe</h3>
                <form id="newsletter-form">
                    <input type="email" placeholder="Enter your email" required>
                    <button type="submit" class="btn">Subscribe</button>
                </form>
            </div>
        </div>
        <p>&copy; 2025 Beijing Brief. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Beijing Brief</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Beijing Brief</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="#politics">Politics</a></li>
                <li><a href="#business">Business</a></li>
                <li><a href="#culture">Culture</a></li>
                <li><a href="#dailylife">Daily Life</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="about">
        <h2>About Beijing Brief</h2>
        <p>Beijing Brief is your trusted source for the latest news, insights, and updates from China’s capital. We cover politics, business, culture, and daily life, providing in-depth reporting and analysis to keep you informed.</p>
        <p>Our mission is to deliver accurate, timely, and engaging content that reflects the dynamic spirit of Beijing.</p>
    </section>

    <footer>
        <p>&copy; 2025 Beijing Brief. All rights reserved.</p>
    </footer>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - Beijing Brief</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Beijing Brief</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="#politics">Politics</a></li>
                <li><a href="#business">Business</a></li>
                <li><a href="#culture">Culture</a></li>
                <li><a href="#dailylife">Daily Life</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <label for="name">Name</label>
            <input type="text" id="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" required>
            <label for="message">Message</label>
            <textarea id="message" required></textarea>
            <button type="submit" class="btn">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Beijing Brief. All rights reserved.</p>
    </footer>
</body>
</html>* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

header {
    background: #1a1a1a;
    color: white;
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo h1 {
    font-size: 1.8rem;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 2rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: #f4a261;
}

.hero {
    background: url('https://via.placeholder.com/1500x400') no-repeat center center/cover;
    text-align: center;
    padding: 4rem 2rem;
    color: white;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.btn {
    background: #f4a261;
    color: white;
    padding: 0.8rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.btn:hover {
    background: #e76f51;
}

.news-section, .categories, .about, .contact {
    padding: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.news-section h2, .categories h2, .about h2, .contact h2 {
    text-align: center;
    margin-bottom: 2rem;
}

.news-grid, .category-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.news-card, .category-card {
    background: #f9f9f9;
    padding: 1rem;
    border-radius: 5px;
    text-align: center;
}

.news-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 5px;
}

.read-more {
    color: #f4a261;
    text-decoration: none;
    font-weight: bold;
}

.read-more:hover {
    color: #e76f51;
}

footer {
    background: #1a1a1a;
    color: white;
    padding: 2rem;
    text-align: center;
}

.footer-content {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-bottom: 1rem;
}

.footer-section {
    margin: 1rem;
}

.social-links a {
    color: white;
    margin: 0 0.5rem;
    text-decoration: none;
}

.social-links a:hover {
    color: #f4a261;
}

form input, form textarea {
    width: 100%;
    padding: 0.8rem;
    margin: 0.5rem 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    width: 100%;
}

@media (max-width: 768px) {
    header {
        flex-direction: column;
    }

    nav ul {
        flex-direction: column;
        text-align: center;
    }

    nav ul li {
        margin: 0.5rem 0;
    }

    .hero h2 {
        font-size: 1.8rem;
    }

    .hero p {
        font-size: 1rem;
    }
}document.addEventListener('DOMContentLoaded', () => {
    // Newsletter Form Submission
    const newsletterForm = document.getElementById('newsletter-form');
    if (newsletterForm) {
        newsletterForm.addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Thank you for subscribing to Beijing Brief!');
            newsletterForm.reset();
        });
    }

    // Contact Form Submission
    const contactForm = document.getElementById('contact-form');
    if (contactForm) {
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Your message has been sent!');
            contactForm.reset();
        });
    }
});
