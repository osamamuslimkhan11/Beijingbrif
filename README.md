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
