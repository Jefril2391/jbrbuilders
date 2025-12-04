<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>JBR Builders | Construction, Interior & Real Estate – Kodaikanal</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="JBR Builders offers construction, interior work and real estate services in and around Kodaikanal. Call 9894649900 / 8754608815 for enquiries." />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.6;
      color: #222;
      background: #f5f5f5;
    }
    a { text-decoration: none; color: inherit; }
    header {
      position: sticky;
      top: 0;
      z-index: 100;
      background: #ffffffdd;
      backdrop-filter: blur(8px);
      border-bottom: 1px solid #eee;
    }
    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0 16px;
    }
    .nav {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 12px 0;
    }
    .logo {
      font-weight: 700;
      font-size: 1.1rem;
    }
    .logo span {
      display: block;
      font-size: 0.8rem;
      font-weight: 500;
      color: #666;
    }
    .nav-links {
      display: flex;
      gap: 16px;
      font-size: 0.9rem;
    }
    .nav-links a {
      padding: 6px 10px;
      border-radius: 999px;
    }
    .nav-links a:hover {
      background: #eee;
    }
    .btn-primary, .btn-outline {
      display: inline-block;
      padding: 10px 20px;
      border-radius: 999px;
      font-weight: 600;
      font-size: 0.95rem;
      border: none;
      cursor: pointer;
    }
    .btn-primary {
      background: #1e88e5;
      color: #fff;
    }
    .btn-primary:hover {
      opacity: 0.9;
    }
    .btn-outline {
      border: 1px solid #1e88e5;
      color: #1e88e5;
      background: transparent;
    }
    .btn-outline:hover {
      background: #e3f2fd;
    }
    /* Hero */
    #hero {
      background: linear-gradient(135deg, #0d47a1, #1976d2);
      color: #fff;
      padding: 60px 0 50px;
    }
    .hero-grid {
      display: grid;
      grid-template-columns: 1.2fr 1fr;
      gap: 32px;
      align-items: center;
    }
    .hero-title {
      font-size: 2rem;
      font-weight: 700;
      margin-bottom: 12px;
    }
    .hero-subtitle {
      font-size: 1rem;
      margin-bottom: 16px;
      max-width: 500px;
    }
    .hero-tags {
      margin-bottom: 16px;
      font-size: 0.9rem;
      opacity: 0.95;
    }
    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-bottom: 16px;
    }
    .hero-contact {
      font-size: 0.9rem;
      opacity: 0.9;
    }
    .hero-card {
      background: #ffffff11;
      border-radius: 12px;
      padding: 16px;
      border: 1px solid #ffffff33;
      font-size: 0.9rem;
    }
    .hero-card h3 {
      font-size: 1rem;
      margin-bottom: 8px;
    }
    .hero-list {
      list-style: none;
    }
    .hero-list li::before {
      content: "• ";
    }
    /* Sections */
    section {
      padding: 48px 0;
      background: #fff;
    }
    section:nth-of-type(even) {
      background: #f9fafb;
    }
    .section-title {
      font-size: 1.4rem;
      margin-bottom: 8px;
    }
    .section-subtitle {
      font-size: 0.95rem;
      color: #666;
      margin-bottom: 24px;
    }
    .grid-3 {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }
    .card {
      background: #fff;
      border-radius: 12px;
      padding: 16px;
      border: 1px solid #eee;
      box-shadow: 0 1px 2px rgba(0,0,0,0.03);
      font-size: 0.9rem;
    }
    .card h3 {
      margin-bottom: 8px;
      font-size: 1rem;
    }
    .card ul {
      list-style: disc;
      padding-left: 18px;
      margin-top: 6px;
    }
    .pill-row {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 8px;
    }
    .pill {
      font-size: 0.8rem;
      padding: 4px 10px;
      border-radius: 999px;
      background: #e3f2fd;
      color: #0d47a1;
    }
    .two-col {
      display: grid;
      grid-template-columns: 1.2fr 1fr;
      gap: 24px;
    }
    /* Contact */
    .contact-grid {
      display: grid;
      grid-template-columns: 1.1fr 1fr;
      gap: 24px;
    }
    form {
      background: #fff;
      border-radius: 12px;
      padding: 16px;
      border: 1px solid #eee;
      box-shadow: 0 1px 2px rgba(0,0,0,0.03);
    }
    label {
      display: block;
      font-size: 0.85rem;
      margin-bottom: 4px;
      color: #444;
    }
    input, select, textarea {
      width: 100%;
      padding: 8px 10px;
      margin-bottom: 12px;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 0.9rem;
      font-family: inherit;
    }
    textarea {
      resize: vertical;
      min-height: 80px;
    }
    footer {
      padding: 20px 0 24px;
      background: #111827;
      color: #e5e7eb;
      font-size: 0.85rem;
    }
    .footer-top {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
      justify-content: space-between;
      margin-bottom: 8px;
    }
    .footer-links {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }
    .footer-links a {
      opacity: 0.9;
    }
    .footer-links a:hover {
      text-decoration: underline;
    }
    @media (max-width: 800px) {
      .hero-grid, .two-col, .contact-grid {
        grid-template-columns: 1fr;
      }
      .grid-3 {
        grid-template-columns: 1fr;
      }
      .nav-links {
        display: none;
      }
      #hero {
        padding-top: 40px;
      }
      .hero-title {
        font-size: 1.6rem;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="container nav">
    <div class="logo">
      JBR Builders
      <span>Construction • Interiors • Real Estate – Kodaikanal</span>
    </div>
    <nav class="nav-links">
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#projects">Work</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<section id="hero">
  <div class="container hero-grid">
    <div>
      <h1 class="hero-title">Build, Design & Discover – With JBR Builders</h1>
      <p class="hero-subtitle">
        Construction, interiors and real estate services in and around Kodaikanal. 
        From planning to handover, we handle everything under one roof.
      </p>
      <p class="hero-tags">
        Residential & Commercial Construction • Interior Work • Property / Land Deals
      </p>
      <div class="hero-actions">
        <a href="tel:+919894649900" class="btn-primary">Call: 98946 49900</a>
        <a href="tel:+918754608815" class="btn-outline">Call: 87546 08815</a>
        <a href="https://wa.me/919894649900" class="btn-outline">WhatsApp Us</a>
      </div>
      <p class="hero-contact">
        📍 Based in Kodaikanal • Serving nearby areas as well
      </p>
    </div>
    <div class="hero-card">
      <h3>Our Core Services</h3>
      <ul class="hero-list">
        <li>House & building construction</li>
        <li>Complete interior solutions</li>
        <li>Buy / Sell / Rent properties</li>
        <li>Land & plot sales around Kodaikanal</li>
      </ul>
    </div>
  </div>
</section>

<section id="about">
  <div class="container two-col">
    <div>
      <h2 class="section-title">About JBR Builders</h2>
      <p class="section-subtitle">
        Construction • Interior Work • Real Estate – All under one roof in Kodaikanal.
      </p>
      <p>
        JBR Builders is a Kodaikanal-based company offering end-to-end solutions for 
        construction, interior design and real estate. We focus on quality workmanship, 
        clear timelines and transparent communication so that every client enjoys a 
        smooth experience from first discussion to key handover.
      </p>
      <p>
        Whether you want to build a new home, upgrade your interiors or find the right 
        property or land around Kodaikanal, our team is here to guide you at each step.
      </p>
    </div>
    <div class="card">
      <h3>Why Clients Trust Us</h3>
      <ul>
        <li>Local experience in and around Kodaikanal</li>
        <li>Single team for construction, interiors & property</li>
        <li>Transparent pricing – no hidden charges</li>
        <li>Support throughout the project</li>
      </ul>
    </div>
  </div>
</section>

<section id="services">
  <div class="container">
    <h2 class="section-title">Our Services</h2>
    <p class="section-subtitle">
      One team for building, designing and finding your space.
    </p>

    <div class="grid-3">
      <div class="card">
        <h3>Construction</h3>
        <p>
          Complete residential and commercial building solutions – from foundation 
          to finishing.
        </p>
        <ul>
          <li>New house construction</li>
          <li>Commercial & rental buildings</li>
          <li>Renovation & extension work</li>
          <li>Turnkey projects</li>
        </ul>
      </div>

      <div class="card">
        <h3>Interior Work</h3>
        <p>
          Practical and modern interiors planned to fit your space and budget.
        </p>
        <ul>
          <li>Modular kitchen</li>
          <li>Living & bedroom interiors</li>
          <li>Wardrobes & TV units</li>
          <li>False ceiling & lighting</li>
        </ul>
      </div>

      <div class="card">
        <h3>Real Estate</h3>
        <p>
          Property assistance in and around Kodaikanal for end users and investors.
        </p>
        <ul>
          <li>Buy / Sell / Rent houses & flats</li>
          <li>Land & plot sales</li>
          <li>Site visits & basic guidance</li>
          <li>Support with documentation (basic)</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="projects">
  <div class="container">
    <h2 class="section-title">Recent Work</h2>
    <p class="section-subtitle">
      A quick look at the kind of projects we handle.
    </p>

    <div class="grid-3">
      <div class="card">
        <h3>Residential House – Kodaikanal</h3>
        <p>
          G+1 house with modern elevation, well-planned rooms and quality finishing.
        </p>
        <div class="pill-row">
          <span class="pill">Construction</span>
          <span class="pill">Residential</span>
        </div>
      </div>
      <div class="card">
        <h3>3BHK Interior Fit-out</h3>
        <p>
          Modular kitchen, wardrobes, TV unit, false ceiling and lighting with 
          a clean, modern look.
        </p>
        <div class="pill-row">
          <span class="pill">Interior Work</span>
        </div>
      </div>
      <div class="card">
        <h3>Land & Plot Deals</h3>
        <p>
          Assisted multiple clients in finding legally verified plots around Kodaikanal.
        </p>
        <div class="pill-row">
          <span class="pill">Real Estate</span>
          <span class="pill">Plots</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="contact">
  <div class="container contact-grid">
    <div>
      <h2 class="section-title">Let’s Discuss Your Requirement</h2>
      <p class="section-subtitle">
        Share a few details about your need – construction, interiors or property – 
        and we’ll get back to you.
      </p>
      <p><strong>Engineer:</strong> Bezil Angelan R</p>
      <p><strong>Manager:</strong> Ravi Sebastian</p>
      <p><strong>Phone / WhatsApp:</strong> 98946 49900, 87546 08815</p>
      <p><strong>Location:</strong> Kodaikanal</p>
      <p style="margin-top:8px;">
        You can also directly call or message us on WhatsApp for a quick discussion.
      </p>
      <div style="margin-top:16px;">
        <a href="tel:+919894649900" class="btn-primary">Call Now</a>
        <a href="https://wa.me/919894649900" class="btn-outline">WhatsApp Now</a>
      </div>
    </div>

    <form>
      <!-- For now this is a static form. A developer can connect it to email or backend. -->
      <label for="name">Name</label>
      <input id="name" name="name" type="text" placeholder="Your name" required />

      <label for="phone">Phone</label>
      <input id="phone" name="phone" type="tel" placeholder="Your phone number" required />

      <label for="service">Service Required</label>
      <select id="service" name="service">
        <option>Construction</option>
        <option>Interior Work</option>
        <option>Real Estate</option>
        <option>Others</option>
      </select>

      <label for="message">Message</label>
      <textarea id="message" name="message" placeholder="Tell us about your requirement"></textarea>

      <button type="submit" class="btn-primary">Submit Enquiry</button>
    </form>
  </div>
</section>

<footer>
  <div class="container">
    <div class="footer-top">
      <div>
        <strong>JBR Builders</strong><br />
        Construction • Interiors • Real Estate – Kodaikanal
      </div>
      <div class="footer-links">
        <a href="tel:+919894649900">📞 98946 49900</a>
        <a href="tel:+918754608815">📞 87546 08815</a>
        <a href="https://wa.me/919894649900">💬 WhatsApp</a>
      </div>
    </div>
    <div>
      © <span id="year"></span> JBR Builders. All rights reserved.
    </div>
  </div>
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</footer>

</body>
</html>
