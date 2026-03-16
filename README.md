<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Professional Media & Product Gallery</title>

<style>
/* General Body */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
    color: #333;
    scroll-behavior: smooth;
}

/* Sticky Navigation */
nav {
    position: sticky;
    top: 0;
    background-color: #2c3e50;
    display: flex;
    justify-content: center;
    padding: 12px 0;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    transition: color 0.3s;
}

nav a:hover {
    color: #f39c12;
}

/* Header */
header {
    background-color: #34495e;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

/* Sections */
section {
    padding: 40px 20px;
    max-width: 1200px;
    margin: 20px auto;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 6px 12px rgba(0,0,0,0.1);
}

h2 {
    color: #2c3e50;
    margin-bottom: 20px;
    text-align: center;
}

p {
    line-height: 1.6;
    margin-bottom: 15px;
}

ul, ol {
    margin-left: 40px;
    margin-bottom: 20px;
}

ul li, ol li {
    margin-bottom: 10px;
}

ol li {
    font-weight: bold;
}

/* Gallery styling */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 20px 0;
}

.gallery iframe, .gallery img {
    width: 100%;
    height: 200px;
    border-radius: 10px;
    box-shadow: 0 6px 12px rgba(0,0,0,0.2);
    transition: transform 0.3s, box-shadow 0.3s;
}

.gallery iframe:hover, .gallery img:hover {
    transform: scale(1.05);
    box-shadow: 0 8px 16px rgba(0,0,0,0.3);
}

.caption {
    margin-top: 8px;
    font-style: italic;
    font-size: 0.9em;
    color: #555;
}

/* Price table */
table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

table, th, td {
    border: 1px solid #ddd;
}

th, td {
    padding: 12px;
    text-align: left;
}

th {
    background-color: #2c3e50;
    color: white;
}

tr:hover {
    background-color: #f1f1f1;
}

/* Responsive for small screens */
@media (max-width: 600px){
    .gallery iframe, .gallery img {
        height: 180px;
    }
}
</style>
</head>

<body>

<!-- Navigation -->
<nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#prices">Prices</a>
    <a href="#videos">Videos</a>
    <a href="#images">Images</a>
</nav>

<header>
<h1>Professional Media & Product Gallery</h1>
</header>

<!-- About Section -->
<section id="about">
<h2>About Our Products</h2>
<p>Welcome to our product catalog! We provide high-quality items that cater to all your needs. Our goal is to offer excellent products at affordable prices.</p>
<p>Each product is carefully selected to ensure durability and customer satisfaction. We update our stock regularly and provide detailed descriptions to help you make the best choice.</p>
<p>Ordering is simple: select the items you want, check the prices, and place your order online. Our system will guide you through every step.</p>
<p>We also provide multiple payment options for your convenience, including online payments, bank transfers, and cash on delivery. Your safety and comfort are our priority.</p>
<p>If you have any questions or need assistance, our customer support team is always ready to help. Contact us via phone, email, or live chat for instant support.</p>
</section>

<!-- Products Section -->
<section id="products">
<h2>Popular Products</h2>
<ol>
    <li>Wireless Headphones</li>
    <li>Smart Watches</li>
    <li>Bluetooth Speakers</li>
    <li>Laptop Accessories</li>
    <li>Mobile Phone Cases</li>
</ol>

<h2>Product Features</h2>
<ul>
    <li>High-quality materials for durability</li>
    <li>Modern and stylish design</li>
    <li>Affordable pricing and discounts available</li>
    <li>Easy to use and maintain</li>
    <li>Eco-friendly packaging</li>
</ul>
</section>

<!-- Prices Section -->
<section id="prices">
<h2>Price List</h2>
<table>
    <tr>
        <th>Product</th>
        <th>Price (USD)</th>
    </tr>
    <tr>
        <td>Wireless Headphones</td>
        <td>$50</td>
    </tr>
    <tr>
        <td>Smart Watches</td>
        <td>$80</td>
    </tr>
    <tr>
        <td>Bluetooth Speakers</td>
        <td>$40</td>
    </tr>
    <tr>
        <td>Laptop Accessories</td>
        <td>$30</td>
    </tr>
    <tr>
        <td>Mobile Phone Cases</td>
        <td>$15</td>
    </tr>
</table>
<div class="caption">Prices are subject to change. Check our website for latest updates.</div>
</section>

<!-- Videos Section -->
<section id="videos">
<h2>Video Gallery</h2>
<div class="gallery">
    <div>
        <iframe src="https://www.youtube.com/embed/xvt3pq2_bdY" allowfullscreen></iframe>
        <div class="caption">Video 1</div>
    </div>
    <div>
        <iframe src="https://www.youtube.com/embed/x_it6nqtHtk" allowfullscreen></iframe>
        <div class="caption">Video 2</div>
    </div>
    <div>
        <iframe src="https://www.youtube.com/embed/1XzKAdEZyxc" allowfullscreen></iframe>
        <div class="caption">Video 3</div>
    </div>
    <div>
        <iframe src="https://www.youtube.com/embed/LWdd1SHDgeQ" allowfullscreen></iframe>
        <div class="caption">Video 4</div>
    </div>
    <div>
        <iframe src="https://www.youtube.com/embed/hDXjSOq_iUM" allowfullscreen></iframe>
        <div class="caption">Video 5</div>
    </div>
</div>
</section>

<!-- Images Section -->
<section id="images">
<h2>Image Gallery</h2>
<div class="gallery">
    <div>
       <img src="image/1.jpg">
        <img src="image/2.jpg">
        <img src="image/3.jpg">
        <img src="image/4.jpg">
        <img src="image/5.jpg">
</div>
</section>

</body>
</html>
