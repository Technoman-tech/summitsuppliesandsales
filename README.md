
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Summit Supplies & Sales</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #ffffff;
        color: #002f6c;
    }

    /* Theme blue bars */
    .bar {
        width: 100%;
        height: 55px;
        background-color: #1A3A7A;
    }

    .hero {
        position: relative;
        width: 100%;
        height: calc(100vh - 110px); /* subtract bars */
        overflow: hidden;
        display: flex;
        align-items: center;
        padding-left: 4%;
    }

    .hero img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        position: absolute;
        top: 0;
        left: 0;
        z-index: -3;
    }

    /* Blue left overlay background */
    .overlay-left {
        position: absolute;
        left: 0;
        width: 50%;
        height: 100%;
        background: rgba(10, 43, 105, 0.6);
        z-index: -2;
    }

    /* Diagonal overlay */
    .overlay-diagonal {
        position: absolute;
        right: 0;
        top: 0;
        width: 70%;
        height: 100%;
        background: rgba(255, 255, 255, 0.22);
        clip-path: polygon(35% 0, 100% 0, 100% 100%, 0 100%);
        z-index: -1;
    }

    /* White rounded boxed area */
    .main-box {
        background: rgba(255, 255, 255, 0.92);
        padding: 40px 55px;
        border-radius: 22px;
        border: 4px solid #1F4B9C;
        max-width: 450px;
        backdrop-filter: blur(2px);
    }

    .main-title {
        font-size: 38px;
        font-weight: bold;
        color: #123875;
        margin-bottom: 8px;
    }

    .subtitle {
        font-size: 18px;
        color: #123875;
        opacity: 0.9;
        letter-spacing: 1px;
    }

</style>
</head>

<body>

<div class="bar"></div>

<section class="hero">
    <img src="SummitHomepageBanner.jpg" alt="Outdoor Adventure Theme">

    <div class="overlay-left"></div>
    <div class="overlay-diagonal"></div>

    <div class="main-box">
        <div class="main-title">Summit Supplies & Sales</div>
        <div class="subtitle">GEAR YOUR ADVENTURE</div>
    </div>
</section>

<div class="bar"></div>

</body>
</html>
