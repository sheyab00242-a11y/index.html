
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmed Sheyab | Graphic Designer Portfolio</title>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cloudflare.com">
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0f172a;
            color: #f8fafc;
            line-height: 1.6;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Navbar */
        header {
            background-color: #1e293b;
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: 700;
            color: #38bdf8;
            text-decoration: none;
        }

        .nav-links a {
            color: #cbd5e1;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: #38bdf8;
        }

        /* Hero Section */
        .hero {
            padding: 100px 0 80px 0;
            text-align: center;
            background: linear-gradient(180deg, #1e293b 0%, #0f172a 100%);
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
            color: #ffffff;
        }

        .hero h1 span {
            color: #38bdf8;
        }

        .hero p {
            font-size: 20px;
            color: #94a3b8;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background-color: #38bdf8;
            color: #0f172a;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: transform 0.3s, background-color 0.3s;
        }

        .btn:hover {
            background-color: #0ea5e9;
            transform: translateY(-3px);
        }

        /* About & Experience Section */
        .main-content {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            margin-bottom: 50px;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 4px;
            background-color: #38bdf8;
            margin: 10px auto 0 auto;
            border-radius: 2px;
        }

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }

        @media (max-width: 768px) {
            .about-grid {
                grid-template-columns: 1fr;
                text-align: center;
            }
            .hero h1 { font-size: 36px; }
        }

        .exp-box {
            background-color: #1e293b;
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid #38bdf8;
        }

        .exp-box h3 {
            font-size: 24px;
            color: #ffffff;
            margin-bottom: 10px;
        }

        .exp-box .years {
            color: #38bdf8;
            font-weight: 600;
            margin-bottom: 15px;
        }

        /* Services / Skills */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .service-card {
            background-color: #1e293b;
            padding: 30px;
            border-radius: 12px;
            text-align: center;
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-card i {
            font-size: 40px;
            color: #38bdf8;
            margin-bottom: 20px;
        }

        .service-card h4 {
            font-size: 20px;
            margin-bottom: 10px;
        }

        /* Contact Section */
        .contact {
            background-color: #1e293b;
            padding: 60px 0;
            text-align: center;
        }

        .social-links {
            margin-top: 30px;
        }

        .social-links a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background-color: #0f172a;
            color: #ffffff;
            margin: 0 10px;
            border-radius: 50px;
            font-size: 20px;
            text-decoration: none;
            transition: background-color 0.3s, color 0.3s;
        }

        .social-links a.fb:hover { background-color: #1877f2; }
        .social-links a.wa:hover { background-color: #25d366; }

        footer {
            background-color: #0f172a;
            text-align: center;
            padding: 20px 0;
            color: #64748b;
            font-size: 14px;
            border-top: 1px solid #1e293b;
        }
    </style>
</head>
<body>

    <!-- Header / Navbar -->
    <header>
        <div class="container nav-container">
            <a href="#" class="logo">AS Designs</a>
            <nav class="nav-links">
                <a href="#about">About</a>
                <a href="#services">Services</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Hi, I am <span>Ahmed Sheyab</span></h1>
            <p>Professional Graphic Designer</p>
            <a href="https://wa.me" target="_blank" class="btn"><i class="fab fa-whatsapp"></i> Hire Me</a>
        </div>
    </section>

    <!-- Main Content Section -->
    <div class="container main-content">
        
        <!-- About & Experience -->
        <section id="about" style="margin-bottom: 80px;">
            <h2 class="section-title">About Me & Experience</h2>
            <div class="about-grid">
                <div>
                    <p style="color: #94a3b8; font-size: 18px;">
                        ডিজিটাল দুনিয়ায় যেকোনো ব্র্যান্ড বা ব্যবসাকে ভিজ্যুয়ালি আকর্ষণীয় করে তোলার জন্য আমি কাজ করি। ক্রিয়েটিভ ডিজাইন এবং আধুনিক ট্রেন্ডের সমন্বয়ে ক্লায়েন্টের চাহিদা অনুযায়ী মানসম্মত কাজ উপহার দেওয়াই আমার লক্ষ্য।
                    </p>
                </div>
                <div class="exp-box">
                    <h3>Graphic Design Experience</h3>
                    <div class="years">২+ বছরের কাজের অভিজ্ঞতা</div>
                    <p style="color: #cbd5e1;">সফলতার সাথে বিভিন্ন লোকাল ও অনলাইন প্রোজেক্টে ডিজাইন পার্টনার হিসেবে কাজ করার অভিজ্ঞতা রয়েছে।</p>
                </div>
            </div>
        </section>

        <!-- Services -->
        <section id="services">
            <h2 class="section-title">My Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-palette"></i>
                    <h4>Logo & Branding</h4>
                    <p style="color: #94a3b8; font-size: 14px;">আপনার বিজনেসের জন্য ইউনিক এবং প্রফেশনাল লোগো ডিজাইন।</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-vector-square"></i>
                    <h4>Social Media Banner</h4>
                    <p style="color: #94a3b8; font-size: 14px;">ফেসবুক, ইউটিউব বা অন্যান্য মাধ্যমের জন্য আকর্ষণীয় পোস্টার ও ব্যানার।</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-ad"></i>
                    <h4>Flyer & Print Design</h4>
                    <p style="color: #94a3b8; font-size: 14px;">বিজনেস কার্ড, ফ্লায়ার এবং যেকোনো প্রিন্ট মিডিয়া ডিজাইন।</p>
                </div>
            </div>
        </section>

    </div>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title" style="color: #ffffff;">Let's Work Together</h2>
            <p style="color: #94a3b8;">আপনার নতুন কোনো প্রোজেক্ট নিয়ে আলোচনা করতে সরাসরি যোগাযোগ করতে পারেন</p>
            
            <div class="social-links">
                <!-- Facebook Link -->
                <a href="https://www.facebook.com/share/18EtBB3Aof/" target="_blank" class="fb" title="Facebook"><i class="fab fa-facebook-f"></i></a>
                <!-- WhatsApp Link -->
                <a href="https://wa.me" target="_blank" class="wa" title="WhatsApp"><i class="fab fa-whatsapp"></i></a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Ahmed Sheyab. All Rights Reserved.</p>
    </footer>

</body>
</html>
