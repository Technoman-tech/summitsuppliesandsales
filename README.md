
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
    color: #fff;
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
    text-align: left;
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
