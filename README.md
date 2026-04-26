<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAYRAN | Collection</title>
    <style>
        :root {
            --turquoise: #40E0D0;
            --dark-cyan: #008B8B;
        }

        body { 
            font-family: 'Helvetica Neue', Arial, sans-serif; 
            margin: 0; 
            background-color: var(--turquoise); 
            color: #333;
        }

        header { 
            text-align: center; 
            padding: 40px 0; 
            color: white; 
        }
        header h1 { font-size: 3.5rem; letter-spacing: 15px; margin: 0; font-weight: 200; }
        header p { letter-spacing: 3px; font-size: 0.9rem; opacity: 0.9; }

        .container { 
            max-width: 900px; 
            margin: 0 auto 50px; 
            padding: 0 20px; 
        }

        /* استایل کارت‌های عریض مطابق عکس شما */
        .product-card { 
            background: white; 
            border-radius: 20px;
            margin-bottom: 30px;
            display: flex; /* برای قرارگیری عکس و متن کنار هم */
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            min-height: 250px;
        }

        .product-info { 
            flex: 1; 
            padding: 40px; 
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        
        .product-info h3 { 
            color: var(--dark-cyan); 
            margin: 0 0 15px 0; 
            font-size: 1.5rem;
            text-transform: uppercase;
        }

        .product-info p { color: #666; line-height: 1.6; margin: 0; }

        .product-image { 
            flex: 1.2; 
            background-size: cover;
            background-position: center;
        }

        /* بخش ورق زدن (Pagination) پایین صفحه */
        .pagination {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 40px;
            gap: 10px;
        }

        .page-item {
            width: 35px;
            height: 35px;
            background: white;
            border-radius: 5px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-decoration: none;
            color: var(--dark-cyan);
            font-weight: bold;
            transition: 0.3s;
        }

        .page-item.active {
            background: var(--dark-cyan);
            color: white;
        }

        .page-item:hover:not(.active) {
            background: #eee;
        }

    </style>
</head>
<body>

<header>
    <h1>JAYRAN</h1>
    <p>HANDCRAFTED NATURE-INSPIRED JEWELRY</p>
</header>

<div class="container">
    
    <div class="product-card">
        <div class="product-info">
            <h3>Leaf Collection A</h3>
            <p>Handcrafted ceramic earrings with intricate leaf textures. Finished with turquoise accents.</p>
        </div>
        <div class="product-image" style="background-image: url('4.jfif');"></div>
    </div>

    <div class="product-card">
        <div class="product-info">
            <h3>Leaf Collection B</h3>
            <p>Nature-inspired design featuring authentic turquoise stones and rustic wood elements.</p>
        </div>
        <div class="product-image" style="background-image: url('5.jfif');"></div>
    </div>

    <div class="product-card">
        <div class="product-info">
            <h3>Premium Box</h3>
            <p>Our signature JAYRAN luxury gift box, ready for special occasions.</p>
        </div>
        <div class="product-image" style="background-image: url('94e5e2a1-a59f-4a53-bba8-21978908a5ef.jfif');"></div>
    </div>

    <div class="pagination">
        <a href="#" class="page-item"><</a>
        <a href="#" class="page-item active">1</a>
        <a href="#" class="page-item">2</a>
        <a href="#" class="page-item">3</a>
        <a href="#" class="page-item">></a>
    </div>

</div>

<footer style="text-align: center; padding: 40px; color: white; opacity: 0.7;">
    © 2026 JAYRAN DESIGN
</footer>

</body>
</html>
