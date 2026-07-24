<!DOCTYPE html>
<html lang="te">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>నా డైనమిక్ వెబ్‌సైట్</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f8f9fa; color: #333; line-height: 1.6; }
        
        /* Navigation Bar */
        header { background: #2c3e50; color: white; padding: 1rem 0; text-align: center; position: sticky; top: 0; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        nav a:hover { color: #f39c12; }

        /* Hero Section */
        .hero { background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://picsum.photos/1200/400'); background-size: cover; color: white; text-align: center; padding: 80px 20px; }
        .hero h1 { font-size: 2.5rem; margin-bottom: 10px; }
        
        /* Container Sections */
        .container { max-width: 1000px; margin: 40px auto; padding: 0 20px; }
        .section-title { text-align: center; margin-bottom: 30px; color: #2c3e50; }

        /* Cards Grid */
        .grid { display: flex; gap: 20px; flex-wrap: wrap; justify-content: center; }
        .card { background: white; border-radius: 8px; padding: 20px; flex: 1 1 250px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); text-align: center; }
        .card img { width: 100%; height: 150px; object-fit: cover; border-radius: 5px; }

        /* Footer */
        footer { background: #2c3e50; color: white; text-align: center; padding: 20px; margin-top: 50px; }
    </style>
</head>
<body>

    <!-- Header & Navigation Menu -->
    <header>
        <h1>నా పర్సనల్ వెబ్‌సైట్</h1>
        <nav>
            <a href="#home">హోమ్</a>
            <a href="#about">నా గురించి</a>
            <a href="#services">సేవలు</a>
            <a href="#contact">కాంటాక్ట్</a>
        </nav>
    </header>

    <!-- Banner Section -->
    <section id="home" class="hero">
        <h1>నా డిజిటల్ ప్రపంచానికి స్వాగతం!</h1>
        <p>ఇక్కడ నా ప్రాజెక్ట్‌లు మరియు వివరాలు చూడవచ్చు.</p>
    </section>

    <!-- About Section -->
    <section id="about" class="container">
        <h2 class="section-title">నా గురించి</h2>
        <p style="text-align: center;">నమస్కారం! ఇది నా సొంత వెబ్‌సైట్. నేను కొత్త టెక్నాలజీలు నేర్చుకోవడానికి మరియు నా వర్క్ షేర్ చేయడానికి ఈ సైట్‌ని క్రియేట్ చేశాను.</p>
    </section>

    <!-- Services / Projects Section -->
    <section id="services" class="container">
        <h2 class="section-title">నా ప్రాజెక్ట్‌లు / సేవలు</h2>
        <div class="grid">
            <div class="card">
                <img src="https://picsum.photos/300/200?random=1" alt="Project 1">
                <h3 style="margin-top:15px;">వెబ్ డిజైనింగ్</h3>
                <p>ఆకర్షణీయమైన వెబ్‌సైట్‌ల నిర్మాణం.</p>
            </div>
            <div class="card">
                <img src="https://picsum.photos/300/200?random=2" alt="Project 2">
                <h3 style="margin-top:15px;">కంటెంట్ క్రియేషన్</h3>
                <p>ఉపయోగకరమైన సమాచారాన్ని అందించడం.</p>
            </div>
            <div class="card">
                <img src="https://picsum.photos/300/200?random=3" alt="Project 3">
                <h3 style="margin-top:15px;">కోడింగ్ నేర్చుకోవడం</h3>
                <p>HTML, CSS & JS ప్రాక్టీస్.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container" style="text-align: center;">
        <h2 class="section-title">సంప్రదించండి</h2>
        <p>ఇమెయిల్: myemail@example.com</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 నా వెబ్‌సైట్. All Rights Reserved.</p>
    </footer>

</body>
</html>
