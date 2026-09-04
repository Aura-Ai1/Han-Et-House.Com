<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Han Et House | Premium Steakhouse</title>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #d4af37;
            --bg-dark: #0f0f0f;
            --bg-card: #1a1a1a;
            --text-light: #f5f5f5;
            --text-muted: #aaa;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-light);
            line-height: 1.6;
        }

        h1, h2, h3, .logo {
            font-family: 'Cinzel', serif;
            letter-spacing: 1px;
        }

        /* Navigasyon */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 8%;
            background: rgba(15, 15, 15, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(212, 175, 55, 0.2);
            z-index: 1000;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--primary);
            text-transform: uppercase;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 30px;
        }

        .nav-links a {
            color: var(--text-light);
            text-decoration: none;
            font-size: 0.9rem;
            text-transform: uppercase;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        /* Hero Alanı */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.8)), 
                        url('https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }

        .hero h1 {
            font-size: 4rem;
            color: var(--primary);
            margin-bottom: 15px;
            text-transform: uppercase;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin-bottom: 30px;
            color: var(--text-muted);
        }

        .btn {
            display: inline-block;
            padding: 12px 35px;
            background: transparent;
            color: var(--primary);
            border: 2px solid var(--primary);
            text-decoration: none;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .btn:hover {
            background: var(--primary);
            color: var(--bg-dark);
            box-shadow: 0 0 15px rgba(212, 175, 55, 0.4);
        }

        /* Menü Bölümü */
        .section {
            padding: 100px 8%;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 50px;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 2px;
            background: var(--primary);
            margin: 10px auto 0;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .menu-item {
            background: var(--bg-card);
            border: 1px solid rgba(255,255,255,0.05);
            padding: 25px;
            border-radius: 4px;
            transition: transform 0.3s;
        }

        .menu-item:hover {
            transform: translateY(-5px);
            border-color: rgba(212, 175, 55, 0.3);
        }

        .menu-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 10px;
            border-bottom: 1px dashed rgba(255,255,255,0.1);
            padding-bottom: 10px;
        }

        .menu-price {
            color: var(--primary);
            font-weight: 600;
            font-size: 1.1rem;
        }

        .menu-desc {
            color: var(--text-muted);
            font-size: 0.85rem;
        }

        /* Rezervasyon Formu */
        .reservation-form {
            max-width: 600px;
            margin: 0 auto;
            background: var(--bg-card);
            padding: 40px;
            border-radius: 4px;
            border: 1px solid rgba(212, 175, 55, 0.2);
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-size: 0.85rem;
            color: var(--text-muted);
            text-transform: uppercase;
        }

        .form-group input, .form-group select {
            width: 100%;
            padding: 12px;
            background: var(--bg-dark);
            border: 1px solid #333;
            color: var(--text-light);
            outline: none;
        }

        .form-group input:focus, .form-group select:focus {
            border-color: var(--primary);
        }

        footer {
            text-align: center;
            padding: 30px;
            background: #080808;
            color: var(--text-muted);
            font-size: 0.8rem;
            border-top: 1px solid rgba(255,255,255,0.05);
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">Han Et House</div>
        <ul class="nav-links">
            <li><a href="#home">Ana Sayfa</a></li>
            <li><a href="#menu">Menü</a></li>
            <li><a href="#reservation">Rezervasyon</a></li>
        </ul>
    </nav>

    <section id="home" class="hero">
        <h1>Han Et House</h1>
        <p>Ateşin, lezzetin ve ustalığın buluştuğu nokta. Özel dinlendirilmiş et çeşitlerimizle unutulmaz bir gastronomi deneyimi.</p>
        <a href="#reservation" class="btn">Masa Rezerve Et</a>
    </section>

    <section id="menu" class="section">
        <h2 class="section-title">Öne Çıkan Lezzetler</h2>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="menu-header">
                    <h3>Dallas Steak (400g)</h3>
                    <span class="menu-price">₺850</span>
                </div>
                <p class="menu-desc">28 gün kuru dinlendirilmiş dana pirzola, meşe odunu ateşinde ızgara edilmiş.</p>
            </div>
            <div class="menu-item">
                <div class="menu-header">
                    <h3>Han Özel Kuzu Kafes</h3>
                    <span class="menu-price">₺1.400</span>
                </div>
                <p class="menu-desc">Taze otlar ve tereyağı ile marine edilmiş, ağır ateşte pişmiş kuzu kafes.</p>
            </div>
            <div class="menu-item">
                <div class="menu-header">
                    <h3>Lokum Burger</h3>
                    <span class="menu-price">₺420</span>
                </div>
                <p class="menu-desc">Dana kontrfile dilimleri, karamelize soğan, cheddar peyniri ve özel sos ile.</p>
            </div>
        </div>
    </section>

    <section id="reservation" class="section">
        <h2 class="section-title">Online Rezervasyon</h2>
        <form class="reservation-form" id="resForm">
            <div class="form-group">
                <label>Ad Soyad</label>
                <input type="text" required placeholder="Adınız">
            </div>
            <div class="form-group">
                <label>Tarih ve Saat</label>
                <input type="datetime-local" required>
            </div>
            <div class="form-group">
                <label>Kişi Sayısı</label>
                <select required>
                    <option value="2">2 Kişi</option>
                    <option value="4">4 Kişi</option>
                    <option value="6">6+ Kişi</option>
                </select>
            </div>
            <button type="submit" class="btn" style="width: 100%;">Rezervasyonu Onayla</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 Han Et House. Tüm hakları saklıdır.</p>
    </footer>

    <script>
        document.getElementById('resForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Rezervasyon talebiniz alındı! Sizinle en kısa sürede iletişime geçeceğiz.');
            this.reset();
        });
    </script>
</body>
</html>
