<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAYRAN | Exclusive Jewelry</title>
    <style>
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            margin: 0; 
            background-color: #f4f4f4;
            color: #333;
        }

        /* بخش هدر با پس‌زمینه تصویر چوب */
        header { 
            background: linear-gradient(rgba(0,0,0,0.2), rgba(0,0,0,0.2)), 
                        url('5.jfif'); /* اینجا نام عکسی که می‌خواهی در پس‌زمینه باشد را بنویس */
            background-size: cover;
            background-position: center;
            height: 450px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        h1 { font-size: 4rem; letter-spacing: 15px; margin: 0; font-weight: 300; text-shadow: 2px 2px 10px rgba(0,0,0,0.3); }
        .tagline { font-size: 1.2rem; letter-spacing: 4px; margin-top: 20px; text-transform: uppercase; }

        .container { max-width: 1200px; margin: -50px auto 50px; padding: 0 20px; }

        /* استایل کارت‌ها شبیه به عکس ارسالی شما */
        .product-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
            gap: 20px; 
        }

        .product-card { 
            background: rgba(255, 255, 255, 0.9); 
            padding: 40px 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            backdrop-filter: blur(5px);
            border: 1px solid rgba(255,255,255,0.3);
        }

        .product-card h3 { 
            text-transform: uppercase; 
            letter-spacing: 2px; 
            font-size: 1.3rem;
            margin-bottom: 20px;
        }

        .product-card p { 
            font-size: 1rem; 
            color: #555; 
            line-height: 1.6;
            margin-bottom: 15px;
        }

        /* بخش تماس */
        .contact-section { 
            background: white; 
            padding: 40px; 
            margin-top: 50px; 
            border-radius: 8px;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
        }

        .contact-info { flex: 1; min-width: 300px; }
        .map-box { flex: 1; min-width: 300px; height: 250px; background: #eee; border-radius: 8px; overflow: hidden; }

        .lang-switch { margin-top: 20px; font-size: 0.9rem; }
    </style>
</head>
<body>

<header>
    <h1>JAYRAN</h1>
    <div class="tagline">HANDCRAFTED NATURE-INSPIRED JEWELRY</div>
</header>

<div class="container">
    <div class="product-grid">
        
        <div class="product-card">
            <h3>Leaf Collection A</h3>
            <p>Handcrafted ceramic earrings with intricate leaf textures. Finished with turquoise accents.</p>
        </div>

        <div class="product-card">
            <h3>Leaf Collection B</h3>
            <p>Nature-inspired design featuring authentic turquoise stones and rustic wood elements.</p>
        </div>

        <div class="product-card">
            <h3>Premium Packaging</h3>
            <p>Every piece comes in our signature JAYRAN luxury gift box, ready for special occasions.</p>
        </div>

    </div>

    <div class="contact-section">
        <div class="contact-info">
            <h2>Contact Us</h2>
            <p><strong>Location:</strong> Bad Windsheim, Germany</p>
            <p><strong>Phone:</strong> +49 1XX XXXXXXXX</p>
            <div class="lang-switch">🇩🇪 German / 🇬🇧 English</div>
        </div>
        <div class="map-box">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2586.2!2d10.3!3d49.5!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a123!2sBad%20Windsheim!5e0!3m2!1sen!2sde!4v1" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </div>
</div>

<footer style="text-align
