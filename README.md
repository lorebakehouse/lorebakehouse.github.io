<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lore Bakehouse</title>
    <style>
        /* Yasakagama Inspired Layout with Terracotta Accents */
        :root {
            --bg-color: #1c1b1a;       /* Woodfire soot / deep charcoal kiln interior */
            --text-color: #ece9e2;     /* Raw unbleached linen / pale flour cream */
            --muted-text: #8e8a82;     /* Ash gray */
            --border-color: #33302c;   /* Weathered timber / dark stone line */
            --pop-color: #e28455;      /* The pop: Warm terracotta / raw copper */
            --font-main: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            --font-accent: "Georgia", "Times New Roman", serif;
        }

        * { box-sizing: border-box; }
        body {
            font-family: var(--font-main);
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.7;
            margin: 0;
            padding: 0;
            -webkit-font-smoothing: antialiased;
            letter-spacing: 0.2px;
        }

        .wrapper {
            max-width: 720px;
            margin: 0 auto;
            padding: 90px 24px;
        }

        /* Navigation Strip */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 20px;
            margin-bottom: 30px; 
            font-size: 0.8rem;
            letter-spacing: 1.5px;
            text-transform: uppercase;
        }

        nav .brand-container {
            display: flex;
            align-items: center;
        }

        nav .logo {
            height: 38px;
            width: auto;
            display: block;
            filter: invert(1) sepia(10%) contrast(90%) brightness(95%);
            opacity: 0.9;
        }
        
        nav .links a { color: var(--pop-color); text-decoration: none; margin-left: 24px; transition: opacity 0.2s ease; }
        nav .links a:hover { opacity: 0.8; }

        /* Landscape/Workshop Hero Placeholder */
        .hero-image-placeholder {
            width: 100%;
            height: 360px;
            background-color: #151413;
            border: 1px solid var(--border-color);
            margin-bottom: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--muted-text);
            font-family: var(--font-accent);
            font-style: italic;
            font-size: 0.9rem;
            letter-spacing: 1px;
        }

        /* Typography & Tone */
        h1 {
            font-family: var(--font-accent);
            font-size: 2.3rem;
            font-weight: 400;
            letter-spacing: -0.5px;
            margin: 0 0 16px 0;
            line-height: 1.2;
            color: var(--text-color);
        }

        .definition {
            font-family: var(--font-main);
            font-size: 0.88rem;
            color: var(--muted-text);
            margin-bottom: 50px;
            line-height: 1.6;
            border-left: 1px solid var(--pop-color);
            padding-left: 16px;
        }

        .definition strong { color: var(--text-color); font-weight: 500; }

        h2 {
            font-family: var(--font-main);
            font-size: 0.8rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: var(--pop-color);
            margin-top: 60px;
            margin-bottom: 24px;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 8px;
        }

        p { margin-bottom: 24px; font-size: 1.02rem; font-weight: 300; color: #dfded9; }

        /* Logistics & Schedule Grid */
        .market-list { margin-bottom: 40px; }
        .market-item { margin-bottom: 24px; padding-left: 16px; border-left: 1px solid var(--border-color); }
        .market-day { font-weight: 600; font-size: 0.95rem; color: var(--text-color); }
        .market-location { color: var(--muted-text); font-size: 0.95rem; margin-top: 4px; line-height: 1.5; }

        /* Care & Utility Systems */
        .tips-container { margin-top: 20px; }
        .tip-block { margin-bottom: 28px; }
        .tip-title { font-family: var(--font-accent); font-style: italic; font-size: 1.05rem; color: var(--text-color); margin-bottom: 6px; }
        .tip-desc { font-size: 0.95rem; color: var(--muted-text); font-weight: 300; }

        /* Direct-Action Footer Links */
        .footer-links { margin-top: 70px; padding-top: 40px; border-top: 1px solid var(--border-color); }
        .arrow-link { display: block; font-size: 1.02rem; color: var(--text-color); text-decoration: none; margin-bottom: 16px; font-weight: 400; font-family: var(--font-accent); font-style: italic; }
        .arrow-link span { color: var(--pop-color); margin-right: 8px; font-style: normal; font-weight: bold; }
        .arrow-link:hover { text-decoration: underline; color: var(--pop-color); }

        footer { margin-top: 90px; font-size: 0.7rem; color: var(--muted-text); letter-spacing: 1px; text-transform: uppercase; }

        @media (max-width: 600px) {
            .wrapper { padding: 50px 20px; }
            h1 { font-size: 2rem; }
            nav { flex-direction: column; align-items: flex-start; gap: 16px; }
            nav .links { margin-top: 4px; }
            nav .links a { margin-left: 0; margin-right: 20px; }
            .hero-image-placeholder { height: 220px; }
        }
    </style>
</head>
<body>

    <div class="wrapper">
        <!-- Navigation Strip with Standalone Logo Image Block -->
        <nav>
            <div class="brand-container">
                <img src="Lore Bakehouse-logos_black.png" alt="Lore Bakehouse" class="logo">
            </div>
            <div class="links">
                <a href="#provisions">Provisions</a>
                <a href="#philosophy">Philosophy</a>
                <a href="#preservation">Preservation</a>
            </div>
        </nav>

        <!-- Landscape / Woodfire Workshop Hero Image Placeholder -->
        <div class="hero-image-placeholder">
            [ Farmhouse Bakery &amp; Woodfire Oven Landscape ]
        </div>

        <!-- Identity Content Framework -->
        <main>
            <h1>Lore Bakehouse</h1>
            <div class="definition">
                <strong>lore (noun)</strong><br>
                1: a particular body of knowledge or tradition<br>
                2: something that is learned: traditional knowledge or belief
            </div>

            <p>Lore Bakehouse is a home-based bakery operating under Florida's cottage food laws, practicing the traditional knowledge of sourdough baking. We offer handmade artisan breads and baked goods using the highest quality ingredients. All the flour we use is sourced from a Southern mill and is 100% organic. We favor whole grains. Our dairy products are organic and/or grass-fed.</p>
            <p>Our mission is to produce nourishing and delicious food and to support the growth of the North Florida local food community.</p>

            <!-- Section: Provisions -->
            <section id="provisions">
                <h2>Weekly Provisions ↓</h2>
                <div class="market-list">
                    <div class="market-item">
                        <div class="market-day">Saturdays — 8:30 am to 12:00 pm</div>
                        <div class="market-location">@ Haile Farmers Market<br>5213 SW 91st Terrace, Gainesville, FL</div>
                    </div>
                    <div class="market-item">
                        <div class="market-day">Mondays — 4:00 pm to 7:00 pm</div>
                        <div class="market-location">@ Grove Street Farmers Market<br>1001 NW 4th St, Gainesville, FL 32601</div>
                    </div>
                </div>
            </section>

            <!-- Section: Philosophy -->
            <section id="philosophy">
                <h2>Why Sourdough? ↓</h2>
                <p>While many think of sourdough as a flavor, it is actually a method for making bread and other baked goods rise. Most breads labeled "sourdough" in the United States are actually yeasted breads with lactic acid added for flavor. Real sourdough products made via the traditional method can be sweet, savory, mild, or tangy.</p>
                <p>The story of sourdough is ancient. For thousands of years, people have been using the sourdough method to create healthy bread, a vital staple that has nourished civilizations. All of our leavened products start with this traditional method, harnessing the power of a living ecosystem of wild yeasts and bacteria to bring our products to life.</p>
                <p>There are many benefits of baking with sourdough. Through sourdough's slow fermentation process, wild yeasts and bacteria feed on the starch found in the flour. This results in a bread with a lower glycemic index compared to yeasted breads. Additionally, the same process breaks down gluten and increases digestibility and the absorption of nutrients.</p>
            </section>

            <!-- Section: Preservation -->
            <section id="preservation">
                <h2>Storage & Care Tips ↓</h2>
                <div class="tips-container">
                    <div class="tip-block">
                        <div class="tip-title">Day 1 to 3: The Counter</div>
                        <div class="tip-desc">Keep your bread cut-side down on a wooden cutting board or stored in a brown paper bag. Avoid plastic bags, which trap moisture and soften the beautiful, crisp crust. Never store real bread in the refrigerator, as it forces the moisture out and stales the crumb prematurely.</div>
                    </div>
                    <div class="tip-block">
                        <div class="tip-title">Long Term: The Freezer</div>
                        <div class="tip-desc">Slice the loaf completely before freezing. Store the slices in a tightly sealed freezer bag. When you want a slice, drop it directly from the freezer straight into the toaster or oven to bring back that fresh-baked texture instantly.</div>
                    </div>
                </div>
            </section>

            <!-- Editorial Action Links -->
            <section class="footer-links">
                <a class="arrow-link" href="https://www.instagram.com/lorebakehouse" target="_blank" rel="noopener"><span>→</span> Instagram Updates</a>
                <a class="arrow-link" href="mailto:hello@lorebakehouse.com"><span>→</span> Preorders & Inquiries</a>
            </section>
        </main>

        <footer>
            &copy; 2026 Lore Bakehouse. Operating under Florida Cottage Food Law.
        </footer>
    </div>

</body>
</html>
