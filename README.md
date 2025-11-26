<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Shri Ram Decoration | Sultanpur</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Shri Ram Decoration - Wedding, Birthday, Flower, Light & All Event Decoration in Sultanpur, Uttar Pradesh. 11 years experience." />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Yeseva+One&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #f4b41a;
      --primary-dark: #c48a00;
      --accent: #f72585;
      --accent-2: #4cc9f0;
      --bg: #faf7ff;
      --text: #1d1b27;
      --muted: #6b6b80;
      --card-bg: #ffffff;
      --border-soft: rgba(0,0,0,0.06);
      --shadow-soft: 0 18px 40px rgba(15, 23, 42, 0.14);
      --radius-lg: 24px;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Poppins', system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
      background: radial-gradient(circle at top left, #fff3d9 0, #faf7ff 40%, #ffffff 100%);
      color: var(--text);
      scroll-behavior: smooth;
    }
    a { text-decoration: none; color: inherit; }
    img { max-width: 100%; display: block; }
    ul { list-style: none; }

    .container {
      width: 100%;
      max-width: 1120px;
      margin: 0 auto;
      padding: 0 16px;
    }

    /* Navbar */
    header {
      position: sticky;
      top: 0;
      z-index: 999;
      backdrop-filter: blur(16px);
      background: rgba(255, 255, 255, 0.9);
      border-bottom: 1px solid rgba(255, 255, 255, 0.7);
    }
    .nav {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 0;
    }
    .nav-left {
      display: flex;
      gap: 10px;
      align-items: center;
    }
    .logo-circle {
      width: 44px;
      height: 44px;
      border-radius: 50%;
      background: radial-gradient(circle at 20% 20%, #ffe8b3, #f4b41a);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 22px;
      font-weight: 700;
      color: #4a2b00;
      border: 2px solid #ffffff;
      box-shadow: 0 8px 18px rgba(0,0,0,0.15);
    }
    .nav-title {
      display: flex;
      flex-direction: column;
    }
    .nav-title span:first-child {
      font-family: 'Yeseva One', cursive;
      font-size: 18px;
      letter-spacing: 0.5px;
    }
    .nav-title span:last-child {
      font-size: 11px;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    .nav-links {
      display: flex;
      flex-wrap: wrap;
      gap: 18px;
      font-size: 13px;
      text-transform: uppercase;
      letter-spacing: 1.3px;
    }
    .nav-links a {
      position: relative;
      padding-bottom: 4px;
      color: #33344f;
    }
    .nav-links a::after {
      content: "";
      position: absolute;
      left: 0;
      bottom: 0;
      width: 0;
      height: 2px;
      background: linear-gradient(90deg, var(--primary), var(--accent));
      transition: width 0.2s ease;
    }
    .nav-links a:hover::after {
      width: 100%;
    }
    .nav-cta {
      display: flex;
      gap: 10px;
      align-items: center;
    }
    .btn {
      border-radius: 999px;
      padding: 9px 18px;
      border: none;
      font-size: 13px;
      font-weight: 500;
      cursor: pointer;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      transition: transform 0.12s ease, box-shadow 0.12s ease, background 0.12s ease;
      white-space: nowrap;
    }
    .btn-primary {
      background: linear-gradient(120deg, var(--primary), var(--accent));
      color: #fff;
      box-shadow: 0 14px 24px rgba(248, 165, 35, 0.35);
    }
    .btn-outline {
      background: rgba(255,255,255,0.75);
      border: 1px solid rgba(0,0,0,0.08);
      color: #363653;
    }
    .btn:hover {
      transform: translateY(-1px);
      box-shadow: 0 18px 35px rgba(15, 23, 42, 0.20);
    }

    /* Hero */
    .hero {
      padding: 40px 0 60px;
    }
    .hero-grid {
      display: grid;
      grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr);
      gap: 32px;
      align-items: center;
    }
    @media (max-width: 840px) {
      .hero-grid {
        grid-template-columns: 1fr;
      }
      .nav-links { display: none; }
    }
    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 2px;
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(255,255,255,0.85);
      border: 1px solid rgba(0,0,0,0.05);
      margin-bottom: 12px;
    }
    .eyebrow-dot {
      width: 7px;
      height: 7px;
      border-radius: 50%;
      background: linear-gradient(120deg, var(--primary), var(--accent));
    }
    .hero h1 {
      font-family: 'Yeseva One', cursive;
      font-size: 38px;
      line-height: 1.1;
      margin-bottom: 10px;
    }
    .hero-gradient {
      background: linear-gradient(120deg, #f72585, #ff9f1c);
      -webkit-background-clip: text;
      color: transparent;
    }
    .hero-sub {
      color: var(--muted);
      font-size: 14px;
      margin-bottom: 18px;
    }
    .hero-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      font-size: 11px;
      margin-bottom: 20px;
    }
    .badge {
      border-radius: 999px;
      padding: 5px 11px;
      border: 1px solid rgba(0,0,0,0.05);
      background: rgba(255,255,255,0.9);
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }
    .badge strong {
      font-size: 12px;
    }
    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-bottom: 18px;
    }
    .hero-note {
      font-size: 11px;
      color: var(--muted);
    }
    .hero-right {
      position: relative;
    }
    .hero-card {
      background: radial-gradient(circle at 0 0, #fffaf0, #ffffff);
      border-radius: 32px;
      box-shadow: var(--shadow-soft);
      padding: 20px 18px;
      border: 1px solid rgba(244, 180, 26, 0.2);
      position: relative;
      overflow: hidden;
    }
    .hero-tag {
      position: absolute;
      right: 16px;
      top: 16px;
      font-size: 11px;
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(0,0,0,0.06);
      color: #43302b;
    }
    .hero-card h3 {
      font-size: 16px;
      margin-bottom: 6px;
    }
    .hero-card p {
      font-size: 12px;
      color: var(--muted);
      margin-bottom: 12px;
    }
    .hero-timeline {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
      margin-top: 8px;
    }
    .mini-card {
      border-radius: 18px;
      padding: 10px 10px;
      background: rgba(255,255,255,0.85);
      border: 1px solid rgba(255,255,255,0.8);
      font-size: 11px;
    }
    .mini-card strong {
      display: block;
      font-size: 13px;
      margin-bottom: 2px;
    }

    section {
      padding: 40px 0;
    }
    .section-header {
      text-align: center;
      margin-bottom: 24px;
    }
    .section-eyebrow {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 2px;
      color: var(--muted);
      margin-bottom: 6px;
    }
    .section-title {
      font-size: 24px;
      font-weight: 600;
      margin-bottom: 4px;
    }
    .section-sub {
      font-size: 13px;
      color: var(--muted);
    }

    .about-grid {
      display: grid;
      grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr);
      gap: 26px;
      align-items: flex-start;
    }
    @media (max-width: 840px) {
      .about-grid {
        grid-template-columns: 1fr;
      }
    }
    .about-card {
      background: var(--card-bg);
      border-radius: var(--radius-lg);
      border: 1px solid var(--border-soft);
      padding: 18px 18px 16px;
      box-shadow: 0 12px 28px rgba(15, 23, 42, 0.05);
      font-size: 13px;
      color: var(--muted);
    }
    .stats-row {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
      margin-top: 14px;
    }
    .stat {
      min-width: 90px;
    }
    .stat strong {
      display: block;
      font-size: 18px;
      font-weight: 600;
      color: var(--text);
    }
    .stat span {
      font-size: 11px;
      color: var(--muted);
    }

    .cards-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 16px;
    }
    .card {
      background: var(--card-bg);
      border-radius: var(--radius-lg);
      padding: 14px 14px 12px;
      border: 1px solid var(--border-soft);
      box-shadow: 0 14px 30px rgba(15, 23, 42, 0.06);
      font-size: 13px;
      position: relative;
      overflow: hidden;
    }
    .card-tag {
      position: absolute;
      right: 12px;
      top: 10px;
      font-size: 10px;
      padding: 3px 8px;
      border-radius: 999px;
      background: rgba(244,180,26,0.16);
      color: #8a5b00;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
    .card h3 {
      font-size: 15px;
      margin-bottom: 4px;
    }
    .card p {
      font-size: 12px;
      color: var(--muted);
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 10px;
    }
    .gallery-item {
      border-radius: 18px;
      padding: 12px;
      border: 1px solid rgba(255,255,255,0.8);
      background: linear-gradient(135deg, #fffaf0, #ffe0f0);
      font-size: 12px;
      box-shadow: 0 12px 26px rgba(15,23,42,0.08);
      min-height: 90px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .gallery-pill {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      color: #9a4d12;
    }
    .gallery-caption {
      margin-top: 6px;
      font-size: 11px;
      color: #4a3a35;
    }

    .package-card {
      background: var(--card-bg);
      border-radius: var(--radius-lg);
      border: 1px solid var(--border-soft);
      box-shadow: 0 14px 30px rgba(15, 23, 42, 0.08);
      padding: 16px 16px 14px;
      font-size: 13px;
    }
    .package-card h3 {
      font-size: 16px;
      margin-bottom: 4px;
    }
    .package-tagline {
      font-size: 11px;
      color: var(--muted);
      margin-bottom: 8px;
    }
    .package-list {
      font-size: 12px;
      color: var(--muted);
      margin-bottom: 10px;
    }
    .package-list li {
      margin: 3px 0;
    }

    .form-card {
      background: var(--card-bg);
      border-radius: var(--radius-lg);
      border: 1px solid var(--border-soft);
      box-shadow: 0 14px 30px rgba(15,23,42,0.06);
      padding: 16px;
      font-size: 13px;
    }
    .form-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 12px;
    }
    label {
      font-size: 11px;
      font-weight: 500;
      color: #444;
      display: block;
      margin-bottom: 4px;
    }
    input, select, textarea {
      width: 100%;
      border-radius: 12px;
      border: 1px solid rgba(0,0,0,0.12);
      padding: 8px 10px;
      font-size: 13px;
      font-family: inherit;
      background: rgba(249,249,255,0.9);
      outline: none;
      transition: border 0.1s ease, box-shadow 0.1s ease, background 0.1s ease;
    }
    input:focus, select:focus, textarea:focus {
      border-color: var(--primary);
      box-shadow: 0 0 0 1px rgba(244,180,26,0.5);
      background: #ffffff;
    }
    textarea {
      min-height: 80px;
      resize: vertical;
    }

    .contact-grid {
      display: grid;
      grid-template-columns: minmax(0, 1fr) minmax(0, 1fr);
      gap: 20px;
    }
    @media (max-width: 840px) {
      .contact-grid { grid-template-columns: 1fr; }
    }
    .contact-card {
      background: var(--card-bg);
      border-radius: var(--radius-lg);
      border: 1px solid var(--border-soft);
      padding: 16px;
      font-size: 13px;
      box-shadow: 0 14px 30px rgba(15,23,42,0.06);
    }
    .contact-list li {
      margin: 6px 0;
      color: var(--muted);
    }

    .agent-wrapper {
      margin-top: 18px;
      display: grid;
      grid-template-columns: minmax(0, 260px) minmax(0, 1fr);
      gap: 16px;
    }
    @media (max-width: 840px) {
      .agent-wrapper {
        grid-template-columns: 1fr;
      }
    }
    .agent-login, .agent-panel {
      background: var(--card-bg);
      border-radius: var(--radius-lg);
      border: 1px solid var(--border-soft);
      padding: 14px 14px 12px;
      font-size: 13px;
      box-shadow: 0 12px 26px rgba(15,23,42,0.06);
    }
    .agent-panel {
      display: none;
    }
    .agent-note {
      font-size: 11px;
      color: var(--muted);
      margin-bottom: 8px;
    }
    .upload-preview {
      margin-top: 10px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));
      gap: 8px;
    }
    .upload-thumb {
      border-radius: 12px;
      overflow: hidden;
      border: 1px solid rgba(0,0,0,0.08);
      background: #f3f3ff;
      height: 80px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 10px;
      color: var(--muted);
    }

    footer {
      padding: 18px 0 14px;
      border-top: 1px solid rgba(0,0,0,0.06);
      font-size: 11px;
      color: var(--muted);
    }
    footer .footer-inner {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 8px;
      align-items: center;
    }

    .whatsapp-float {
      position: fixed;
      right: 16px;
      bottom: 16px;
      width: 56px;
      height: 56px;
      border-radius: 50%;
      background: #25d366;
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
      box-shadow: 0 18px 40px rgba(0,0,0,0.25);
      z-index: 1000;
      text-decoration: none;
    }
    .whatsapp-float::after {
      content: "";
      position: absolute;
      inset: 4px;
      border-radius: 50%;
      border: 1px solid rgba(255,255,255,0.4);
    }

    .text-muted { color: var(--muted); }
    .mt-1 { margin-top: 4px; }
    .mt-2 { margin-top: 8px; }
    .mt-3 { margin-top: 12px; }
    .mt-4 { margin-top: 16px; }
  </style>
