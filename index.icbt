<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUXE COLLECTION | PREMIUM FASHION</title>
    <style>
        /* Base Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            scroll-behavior: smooth;
        }

        body {
            background-color: #0905f04d; /* Light elegant green tint */
            color: #1a1a1a;
            overflow-x: hidden;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 5%;
            background: #d4d6d42c;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 15px rgba(0,0,0,0.03);
        }

        .logo {
            font-size: 20px;
            font-weight: bold;
            letter-spacing: 5px;
            text-transform: uppercase;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        .nav-links a {
            text-decoration: none;
            color: #1a1a1a;
            font-size: 12px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: 0.3s;
        }

        .nav-links a:hover { color: #c5a059; }

        /* Hero Section */
        .hero-container {
            position: relative;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }

        .hero-bg {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background: url('https://images.unsplash.com/photo-1490481651871-ab68de25d43d?q=80&w=2070') center/cover;
            filter: blur(10px);
            transform: scale(1.1);
            z-index: -1;
        }

        .hero-overlay {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.3);
            z-index: 0;
        }

        .hero-content {
            position: relative;
            z-index: 1;
            text-align: center;
            color: rgb(248, 243, 243);
        }

        .hero-content h1 {
            font-size: clamp(3rem, 12vw, 7rem);
            letter-spacing: 30px;
            text-transform: uppercase;
            font-weight: 200;
            text-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }

        /* Common Header Style */
        .section-header {
            font-size: 28px;
            letter-spacing: 8px;
            text-transform: uppercase;
            margin-bottom: 40px;
            color: #1a1a1a;
            position: relative;
            display: inline-block;
            text-align: center;
            width: 100%;
        }

        .section-header::after {
            content: '';
            position: absolute;
            width: 50px; height: 2px;
            background: #c5a059;
            bottom: -15px; left: 50%;
            transform: translateX(-50%);
        }

        /* --- UPDATED FULL ABOUT SECTION --- */
        .about-section {
            padding: 100px 10%;
            background: rgb(245, 250, 245);
        }

        .about-intro {
            max-width: 800px;
            margin: 0 auto 80px;
            text-align: center;
            line-height: 2;
            color: #555;
            font-size: 16px;
        }

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            margin-bottom: 80px;
            align-items: center;
        }

        .about-image {
            width: 100%;
            height: 450px;
            background: url('https://images.unsplash.com/photo-1441986300917-64674bd600d8?q=80&w=2070') center/cover;
            border-radius: 2px;
        }

        .about-content h3 {
            font-size: 14px;
            letter-spacing: 3px;
            text-transform: uppercase;
            color: #c5a059;
            margin-bottom: 15px;
        }

        .about-content p {
            margin-bottom: 25px;
            line-height: 1.8;
            color: #444;
        }

        /* Vision, Mission, Values Grid */
        .vmv-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }

        .vmv-box {
            padding: 40px;
            background: #f1eef1;
            border: 1px solid #080808;
            text-align: center;
            transition: 0.3s;
        }

        .vmv-box:hover {
            border-color: #c5a059;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
        }

        .vmv-box h4 {
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 15px;
            font-size: 13px;
            color: #111;
        }

        /* Catalog Grid */
        .catalog-title { text-align: center; padding: 80px 0 20px; font-size: 24px; letter-spacing: 5px; text-transform: uppercase; }
        .catalog-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 30px; padding: 40px 5%; }
        .product-card { background: #27899b; padding-bottom: 20px; border: 1px solid #eee; transition: 0.4s; }
        .product-card:hover { transform: translateY(-10px); }
        .img-container { width: 100%; height: 380px; overflow: hidden; }
        .product-img { width: 100%; height: 100%; object-fit: cover; transition: 0.6s; }
        .product-card:hover .product-img { transform: scale(1.08); }
        .product-info { padding: 20px; text-align: center; }
        .product-name { font-size: 13px; font-weight: bold; margin-bottom: 8px; }
        .product-price { color: #c5a059; font-weight: bold; }

        /* Table Section */
        .table-section { padding: 80px 5%; background: #f1ecec; }
        .table-wrapper { max-width: 1000px; margin: 0 auto; overflow-x: auto; }
        table { width: 100%; border-collapse: collapse; background: white; }
        th { background: #111; color: #c5a059; padding: 15px; text-align: left; font-size: 11px; text-transform: uppercase; }
        td { padding: 15px; border-bottom: 1px solid #634f7e; font-size: 13px; }
        .size-tag { background: #ebe4e4; padding: 2px 6px; border-radius: 3px; font-size: 10px; margin-right: 4px; }

        /* Contact Section */
        .contact-section { padding: 100px 10%; background: #ebe8e8; }
        .form-container { max-width: 600px; margin: 0 auto; }
        .form-group { margin-bottom: 25px; }
        .form-group label { display: block; font-size: 11px; text-transform: uppercase; font-weight: bold; margin-bottom: 10px; }
        .form-group input, .form-group select, .form-group textarea { width: 100%; padding: 15px; border: 1px solid #ddd; outline: none; }
        .submit-btn { width: 100%; background: #111; color: rgb(165, 123, 123); padding: 18px; border: none; text-transform: uppercase; letter-spacing: 2px; cursor: pointer; transition: 0.3s; }
        .submit-btn:hover { background: #c5a059; }

        /* Footer */
        .footer { background: #111; color: #999; padding: 60px 5%; text-align: center; font-size: 12px; }
        .footer h3 { color: #c5a059; letter-spacing: 3px; margin-bottom: 20px; font-size: 14px; }

        @media (max-width: 768px) {
            .about-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">LUXE</div>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#catalog">Collection</a></li>
            <li><a href="#details">Details</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <div style="cursor: pointer;">🔍</div>
    </nav>

    <div class="hero-container">
        <div class="hero-bg"></div>
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <h1>LUXE</h1>
        </div>
    </div>

    <section class="about-section" id="about">
        <h2 class="section-header">Our Story</h2>
        <p class="about-intro">
            Welcome to <strong>LUXE Collection</strong>, where elegance meets craftsmanship. We believe that fashion is more than just clothing; it is a statement of identity and a celebration of timeless grace.
        </p>

        <div class="about-grid">
            <div class="about-image"></div>
            <div class="about-content">
                <h3>The Heritage</h3>
                <p>Established in 2020 in the heart of Colombo, LUXE began as a small boutique dedicated to bespoke tailoring. Over the years, we have evolved into a premium fashion house, blending traditional Sri Lankan craftsmanship with contemporary global silhouettes.</p>
                
                <h3>Quality Excellence</h3>
                <p>Every piece in our collection is crafted with meticulous attention to detail. We source only the finest fabrics—from Italian silks to organic linens—ensuring that our customers experience unparalleled luxury and comfort.</p>
            </div>
        </div>

        <div class="vmv-container">
            <div class="vmv-box">
                <h4>Vision</h4>
                <p style="font-size: 14px; color: #666;">To become a global symbol of sustainable luxury fashion, inspiring confidence through timeless design.</p>
            </div>
            <div class="vmv-box">
                <h4>Mission</h4>
                <p style="font-size: 14px; color: #666;">To deliver superior quality garments that combine artisan craftsmanship with modern innovation for the sophisticated individual.</p>
            </div>
            <div class="vmv-box">
                <h4>Core Values</h4>
                <p style="font-size: 14px; color: #666;">Integrity, Innovation, Sustainability, and a relentless commitment to Premium Quality.</p>
            </div>
        </div>
    </section>

    <h2 class="catalog-title" id="catalog">The Collection</h2>
    <div class="catalog-grid" id="catalog-container"></div>

    <section class="table-section" id="details">
        <h2 class="section-header">Specifications</h2>
        <div class="table-wrapper">
            <table>
                <thead>
                    <tr>
                        <th>Product Name</th>
                        <th>Material</th>
                        <th>Available Sizes</th>
                        <th>Price (LKR)</th>
                    </tr>
                </thead>
                <tbody id="table-body"></tbody>
            </table>
        </div>
    </section>

    <section class="contact-section" id="contact">
        <h2 class="section-header">Get In Touch</h2>
        <div class="form-container">
            <form>
                <div class="form-group">
                    <label>Inquiry Type</label>
                    <select required>
                        <option value="">Select Option</option>
                        <option>General Inquiry</option>
                        <option>Appointment Request</option>
                        <option>Feedback</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Full Name</label>
                    <input type="text" placeholder="Your name" required>
                </div>
                <div class="form-group">
                    <label>Email Address</label>
                    <input type="email" placeholder="email@example.com" required>
                </div>
                <div class="form-group">
                    <label>Message</label>
                    <textarea placeholder="Write your message here..." style="height: 100px;"></textarea>
                </div>
                <button type="submit" class="submit-btn">Send Message</button>
            </form>
        </div>
    </section>

    <footer class="footer">
        <h3>LUXE COLLECTION</h3>
        <p>No 120, Luxury Arcade, Colombo 07, Sri Lanka.</p>
        <p>Email: info@luxecollection.lk | Designer: Samali Bandara</p>
        <p style="margin-top: 30px; font-size: 10px; opacity: 0.5;">© 2026 LUXE COLLECTION. ALL RIGHTS RESERVED.</p>
    </footer>

    <script>
        const catalogContainer = document.getElementById('catalog-container');
        const tableBody = document.getElementById('table-body');

        const products = [
            { name: "SILK SERENITY GOWN", price: 12500, mat: "Mulberry Silk", img: "https://images.unsplash.com/photo-1539109136881-3be0616acf4b?w=500" },
            { name: "AVANT-GARDE COAT", price: 18900, mat: "Wool Blend", img: "https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?w=500" },
            { name: "MIDNIGHT VELVET DRESS", price: 24500, mat: "Italian Velvet", img: "https://images.unsplash.com/photo-1496747611176-843222e1e57c?w=500" },
            { name: "SAHARA LINEN SHIRT", price: 8500, mat: "Organic Linen", img: "https://images.unsplash.com/photo-1581044777550-4cfa60707c03?w=500" },
            { name: "URBAN CHIC BLAZER", price: 32000, mat: "Fine Twill", img: "https://images.unsplash.com/photo-1509631179647-0177331693ae?w=500" },
            { name: "IVORY SATIN SKIRT", price: 15000, mat: "Premium Satin", img: "https://images.unsplash.com/photo-1485230895905-ec40ba36b9bc?w=500" },
            { name: "ECLIPSE NOIR TROUSERS", price: 45000, mat: "Cotton Gabardine", img: "https://images.unsplash.com/photo-1550639525-c97d455acf70?w=500" },
            { name: "CELESTIAL LACE TOP", price: 21000, mat: "French Lace", img: "https://images.unsplash.com/photo-1566174053879-31528523f8ae?w=500" }
        ];

        products.forEach(p => {
            catalogContainer.innerHTML += `
                <div class="product-card">
                    <div class="img-container">
                        <img src="${p.img}" class="product-img" alt="${p.name}">
                    </div>
                    <div class="product-info">
                        <p class="product-name">${p.name}</p>
                        <p class="product-price">LKR ${p.price.toLocaleString()}.00</p>
                    </div>
                </div>`;
            
            tableBody.innerHTML += `
                <tr>
                    <td><strong>${p.name}</strong></td>
                    <td>${p.mat}</td>
                    <td><span class="size-tag">S</span><span class="size-tag">M</span><span class="size-tag">L</span></td>
                    <td><b>LKR ${p.price.toLocaleString()}</b></td>
                </tr>`;
        });
    </script>
</body>
</html>
