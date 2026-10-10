<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deepak Biscuits Bakery | Homemade Biscuits - Jalandhar"Lambra Abadi"</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Poppins:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      font-family: 'Poppins', sans-serif;
      background: #fff8f0;
      color: #333;
      line-height: 1.7;
    }
    h1, h2, h3 { font-family: 'Playfair Display', serif; }
    /* Animations */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .fade-up { animation: fadeUp 0.9s ease both; }
    .delay-1 { animation-delay: 0.15s; }
    .delay-2 { animation-delay: 0.3s; }
    .delay-3 { animation-delay: 0.45s; }
    /* NAV */
    nav {
      background: #2c1810;
      color: white;
      padding: 14px 5%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 3px 15px rgba(0,0,0,0.3);
    }
    .logo { font-size: 1.4rem; font-weight: 700; }
    .logo span { color: #f4a261; }
    nav ul { display: flex; list-style: none; gap: 6px; }
    nav a {
      color: #f5e6d3;
      text-decoration: none;
      font-weight: 500;
      font-size: 0.95rem;
      padding: 8px 14px;
      border-radius: 8px;
      transition: 0.25s;
    }
    nav a:hover, nav a.active {
      background: #f4a261;
      color: #2c1810;
    }
    nav a:active { transform: scale(0.95); }
    /* HERO */
    .hero {
      height: 88vh;
      min-height: 520px;
      background: linear-gradient(rgba(25,12,6,0.7), rgba(25,12,6,0.78)),
                  url('https://lh3.googleusercontent.com/gps-cs-s/ANWiy9Tu0iRLXvdT37eafBO79hYFbaG0LWC5CaZbcSfYe9bd7Jg79wkGkpiNfCexsOmUnXkPZiD23kL_O2XA3ktK3ntKPSDgrSIQyORDJfmI5Xuqmk9DNuMpbiIBnsYhMmPm5JH-p9MfE28_vqXw=s1360-w1360-h1020-rw') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      padding: 20px;
    }
    .hero-content h1 {
      font-size: 3.3rem;
      margin-bottom: 14px;
      text-shadow: 0 3px 12px rgba(0,0,0,0.5);
      animation: fadeUp 0.9s ease;
    }
    .hero-content p {
      font-size: 1.25rem;
      margin-bottom: 30px;
      opacity: 0.95;
      animation: fadeUp 1.1s ease;
    }
    .btn {
      display: inline-block;
      background: #f4a261;
      color: #2c1810;
      padding: 15px 38px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1rem;
      transition: all 0.3s ease;
      box-shadow: 0 8px 22px rgba(244,162,97,0.4);
      animation: fadeUp 1.3s ease;
    }
    .btn:hover {
      background: #e76f51;
      color: white;
      transform: translateY(-4px);
      box-shadow: 0 12px 28px rgba(231,111,81,0.45);
    }
    .btn:active { transform: scale(0.96); }
    /* SECTIONS */
    section { padding: 80px 5%; max-width: 1100px; margin: 0 auto; }
    .section-title {
      text-align: center;
      font-size: 2.3rem;
      color: #2c1810;
      margin-bottom: 12px;
    }
    .section-subtitle {
      text-align: center;
      color: #777;
      margin-bottom: 45px;
    }
    /* FEATURES */
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 24px;
      margin-top: 20px;
    }
    .feature-card {
      background: white;
      padding: 32px 22px;
      border-radius: 16px;
      text-align: center;
      box-shadow: 0 8px 25px rgba(0,0,0,0.07);
      border-top: 4px solid #f4a261;
      transition: 0.3s;
    }
    .feature-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 16px 35px rgba(0,0,0,0.12);
    }
    .feature-card:active { transform: scale(0.97); }
    .feature-card h3 { color: #2c1810; margin-bottom: 8px; font-size: 1.3rem; }
    .feature-card p { color: #555; font-size: 0.95rem; }
    /* ABOUT */
    .about-box {
      background: white;
      padding: 40px;
      border-radius: 18px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    }
    .about-box p { margin-bottom: 16px; font-size: 1.05rem; color: #444; }
    .specialty {
      background: #fff3e0;
      border-left: 5px solid #f4a261;
      padding: 28px;
      border-radius: 12px;
      margin-top: 28px;
    }
    .specialty h3 { color: #2c1810; margin-bottom: 14px; }
    .specialty ul { padding-left: 22px; }
    .specialty li { margin-bottom: 10px; }
    /* PRODUCTS */
    .price-card {
      background: white;
      border-radius: 20px;
      padding: 45px 35px;
      text-align: center;
      box-shadow: 0 12px 35px rgba(0,0,0,0.09);
      max-width: 480px;
      margin: 0 auto;
    }
    .price-option {
      background: #fff3e0;
      padding: 18px;
      border-radius: 14px;
      margin-bottom: 16px;
      font-size: 1.25rem;
      font-weight: 600;
      transition: 0.3s;
    }
    .price-option:hover { transform: scale(1.04); }
    .price-option:active { transform: scale(0.98); }
    .price-option span { color: #c45c26; font-size: 1.45rem; }
    .extra { margin-top: 22px; color: #666; font-size: 0.98rem; }
    /* GALLERY */
    .photo-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 22px;
    }
    .photo-grid img {
      width: 100%;
      height: 260px;
      object-fit: cover;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.12);
      transition: 0.4s;
      display: block;
    }
    .photo-grid img:hover {
      transform: scale(1.03);
      box-shadow: 0 16px 35px rgba(0,0,0,0.18);
    }
    /* CONTACT */
    .contact-box {
      background: linear-gradient(135deg, #2c1810, #4a2c1a);
      color: white;
      border-radius: 22px;
      padding: 55px 35px;
      text-align: center;
      box-shadow: 0 15px 40px rgba(44,24,16,0.3);
    }
    .contact-box h2 { color: white; margin-bottom: 10px; }
    .contact-details { margin: 28px 0; font-size: 1.15rem; }
    .contact-details a { color: #f4a261; text-decoration: none; font-weight: 600; }
    .contact-details p { margin-bottom: 12px; }
    .contact-btn {
      display: inline-block;
      background: #f4a261;
      color: #2c1810;
      padding: 14px 32px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.05rem;
      margin: 8px;
      transition: 0.3s;
    }
    .contact-btn:hover {
      background: #e76f51;
      color: white;
      transform: translateY(-3px);
    }
    .contact-btn:active { transform: scale(0.96); }
    .note {
      background: #fff3cd;
      color: #856404;
      padding: 13px 22px;
      border-radius: 10px;
      margin-top: 22px;
      font-weight: 600;
      display: inline-block;
    }
    footer {
      background: #1a0f0a;
      color: #c9b8a8;
      text-align: center;
      padding: 25px;
      margin-top: 50px;
      font-size: 0.95rem;
    }
    @media (max-width: 700px) {
      .hero-content h1 { font-size: 2.3rem; }
      nav ul { gap: 3px; }
      nav a { padding: 6px 10px; font-size: 0.85rem; }
      .photo-grid img { height: 210px; }
      .about-box { padding: 28px 20px; }
    }
  </style>
</head>
<body>
  <!-- NAV -->
  <nav>
    <div class="logo">Deepak <span>Biscuits</span></div>
    <ul>
      <li><a href="#home" class="active">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#products">Products</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
  <!-- HERO -->
  <section class="hero" id="home">
    <div class="hero-content">
      <h1>Deepak Biscuits Bakery</h1>
      <p>Homemade Taste • 100% Eggless • Pure Desi Ghee<br>Jalandhar"Lambra Abadi"</p>
      <a href="#contact" class="btn">Visit Our Shop & Get Fresh Biscuits</a>
    </div>
  </section>
  <!-- FEATURES -->
  <section>
    <div class="features">
      <div class="feature-card fade-up">
        <h3>100% Eggless</h3>
        <p>Sirf pure ingredients, bilkul eggless</p>
      </div>
      <div class="feature-card fade-up delay-1">
        <h3>Haath Se Bana</h3>
        <p>Har biscuit pyaar se apne haath se</p>
      </div>
      <div class="feature-card fade-up delay-2">
        <h3>Desi Ghee</h3>
        <p>Asli shudh ghee ka istemaal</p>
      </div>
      <div class="feature-card fade-up delay-3">
        <h3>Fresh Daily</h3>
        <p>Roz taaza biscuits banate hain</p>
      </div>
    </div>
  </section>
  <!-- ABOUT -->
  <section id="about">
    <h2 class="section-title">About Us</h2>
    <p class="section-subtitle">Homemade Taste & Purity</p>
    <div class="about-box fade-up">
      <p><strong>"Deepak Biscuits Bakery" mein aapka swagat hai!</strong></p>
      <p>Hum Jalandhar mein Homemade Taste aur Purity ka vaada karte hain. Humara har biscuit taaza (fresh) aur pyaar se apne haath se (by our own hands) banaya jaata hai. Hum 100% Eggless products ke saath, sirf Asli Desi Ghee ka istemaal karte hain. 🍪</p>
      <div class="specialty">
        <h3>Humare Biscuits ki Khaas Baat</h3>
        <p>Humari recipes bahut simple aur shudh (pure) hain. Har biscuit sirf in chaar mukhya cheezon se banta hai:</p>
        <ul>
          <li><strong>Aata (Whole Wheat Flour)</strong> – Healthy base ke liye</li>
          <li><strong>Khand (Unrefined Sugar)</strong> – Sugar aapke swaad ke anusar</li>
          <li><strong>Doodh (Milk)</strong> – Softness aur richness ke liye</li>
          <li><strong>Shudh Ghee (Pure Clarified Butter)</strong> – Authentic taste ke liye</li>
        </ul>
        <p style="margin-top: 16px;">Aap apni pasand ke anusaar <strong>Dry Fruits</strong> bhi add karwa sakte hain.</p>
      </div>
    </div>
  </section>
  <!-- PRODUCTS -->
  <section id="products">
    <h2 class="section-title">Hamare Biscuits</h2>
    <p class="section-subtitle">Whole Wheat • Freshly Made • Pure Ingredients</p>
    <div class="price-card fade-up">
      <h3 style="color:#2c1810; margin-bottom:25px; font-size:1.6rem;">Price List (Per Kg)</h3>
      <div class="price-option">
        Normal Ghee → <span>₹120 / kg</span>
      </div>
      <div class="price-option">
        Desi Ghee → <span>₹140 / kg</span>
      </div>
      <p class="extra">
        • Badam (Almond) add karwa sakte hain<br>
        • 100% Eggless<br>
        • Freshly made by hand
      </p>
    </div>
  </section>
  <!-- GALLERY -->
  <section id="gallery">
    <h2 class="section-title">Hamare Fresh Biscuits</h2>
    <p class="section-subtitle">Real photos from our shop</p>
    <div class="photo-grid">
      <img src="https://lh3.googleusercontent.com/gps-cs-s/ANWiy9Tu0iRLXvdT37eafBO79hYFbaG0LWC5CaZbcSfYe9bd7Jg79wkGkpiNfCexsOmUnXkPZiD23kL_O2XA3ktK3ntKPSDgrSIQyORDJfmI5Xuqmk9DNuMpbiIBnsYhMmPm5JH-p9MfE28_vqXw=s1360-w1360-h1020-rw" alt="Deepak Biscuits 1" class="fade-up">
      <img src="https://lh3.googleusercontent.com/gps-cs-s/ANWiy9QcpKDNewWmvQSppF-Etz7ezeg_IDuv00yfgNYUa7CN-4BVup5IiTdJ5uxY8G-UdA0RGIjDtDLCtgdn7C3tr0nzdQ-oGiA5zwhoxpAQGS6xHQwsnHns-PQ4Has9LIgoFO4f6V4sL1JycWwS=s1360-w1360-h1020-rw" alt="Deepak Biscuits 2" class="fade-up delay-1">
      <img src="https://lh3.googleusercontent.com/gps-cs-s/ANWiy9SdKO0WiWUSpJI969ONU_BttlVTeJFrVBgcSGi3PleQj3j1uCWq1LNEV941dB_yb7gLOXIJ5Bxh_xWxFE8UDNhXSd7HRgYjip01XtLD8YZb_ktZdelZlEveyNVSbrj4i3w4PCIDY8Wzccqm=s1360-w1360-h1020-rw" alt="Deepak Biscuits 3" class="fade-up delay-2">
    </div>
  </section>
  <!-- CONTACT -->
  <section id="contact">
    <div class="contact-box fade-up">
      <h2>Vist our shop & Get Fresh Biscuits</h2>
      <p>Online delivery nahi hota. Sirf shop se collection.</p>
      <div class="contact-details">
        <p>📍 Deepak Biscuits Bakery, Jalandhar"Lambra Abadi"</p>
        <p>📞 <a href="tel:9872330967">9872330967</a></p>
      </div>
      <a href="tel:9872330967" class="contact-btn">Call Now</a>
      <a href="https://share.google/EptRUg2EE7ds9IXWY" target="_blank" class="contact-btn">Shop Location</a>
      <div class="note">
        Call karke order de sakte ho → Shop pe aake le jao
      </div>
    </div>
  </section>
  <footer>
    <p>© 2026 Deepak Biscuits Bakery • Homemade Biscuits in Jalandhar"Lambra Abadi"</p>
  </footer>
</body>
</html>
