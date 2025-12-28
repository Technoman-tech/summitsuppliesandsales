<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Summit Supplies & Sales</title>

    <style>
        :root {
            --primary-blue: #1f3f75;
            --secondary-blue: #2f5fa8;
            --accent-gold: #f2b705;
            --light-bg: #f5f7fb;
            --dark-text: #1f2933;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: var(--light-bg);
            color: var(--dark-text);
        }

        header {
            background: linear-gradient(135deg, var(--primary-blue), var(--secondary-blue));
            color: white;
            padding: 25px;
            text-align: center;
        }

        nav {
            background: var(--primary-blue);
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: var(--accent-gold);
        }

        .hero {
            background:
                linear-gradient(
                    120deg,
                    rgba(31,63,117,0.85) 0%,
                    rgba(31,63,117,0.85) 45%,
                    rgba(31,63,117,0.2) 45%,
                    rgba(31,63,117,0.2) 100%
                ),
                url("SummitHomepageBanner.png") center/cover no-repeat;
            padding: 80px 20px;
            color: white;
        }

        .hero h1 {
            font-size: 2.8rem;
            max-width: 500px;
        }

        .hero a {
            display: inline-block;
            margin-top: 25px;
            padding: 14px 28px;
            background: var(--accent-gold);
            color: #1a1a1a;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero a:hover {
            background: #e0a800;
        }

        .section {
            padding: 50px 20px;
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
            border-radius: 12px;
            background: white;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            transition: transform 0.25s;
        }

        .category-card:hover {
            transform: translateY(-6px);
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
            width: 260px;
            height: 160px;
            object-fit: cover;
            border-radius: 12px;
            transition: transform 0.25s;
        }

        .gallery img:hover {
            transform: scale(1.06);
        }

        footer {
            background: var(--primary-blue);
            color: white;
            padding: 25px;
            text-align: center;
            margin-top: 40px;
        }

        @media (max-width: 768px) {
            .hero {
                text-align: center;
            }

            .categories {
                flex-direction: column;
                align-items: center;
            }

            .category-card {
                width: 85%;
            }

            .gallery img {
                width: 85%;
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
    <h1>Gear Your Adventure</h1>
    <a href="https://summit-supplies-sales.myshopify.com" target="_blank">Shop Now</a>
</div>

<div class="section" id="products">
    <h2>Product Categories</h2>
    <div class="categories">
        <div class="category-card">
            <img src="monocular.jpg" alt="Camping monocular">
            Camping Gear
        </div>
        <div class="category-card">
            <img src="parka.jpg" alt="Outdoor parka">
            Outdoor Apparel
        </div>
        <div class="category-card">
            <img src="iphone16.jpg" alt="Smartphone">
            Cell Phones
        </div>
        <div class="category-card">
            <img src="gpswatch.jpg" alt="GPS watch">
            Electronics
        </div>
        <div class="category-card">
            <img src="Boots.jpg" alt="Outdoor boots">
            Footwear
        </div>
        <div class="category-card">
            <img src="hat.jpg" alt="Winter hat">
            Seasonal Deals
        </div>
    </div>
</div>

<div class="section" id="gallery">
    <h2>Photo Gallery</h2>
    <div class="gallery">
        <img src="Boots.jpg" alt="Boots">
        <img src="android.jpg" alt="Android phone">
        <img src="gpswatch.jpg" alt="GPS watch">
        <img src="hat.jpg" alt="Hat">
        <img src="iphone16.jpg" alt="iPhone">
        <img src="jacket.jpg" alt="Jacket">
        <img src="monocular.jpg" alt="Monocular">
        <img src="socks.jpg" alt="Socks">
        <img src="survivalkit.jpg" alt="Survival kit">
        <img src="campinggear.jpg" alt="Camping gear">
        <img src="campinggear2.jpg" alt="Camping gear set">
        <img src="campinggear3.jpg" alt="Camping equipment">
    </div>
</div>

<footer>
    <p>Summit Supplies & Sales © 2025</p>
</footer>

</body>
</html>
