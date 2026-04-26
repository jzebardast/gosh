<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAYRAN | Exclusive Jewelry Design</title>
    <style>
        :root {
            --turquoise: #40E0D0;
            --dark-turquoise: #008B8B;
        }
        body { font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; margin: 0; background-color: #f8fbfb; color: #222; }
        
        header { background: var(--turquoise); padding: 60px 20px; text-align: center; color: white; }
        h1 { margin: 0; font-size: 3.2rem; letter-spacing: 10px; text-transform: uppercase; font-weight: 300; }
        .tagline { font-size: 1.1rem; margin-top: 15px; letter-spacing: 2px; opacity: 0.9; }

        .container { max-width: 1200px; margin: 50px auto; padding: 0 25px; }

        /* Product Gallery */
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 40px; }
        .product-card { background: white; border-radius: 4px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.05); transition: 0.4s; }
        .product-card:hover { transform: translateY(-10px); box-shadow: 0 12px 30px rgba(0,0,0,0.1); }
        .product-card img { width: 100%; height: 350px; object-fit: cover; cursor: zoom-in; }
        
        .product-info { padding: 25px; text-align: center; }
        .product-title { font-size: 1.2rem; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 10px; }
        .price { font-size: 1.4rem; color: var(--dark-turquoise); font-weight: bold; margin: 15px 0; }
        .description { font-size: 0.95rem; color: #777; line-height: 1.5; margin-bottom: 20px; }

        /* Contact Section */
        .contact-section { background: #fff; padding: 60px; margin-top: 80px; text-align: center; border-radius: 8px; }
        .contact-title { font-size: 2rem; margin-bottom: 30px; color: var(--dark-turquoise); }
        .contact-details { font-size: 1.1rem; margin-bottom: 40px; line-height: 2; }
        
        .btn { 
            background: var(--dark-turquoise); 
            color: white; 
            padding: 18px 40px; 
            text-decoration: none; 
            border-radius: 2px; 
            font-weight: bold; 
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: 0.3s;
        }
        .btn:hover { background: #333; }
        
        .map-container { margin-top: 50px; border: 1px solid #eee; border-radius: 4px; overflow: hidden; }
        
        footer { text-align: center; padding: 60px; color: #bbb; font-size: 0.85rem; letter-spacing: 1px; }
    </style>
</head>
<body>

<header>
    <h1>JAYRAN</h1>
    <p class="tagline">HANDCRAFTED NATURE-INSPIRED JEWELRY</p>
</header>

<div class="container">
    <div class="product-grid">
        
        <div class="product-card">
            <img src="4.jfif" alt="Leaf Collection A" onclick="window.open(this.src)">
            <div class="product-info">
                <div class="product-title">Leaf Collection A</div>
                <p class="description">Handcrafted ceramic earrings with intricate leaf textures. Finished with turquoise accents.</p>
                <p class="price">€49.00</p>
            </div>
        </div>

        <div class="product-card">
            <img src="5.jfif" alt="Leaf Collection B" onclick="window.open(this.src)">
            <div class="product-info">
                <div class="product-title">Leaf Collection B</div>
                <p class="description">Nature-inspired design featuring authentic turquoise stones and rustic wood elements.</p>
                <p class="price">€55.00</p>
            </div>
        </div>

        <div class="product-card">
            <img src="94e5e2a1-a59f-4a53-bba8-21978908a5ef.jfif" alt="Premium Packaging" onclick="window.open(this.src)">
            <div class="product-info">
                <div class="product-title">Premium Packaging</div>
                <p class="description">Every piece comes in our signature JAYRAN luxury gift box, ready for special occasions.</p>
                <p class="price">Included</p>
            </div>
        </div>

        <div class="product-card">
            <img src="05fd2fd5-b537-4962-a431-02107b695ec9.jfif" alt="Detail View" onclick="window.open(this.src)">
            <div class="product-info">
                <div class="product-title">Fine Details</div>
                <p class="description">Close-up view of the handcrafted textures inspired by the forests of Germany.</p>
                <p class="price">€59.00</p>
            </div>
        </div>

        <div class="product-card">
            <img src="image_47e95b.jpg" alt="The Collection" onclick="window.open(this.src)">
            <div class="product-info">
                <div class="product-title">The Full Collection</div>
                <p class="description">Our complete set of artisanal jewelry. Custom orders available upon request.</p>
                <p class="price">Contact for Quote</p>
            </div>
        </div>

    </div>

    <div class="contact-section">
        <div class="contact-title">Inquiries & Orders</div>
        <div class="contact-details">
            <p><strong>Location:</strong> Bad Windsheim, Germany</p>
            <p><strong>WhatsApp / Phone:</strong> +49 1XX XXXXXXXX</p>
            <p><strong>Email:</strong> info@jzebardast.com</p>
        </div>
        <a href="https://wa.me/491XXXXXXXX" class="btn">Order via WhatsApp</a>
        
        <div class="map-container">
            <iframe src="
