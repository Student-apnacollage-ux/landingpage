#CSS
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
}

header h1 {
    margin: 0;
    display: inline-block;
}

nav ul {
    list-style: none;
    float: right;
}

nav ul li {
    display: inline;
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

#hero {
    background: #f4f4f4;
    padding: 50px 0;
    text-align: center;
}

#hero h2 {
    margin-bottom: 20px;
}

#hero .btn {
    background: #333;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

#features {
    padding: 50px 0;
    background: #e2e2e2;
}

.features-grid {
    display: flex;
    justify-content: space-between;
}

.feature {
    width: 30%;
    text-align: center;
}

#testimonials {
    padding: 50px 0;
    background: #f4f4f4;
    text-align: center;
}

#cta {
    padding: 50px 0;
    text-align: center;
    background: #333;
    color: #fff;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

footer ul {
    list-style: none;
    padding: 0;
}

footer ul li {
    display: inline;
    margin-left: 10px;
}

footer ul li a {
    color: #fff;
    text-decoration: none;
}

#HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="CNstyle2.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Company Name</h1>
            <nav>
                <ul>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <div class="container">
            <h2>Main Headline</h2>
            <p>Your subheadline goes here. Make it compelling!</p>
            <a href="#cta" class="btn">Call to Action</a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features">
        <div class="container">
            <h2>Features</h2>
            <div class="features-grid">
                <div class="feature">
                    <h3>Feature 1</h3>
                    <p>Description of the feature.</p>
                </div>
                <div class="feature">
                    <h3>Feature 2</h3>
                    <p>Description of the feature.</p>
                </div>
                <div class="feature">
                    <h3>Feature 3</h3>
                    <p>Description of the feature.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <div class="container">
            <h2>What Our Customers Say</h2>
            <blockquote>"Great product! It changed my life."</blockquote>
            <cite>- Happy Customer</cite>
        </div>
    </section>

    <!-- Call to Action Section -->
    <section id="cta">
        <div class="container">
            <h2>Ready to Get Started?</h2>
            <a href="#contact" class="btn">Contact Us</a>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Company Name. All rights reserved.</p>
            <ul>
                <li><a href="#privacy">Privacy Policy</a></li>
                <li><a href="#terms">Terms of Service</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
