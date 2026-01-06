<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Summit Supplies & Sales</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #ffffff;
            color: #333;
        }

        header {
            background: #1f4db8;
            color: #fff;
            padding: 30px 20px;
            text-align: center;
        }

        nav {
            background: #003087;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            background: linear-gradient(135deg, #1f4db8, #79aaff);
            padding: 60px 20px;
            text-align: center;
            color: white;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .hero a {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background: #003087;
            color: #fff;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }

        .section {
            padding: 40px 20px;
            text-align: center;
        }

        .categories {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .category-card {
            width: 200px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            background: #f7f9ff;
            transition: transform 0.2s;
        }

        .category-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .category-card img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 10px;
        }

        .gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .gallery img {
            width: 250px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.2s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        .policy-section {
            padding: 40px 20px;
            max-width: 800px;
            margin: auto;
            text-align: left;
        }

        .policy-section h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .about-us {
            padding: 20px;
            text-align: center;
            background: #f7f7f7;
            font-size: 0.9rem;
        }

        footer {
            background: #003087;
            color: white;
            padding: 20px;
            text-align: center;
            margin-top: 40px;
        }

        footer a {
            color: #fff;
            margin: 0 10px;
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            .categories {
                flex-direction: column;
                align-items: center;
            }

            .category-card {
                width: 80%;
            }

            .gallery img {
                width: 80%;
                height: auto;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Summit Supplies & Sales</h1>
    <p>Quality Products, Smart Prices</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="https://summit-supplies-sales.myshopify.com" target="_blank">Shop Now</a>
    <a href="#gallery">Photo Gallery</a>
</nav>

<div class="hero" id="home">
    <h1>Buy Now on Shopify!</h1>
    <a href="https://summit-supplies-sales.myshopify.com" target="_blank">Shop Now</a>
</div>

<div class="section" id="products">
    <h2>Product Categories</h2>
    <div class="categories">
        <div class="category-card"><img src="campinggear3.jpg" alt="Camping Gear">Camping Gear</div>
        <div class="category-card"><img src="parka.jpg" alt="Parka">Outdoor Apparel</div>
        <div class="category-card"><img src="iphone16.jpg" alt="Electronics">Electronics</div>
        <div class="category-card"><img src="hat.jpg" alt="Seasonal Deals">Seasonal Deals</div>
    </div>
</div>

<div class="section" id="gallery">
    <h2>Photo Gallery</h2>
    <div class="gallery">
        <img src="Boots.jpg" alt="Boots">
        <img src="android.jpg" alt="Android">
        <img src="gpswatch.jpg" alt="GPS Watch">
        <img src="hat.jpg" alt="Hat">
        <img src="iphone16.jpg" alt="iPhone">
        <img src="jacket.jpg" alt="Jacket">
        <img src="monocular.jpg" alt="Monocular">
        <img src="socks.jpg" alt="Socks">
        <img src="campinggear.jpg" alt="Camping Gear">
        <img src="campinggear2.jpg" alt="Camping Gear">
        <img src="campinggear3.jpg" alt="Camping Gear">
    </div>
</div>

<div class="policy-section" id="terms">
    <h2>Terms & Conditions</h2>
    <p>Welcome to Summit Supplies & Sales. By accessing our website, you agree to comply with our terms.</p>
</div>

<div class="policy-section" id="privacy">
    <h2>Privacy Policy</h2>
    <p>We respect your privacy. Personal information is used solely for order processing and customer service.</p>
</div>

<div class="policy-section" id="shipping">
    <h2>Shipping & Returns</h2>
    <p>Orders are processed within 2–5 business days. Returns accepted within 14 days.</p>
</div>

<div class="policy-section" id="refunds">
    <h2>Refund Policy</h2>
    <p>Refunds issued within 7 business days of receiving returned items.</p>
</div>

<div class="about-us">
    <p>Summit Supplies & Sales is owned and operated by Phillip Nasogaluak, providing quality products at smart prices.</p>
</div>

<footer>
    <p>Summit Supplies & Sales © 2025</p>
    <p>
        <a href="#terms">Terms</a> |
        <a href="#privacy">Privacy</a> |
        <a href="#shipping">Shipping</a> |
        <a href="#refunds">Refunds</a>
    </p>
</footer>

</body>
</html>