</head>
<body>

  <!-- Floating WhatsApp: direct link, no JS -->
  <a class="whatsapp-float" href="https://wa.me/917985634050" target="_blank" aria-label="Chat on WhatsApp">
    💬
  </a>

  <!-- Header / Nav -->
  <header>
    <div class="container">
      <nav class="nav">
        <div class="nav-left">
          <div class="logo-circle">श</div>
          <div class="nav-title">
            <span>Shri Ram Decoration</span>
            <span>Sultanpur · 11+ Years</span>
          </div>
        </div>
        <div class="nav-links">
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#services">Services</a>
          <a href="#gallery">Gallery</a>
          <a href="#packages">Packages</a>
          <a href="#booking">Booking</a>
          <a href="#agent">Agent Login</a>
        </div>
        <div class="nav-cta">
          <a href="tel:+917985634050" class="btn btn-outline">Call Now</a>
          <a href="https://wa.me/917985634050" target="_blank" class="btn btn-primary">WhatsApp</a>
        </div>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="hero">
    <div class="container">
      <div class="hero-grid">
        <div>
          <div class="eyebrow">
            <span class="eyebrow-dot"></span>
            SHRI RAM DECORATION · SULTANPUR
          </div>
          <h1>
            Royal <span class="hero-gradient">Wedding & Event</span><br/>
            Decoration in Sultanpur
          </h1>
          <p class="hero-sub">
            11+ साल से Sultanpur, Uttar Pradesh में शादी, जन्मदिन, फूल, लाइट, बैंड,
            कॉफी, पॉपकॉर्न और हर तरह की event decoration की premium सेवा।
          </p>

          <div class="hero-badges">
            <div class="badge">
              ⭐ <strong>11+ Years</strong> Experience
            </div>
            <div class="badge">
              🎉 All Event Decoration
            </div>
            <div class="badge">
              📍 All Sultanpur
            </div>
          </div>

          <div class="hero-actions">
            <a href="#booking" class="btn btn-primary">
              Book Your Event
            </a>
            <a href="https://wa.me/917985634050" target="_blank" class="btn btn-outline">
              Chat on WhatsApp
            </a>
          </div>
          <p class="hero-note">
            Quick response on call / WhatsApp: <strong>+91 79856 34050</strong>
          </p>
        </div>

        <div class="hero-right">
          <div class="hero-card">
            <div class="hero-tag">Upcoming Shaadi / Birthday?</div>
            <h3>Designer Decoration, बिना टेंशन के</h3>
            <p>
              बस तारीख, लोकेशन और budget बताइये – पूरी decoration planning Shri Ram
              Decoration संभाल लेगा।
            </p>

            <div class="hero-timeline">
              <div class="mini-card">
                <strong>Step 1 · Call / WhatsApp</strong>
                Event detail & decoration style decide कीजिए।
              </div>
              <div class="mini-card">
                <strong>Step 2 · Design & Setup</strong>
                हमारी team time पर पहुँचकर पूरा setup तैयार करती है।
              </div>
              <div class="mini-card">
                <strong>Step 3 · Event Day</strong>
                Royal look वाला सुंदर stage, gate, flowers & lighting।
              </div>
              <div class="mini-card">
                <strong>Step 4 · Happy Memories</strong>
                आपका event photos & videos में हमेशा के लिए यादगार।
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about">
    <div class="container">
      <div class="section-header">
        <div class="section-eyebrow">ABOUT SHRI RAM DECORATION</div>
        <div class="section-title">श्री राम के नाम से सजा हर आयोजन</div>
        <p class="section-sub">
          Owner – <strong>Gaya Prasad Gupta</strong>, 11 साल से decoration field में सेवा।
        </p>
      </div>

      <div class="about-grid">
        <div class="about-card">
          <p>
            <strong>Shri Ram Decoration</strong> Sultanpur, Uttar Pradesh की एक trusted
            decoration सेवा है। हम शादी, जन्मदिन, reception, thread ceremony,
            corporate events और हर तरह के कार्यक्रमों के लिए सुंदर और व्यवस्थित
            सजावट उपलब्ध करवाते हैं।
          </p>
          <p class="mt-2">
            हमारी टीम फूलों, लाइट, tent, stage, gate entry, band, coffee counter,
            popcorn counter और theme based decoration में expert है। हर event को हम
            आपके बजट के अंदर royal और यादगार बनाने की कोशिश करते हैं।
          </p>
          <div class="stats-row">
            <div class="stat">
              <strong>11+</strong>
              <span>Years experience</span>
            </div>
            <div class="stat">
              <strong>1000+</strong>
              <span>Decorated events</span>
            </div>
            <div class="stat">
              <strong>100%</strong>
              <span>Sultanpur focus</span>
            </div>
          </div>
        </div>

        <div class="about-card">
          <p><strong>Service Area</strong></p>
          <p class="mt-1 text-muted">
            Main City: <strong>Sultanpur, Uttar Pradesh</strong><br/>
            Local Area: पूरा Sultanpur और आसपास के क्षेत्र।
          </p>

          <p class="mt-3"><strong>Contact Directly</strong></p>
          <ul class="contact-list mt-1">
            <li>📞 Phone: <strong>+91 79856 34050</strong></li>
            <li>💬 WhatsApp: <strong>+91 79856 34050</strong></li>
          </ul>

          <p class="mt-3"><strong>Specialty</strong></p>
          <p class="mt-1 text-muted">
            • Time पर काम पूरा<br/>
            • साफ-सुथरा, सुंदर और balanced decoration<br/>
            • Budget के अंदर best material और design<br/>
            • Friendly & disciplined team
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services">
    <div class="container">
      <div class="section-header">
        <div class="section-eyebrow">DECORATION SERVICES</div>
        <div class="section-title">हर प्रकार के आयोजन के लिए सजावट</div>
        <p class="section-sub">
          Wedding से लेकर Birthday, Flower से लेकर Full Light & Tent – सब एक ही जगह।
        </p>
      </div>

      <div class="cards-grid">
        <div class="card">
          <div class="card-tag">Wedding</div>
          <h3>Wedding & Marriage Decoration</h3>
          <p>
            Stage, mandap, varmala stage, gate entry, path-way, seating area, photo
            corner – सब कुछ एक theme में।
          </p>
        </div>
        <div class="card">
          <div class="card-tag">Birthday</div>
          <h3>Birthday & Kids Theme Party</h3>
          <p>
            Balloon theme, cartoon theme, name backdrop, cake table decoration और
            पूरा फोटो-friendly setup।
          </p>
        </div>
        <div class="card">
          <div class="card-tag">Flowers</div>
          <h3>Flower Decoration</h3>
          <p>
            Fresh & artificial flowers के साथ gate, stage, backdrop और car decoration।
          </p>
        </div>
        <div class="card">
          <div class="card-tag">Lights</div>
          <h3>Lighting & Tent Setup</h3>
          <p>
            LED, serial lights, façade lighting, stage and hall lighting – पूरे
            venue को glow करने के लिए।
          </p>
        </div>
        <div class="card">
          <div class="card-tag">Extras</div>
          <h3>Band, Coffee & Popcorn</h3>
          <p>
            Band, coffee counter, popcorn counter और अन्य व्यवस्था जिससे आपका event
            और भी royal लगे।
          </p>
        </div>
        <div class="card">
          <div class="card-tag">All Events</div>
          <h3>All Type Event Decoration</h3>
          <p>
            शादी, सगाई, reception, mundan, thread ceremony, corporate meet, school
            कार्यक्रम – सभी के लिए decoration।
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Gallery -->
  <section id="gallery">
    <div class="container">
      <div class="section-header">
        <div class="section-eyebrow">GALLERY</div>
        <div class="section-title">Decoration Categories</div>
        <p class="section-sub">
          Agent login से आप real photos gallery में जोड़ सकते हैं।
        </p>
      </div>

      <div class="gallery-grid" id="static-gallery">
        <div class="gallery-item">
          <div class="gallery-pill">Wedding</div>
          <div class="gallery-caption">
            Royal varmala stage, floral gate और lighting वाला शादी setup।
          </div>
        </div>
        <div class="gallery-item">
          <div class="gallery-pill">Birthday</div>
          <div class="gallery-caption">
            Balloon arch, name board और cake table decoration के साथ birthday theme।
          </div>
        </div>
        <div class="gallery-item">
          <div class="gallery-pill">Flower</div>
          <div class="gallery-caption">
            Mandap, gate और backdrop पर fresh flower decoration।
          </div>
        </div>
        <div class="gallery-item">
          <div class="gallery-pill">Light</div>
          <div class="gallery-caption">
            Serial lights and LED focus के साथ पूरा venue glow।
          </div>
        </div>
        <div class="gallery-item">
          <div class="gallery-pill">Band</div>
          <div class="gallery-caption">
            Entry band और baarat के लिए व्यवस्था।
          </div>
        </div>
        <div class="gallery-item">
          <div class="gallery-pill">Coffee & Popcorn</div>
          <div class="gallery-caption">
            Coffee और popcorn counter के साथ guests के लिए special corner।
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Packages -->
  <section id="packages">
    <div class="container">
      <div class="section-header">
        <div class="section-eyebrow">PACKAGES</div>
        <div class="section-title">Basic, Standard & Premium</div>
        <p class="section-sub">
          Budget के हिसाब से 3 तरह के पैकेज – detail WhatsApp / call पर decide होगा।
        </p>
      </div>

      <div class="cards-grid">
        <div class="package-card">
          <h3>Basic Package</h3>
          <div class="package-tagline">छोटे events और simple decoration के लिए</div>
          <ul class="package-list">
            <li>• Basic stage decoration</li>
            <li>• Simple flower / balloon setup</li>
            <li>• Normal lighting</li>
            <li>• Basic gate decoration</li>
          </ul>
          <button class="btn btn-outline" onclick="scrollToBooking()">Enquiry for Basic</button>
        </div>

        <div class="package-card">
          <h3>Standard Package</h3>
          <div class="package-tagline">अच्छा balanced decoration – शादी / birthday के लिए</div>
          <ul class="package-list">
            <li>• Designer stage & backdrop</li>
            <li>• Flower + balloon combination</li>
            <li>• Entry gate decoration</li>
            <li>• Hall / lawn lighting</li>
            <li>• 1 counter (Coffee or Popcorn)</li>
          </ul>
          <button class="btn btn-primary" onclick="scrollToBooking()">Book Standard</button>
        </div>

        <div class="package-card">
          <h3>Premium Package</h3>
          <div class="package-tagline">Royal & full theme-based decoration</div>
          <ul class="package-list">
            <li>• High quality theme-based stage</li>
            <li>• Full venue flower & light decoration</li>
            <li>• Gate entry + varmala stage</li>
            <li>• Band + multiple counters (Coffee + Popcorn)</li>
            <li>• Customized design as per choice</li>
          </ul>
          <button class="btn btn-outline" onclick="scrollToBooking()">Enquiry for Premium</button>
        </div>
      </div>
    </div>
  </section>

  <!-- Booking -->
  <section id="booking">
    <div class="container">
      <div class="section-header">
        <div class="section-eyebrow">BOOKING FORM</div>
        <div class="section-title">अपना event details भेजिए</div>
        <p class="section-sub">
          Event type, date, location और budget भरें – हम जल्दी contact करेंगे।
        </p>
      </div>

      <div class="form-card">
        <form id="bookingForm">
          <div class="form-grid">
            <div>
              <label for="name">Name / नाम</label>
              <input id="name" type="text" required placeholder="आपका नाम" />
            </div>
            <div>
              <label for="phone">Mobile Number</label>
              <input id="phone" type="tel" required placeholder="आपका मोबाइल" />
            </div>
            <div>
              <label for="eventType">Event Type</label>
              <select id="eventType" required>
                <option value="">Select Event</option>
                <option>Wedding / Marriage</option>
                <option>Birthday</option>
                <option>Engagement</option>
                <option>Reception</option>
                <option>Corporate Event</option>
                <option>Other Function</option>
              </select>
            </div>
            <div>
              <label for="eventDate">Event Date</label>
              <input id="eventDate" type="date" required />
            </div>
            <div>
              <label for="location">Event Location</label>
              <input id="location" type="text" required placeholder="गांव / शहर / venue" />
            </div>
            <div>
              <label for="budget">Approx Budget</label>
              <input id="budget" type="text" placeholder="उदाहरण: 30,000 – 80,000" />
            </div>
            <div>
              <label for="style">Decoration Style</label>
              <input id="style" type="text" placeholder="Royal, Simple, Theme etc." />
            </div>
          </div>

          <div class="mt-3">
            <label for="message">Message / Extra Details</label>
            <textarea id="message" placeholder="जो भी extra detail या demand हो, यहाँ लिखें..."></textarea>
          </div>

          <div class="mt-3" style="display:flex; flex-wrap:wrap; gap:10px; align-items:center;">
            <button type="submit" class="btn btn-primary">Submit Booking Request</button>
            <a href="https://wa.me/917985634050" target="_blank" class="btn btn-outline">
              Send on WhatsApp
            </a>
          </div>
          <p class="hero-note mt-2">
            Note: यह form front-end demo है – real enquiry के लिए WhatsApp या call ज़रूर करें।
          </p>
        </form>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <div class="container">
      <div class="section-header">
        <div class="section-eyebrow">CONTACT</div>
        <div class="section-title">सीधे संपर्क करें</div>
        <p class="section-sub">
          Sultanpur में किसी भी event decoration के लिए कॉल या मैसेज कीजिए।
        </p>
      </div>

      <div class="contact-grid">
        <div class="contact-card">
          <h3>Contact Details</h3>
          <ul class="contact-list mt-2">
            <li>📍 <strong>Sultanpur, Uttar Pradesh</strong></li>
            <li>📞 Phone: <a href="tel:+917985634050"><strong>+91 79856 34050</strong></a></li>
            <li>💬 WhatsApp: <a href="https://wa.me/917985634050" target="_blank"><strong>+91 79856 34050</strong></a></li>
          </ul>
          <p class="mt-3 text-muted">
            Service Area: पूरे Sultanpur और आसपास के क्षेत्र।
          </p>
        </div>
        <div class="contact-card">
          <h3>Why Choose Shri Ram Decoration?</h3>
          <p class="mt-2 text-muted">
            • समय पर काम और साफ-सुथरी finishing<br/>
            • Budget के अंदर best decoration<br/>
            • Friendly & अनुभव वाली team<br/>
            • Wedding, Birthday, Flower, Light, Band, Coffee, Popcorn – one stop solution
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Agent Login & Panel -->
  <section id="agent">
    <div class="container">
      <div class="section-header">
        <div class="section-eyebrow">AGENT PANEL</div>
        <div class="section-title">Gallery Update – Agent Login</div>
        <p class="section-sub">
          Agent यहाँ से login करके gallery में नई photos add कर सकता है (local preview).
        </p>
      </div>

      <div class="agent-wrapper">
        <div class="agent-login">
          <h3>Agent Login</h3>
          <p class="agent-note">
            कृपया authorized agent ही login करें।
          </p>
          <form id="agentLoginForm">
            <div class="mt-2">
              <label for="agentId">Agent ID</label>
              <input id="agentId" type="text" placeholder="Enter Agent ID" required />
            </div>
            <div class="mt-2">
              <label for="agentPassword">Password</label>
              <input id="agentPassword" type="password" placeholder="Enter Password" required />
            </div>
            <div class="mt-3">
              <button type="submit" class="btn btn-primary">Login</button>
            </div>
            <p class="hero-note mt-2">
              यह panel browser पर local demo upload के लिए बनाया गया है।
            </p>
          </form>
        </div>

        <div class="agent-panel" id="agentPanel">
          <h3>Gallery Photo Upload</h3>
          <p class="agent-note">
            Category चुनें और photos select करें – नीचे preview में दिखेंगी (सिर्फ इस device पर)।
          </p>
          <div class="mt-2">
            <label for="galleryCategory">Category</label>
            <select id="galleryCategory">
              <option>Wedding</option>
              <option>Birthday</option>
              <option>Flower</option>
              <option>Light</option>
              <option>Band</option>
              <option>Coffee</option>
              <option>Popcorn</option>
              <option>All Events</option>
            </select>
          </div>
          <div class="mt-2">
            <label for="galleryFiles">Select Photos</label>
            <input id="galleryFiles" type="file" multiple accept="image/*" />
          </div>
          <div class="upload-preview" id="uploadPreview">
            <!-- thumbnails will appear here -->
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <div class="footer-inner">
        <span>© <span id="year"></span> Shri Ram Decoration, Sultanpur.</span>
        <span>Made for: Gaya Prasad Gupta · Contact: 79856 34050</span>
      </div>
    </div>
  </footer>

  <script>
    // Footer year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Scroll helper
    function scrollToBooking() {
      document.getElementById('booking').scrollIntoView({ behavior: 'smooth' });
    }

    // Booking form (demo only)
    document.getElementById('bookingForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('धन्यवाद! आपकी booking request (demo) submit हो गई है।\nReal booking के लिए सीधे Call या WhatsApp करें: 79856 34050');
      this.reset();
    });

    // Agent login (ID + password only JS में, page पर कहीं लिखे नहीं)
    const AGENT_ID = '7985634050';
    const AGENT_PASSWORD = 'GP@#2311';

    const agentForm = document.getElementById('agentLoginForm');
    const agentPanel = document.getElementById('agentPanel');

    agentForm.addEventListener('submit', function(e) {
      e.preventDefault();
      const id = document.getElementById('agentId').value.trim();
      const pwd = document.getElementById('agentPassword').value;

      if (id === AGENT_ID && pwd === AGENT_PASSWORD) {
        alert('Login successful! अब आप gallery में photos जोड़ सकते हैं।');
        agentPanel.style.display = 'block';
      } else {
        alert('गलत Agent ID या Password.');
      }
    });

    // Gallery upload preview (local only)
    const fileInput = document.getElementById('galleryFiles');
    const previewContainer = document.getElementById('uploadPreview');
    const categorySelect = document.getElementById('galleryCategory');
    const staticGallery = document.getElementById('static-gallery');

    fileInput.addEventListener('change', function() {
      const files = Array.from(this.files);
      previewContainer.innerHTML = '';

      if (!files.length) return;

      files.forEach(file => {
        const reader = new FileReader();
        reader.onload = function(e) {
          const div = document.createElement('div');
          div.className = 'upload-thumb';

          const img = document.createElement('img');
          img.src = e.target.result;
          img.alt = file.name;
          img.style.width = '100%';
          img.style.height = '100%';
          img.style.objectFit = 'cover';

          div.appendChild(img);
          previewContainer.appendChild(div);

          // Also clone into main gallery area
          const galleryItem = document.createElement('div');
          galleryItem.className = 'gallery-item';
          const pill = document.createElement('div');
          pill.className = 'gallery-pill';
          pill.textContent = categorySelect.value;
          const caption = document.createElement('div');
          caption.className = 'gallery-caption';
          caption.textContent = file.name + ' (local preview)';
          galleryItem.appendChild(pill);
          galleryItem.appendChild(caption);
          staticGallery.appendChild(galleryItem);
        };
        reader.readAsDataURL(file);
      });
    });
  </script>
</body>
</html>
