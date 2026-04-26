<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAYRAN | Exclusive Jewelry</title>
    <style>
        :root {
            --turquoise: #40E0D0; /* فیروزه‌ای اصلی */
            --dark-cyan: #008B8B;
        }

        body { 
            font-family: 'Helvetica Neue', sans-serif; 
            margin: 0; 
            display: flex; /* برای ایجاد منوی سمت چپ */
            background-color: var(--turquoise); /* پس‌زمینه فیروزه‌ای کل سایت */
            color: #333;
        }

        /* منوی عمودی سمت چپ */
        nav {
            width: 250px;
            height: 100vh;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            position: fixed;
            display: flex;
            flex-direction: column;
            padding: 40px 20px;
            border-right: 1px solid rgba(255,255,255,0.2);
        }

        nav h2 { color: white; letter-spacing: 5px; text-transform: uppercase; margin-bottom: 50px; }
        nav a { color: white; text-decoration: none; margin: 15px 0; font-size: 1.1rem; opacity: 0.8; transition: 0.3s; }
        nav a:hover { opacity: 1; padding-left: 10px; }

        /* محتوای اصلی سایت */
        main {
            margin-left: 290px; /* فاصله از منوی سمت چپ */
            padding: 50px;
            width: 100%;
        }

        header { text-align: center; color: white; margin-bottom: 60px; }
        header h1 { font-size: 4rem; letter-spacing: 15px; margin: 0; font-weight: 200; }

        /* کارت‌های محصول */
        .product-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
            gap: 30px; 
        }

        .product-card { 
            background: white; 
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            transition: 0.3s;
        }
        .product-card:hover { transform: translateY(-10px); }

        .card-img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

        .product-info { padding: 25px; text-align: center; }
        .product-info h3 { color: var(--dark-cyan); margin-bottom: 10px; text-transform: uppercase; }
        .product-info p { font-size: 0.9rem; color: #666; line-height: 1.6; }

        /* بخش تماس */
        .contact-box {
            background: white;
            margin-top: 60px;
            padding: 40px;
            border-radius: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .map-frame { width: 45%; height: 250px; border-radius: 10px; overflow: hidden; border: 1px solid #eee; }
    </style>
</head>
<body>

<nav>
    <h2>Jayran</h2>
    <a href="#">Collection</a>
    <a href="#">About Design</a>
    <a href="#">Contact</a>
    <a href="#" style="margin-top: auto;">DE | EN</a>
</nav>

<main>
    <header>
        <h1>JAYRAN</h1>
        <p>HANDCRAFTED NATURE-INSPIRED JEWELRY</p>
    </header>

    <div class="product-grid">
        <div class="product-card">
            <img src="4.jfif" class="card-img" alt="Jewelry 1">
            <div class="product-info">
                <h3>Leaf Collection A</h3>
                <p>Handcrafted ceramic earrings with intricate leaf textures.</p>
            </div>
        </div>

        <div class="product-card">
            <img src="5.jfif" class="card-img" alt="Jewelry 2">
            <div class="product-info">
                <h3>Leaf Collection B</h3>
                <p>Nature-inspired design with authentic turquoise stones.</p>
            </div>
        </div>

        <div class="product-card">
            <img src="94e5e2a1-a59f-4a53-bba8-21978908a5ef.jfif" class="card-img" alt="Jewelry 3">
            <div class="product-info">
                <h3>Premium Gift Box</h3>
                <p>Luxury packaging for exclusive items.</p>
            </div>
        </div>
    </div>

    <div class="contact-box">
        <div style="width: 50%;">
            <h2>Order & Inquiry</h2>
            <p><strong>WhatsApp:</strong> +49 1XX XXXXXXXX</p>
            <p><strong>Location:</strong> Bad Windsheim, Germany</p>
        </div>
        <div class="map-frame">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2595.6!2d10.4!3d49.5!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a123!2sBad%20Windsheim!5e0!3m2!1sen!2sde!4v123456789" width="100%" height="100%" style="border:0;" allowfullscreen=""></iframe>
        </div>
    </div>
</main>

</body>
</html>
