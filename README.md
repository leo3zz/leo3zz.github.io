<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MST Plumbing & Heating | Trusted Barnet Plumbing & Heating Experts</title>
  <meta name="description" content="MST Plumbing & Heating provides expert plumbing, heating, boiler repairs, gas services and emergency callouts across Barnet, North London & Hertfordshire."/>
  
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
      font-family: 'Montserrat', sans-serif;
    }

    body {
      background: #f7fbff;
      color: #0d1b2a;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    header {
      background: linear-gradient(135deg, #001f3f, #0077b6);
      color: white;
      padding: 20px 8%;
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 4px 20px rgba(0,0,0,0.15);
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 12px;
      font-size: 1.8rem;
      font-weight: 800;
      letter-spacing: 2px;
    }

    .logo-icon {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      background: linear-gradient(135deg, #00c6ff, #ff7b00);
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 1.4rem;
      font-weight: bold;
      color: white;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      color: white;
      font-weight: 600;
      transition: 0.3s;
    }

    nav ul li a:hover {
      color: #ffb703;
    }

    .hero {
      min-height: 95vh;
      display: flex;
      align-items: center;
      padding: 0 8%;
      background: linear-gradient(rgba(0,31,63,0.75), rgba(0,119,182,0.75)),
                  url('https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=1600&q=80') center/cover;
      color: white;
    }

    .hero-content {
      max-width: 750px;
    }

    .hero h1 {
      font-size: 4rem;
      margin-bottom: 20px;
      line-height: 1.1;
    }

    .hero p {
      font-size: 1.3rem;
      margin-bottom: 30px;
      color: #dbeafe;
    }

    .hero-buttons {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 15px 35px;
      border-radius: 50px;
      font-weight: 700;
      transition: 0.3s;
      display: inline-block;
    }

    .btn-primary {
      background: #ff7b00;
      color: white;
    }

    .btn-primary:hover {
      background: #e66900;
      transform: translateY(-3px);
    }

    .btn-secondary {
      border: 2px solid white;
      color: white;
    }

    .btn-secondary:hover {
      background: white;
      color: #001f3f;
    }

    section {
      padding: 100px 8%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 60px;
    }

    .section-title h2 {
      font-size: 2.8rem;
      color: #001f3f;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #555;
      font-size: 1.1rem;
    }

    .about {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 50px;
      align-items: center;
    }

    .about img {
      width: 100%;
      border-radius: 20px;
      box-shadow: 0 10px 35px rgba(0,0,0,0.15);
    }

    .about-text h3 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #0077b6;
    }

    .services-grid,
    .coverage-grid,
    .why-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .card {
      background: white;
      padding: 35px;
      border-radius: 20px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.08);
      transition: 0.3s;
      text-align: center;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    .card h3 {
      margin-bottom: 15px;
      color: #0077b6;
    }

    .reviews {
      background: linear-gradient(135deg, #001f3f, #003566);
      color: white;
    }

    .review-card {
      background: rgba(255,255,255,0.08);
      padding: 30px;
      border-radius: 18px;
      backdrop-filter: blur(8px);
    }

    .contact {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 50px;
    }

    form input,
    form textarea {
      width: 100%;
      padding: 15px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 10px;
    }

    form button {
      border: none;
      cursor: pointer;
    }

    footer {
      background: #001f3f;
      color: white;
      text-align: center;
      padding: 30px;
    }

    @media(max-width: 900px) {
      .hero h1 {
        font-size: 2.8rem;
      }

      nav ul {
        gap: 15px;
      }
    }

    @media(max-width: 768px) {
      header {
        flex-direction: column;
        gap: 20px;
      }

      nav ul {
        flex-wrap: wrap;
        justify-content: center;
      }

      .hero {
        text-align: center;
      }

      .hero-buttons {
        justify-content: center;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">
    <div class="logo-icon">MST</div>
    MST Plumbing & Heating
  </div>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#coverage">Areas Covered</a></li>
      <li><a href="#reviews">Reviews</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<section class="hero">
  <div class="hero-content">
    <h1>Trusted Plumbing, Heating & Gas Experts Across Barnet</h1>
    <p>Professional boiler repairs, heating installations, gas services, and emergency plumbing for homes and businesses.</p>
    
    <div class="hero-buttons">
      <a href="#contact" class="btn btn-primary">Get Free Quote</a>
      <a href="tel:+4400000000" class="btn btn-secondary">Emergency Callout</a>
    </div>
  </div>
</section>

<section id="about">
  <div class="section-title">
    <h2>About MST</h2>
    <p>Family-run specialists delivering reliable local service.</p>
  </div>

  <div class="about">
    <img src="https://images.unsplash.com/photo-1621905252507-b35492cc74b4?auto=format&fit=crop&w=800&q=80" alt="MST Team">

    <div class="about-text">
      <h3>Your Local Heating & Plumbing Specialists</h3>
      <p>MST Plumbing & Heating provides certified plumbing, heating and gas engineering services across Barnet, North London and Hertfordshire.</p>
      <br>
      <p>With years of hands-on experience, our engineers specialize in boiler installations, emergency repairs, central heating systems, gas safety, and full bathroom plumbing solutions.</p>
    </div>
  </div>
</section>

<section id="services">
  <div class="section-title">
    <h2>Our Services</h2>
    <p>Complete residential and commercial solutions.</p>
  </div>

  <div class="services-grid">
    <div class="card"><h3>Boiler Installation</h3><p>Modern energy-efficient systems professionally fitted.</p></div>
    <div class="card"><h3>Boiler Repairs</h3><p>Fast diagnosis and reliable repairs.</p></div>
    <div class="card"><h3>Emergency Plumbing</h3><p>24/7 urgent plumbing response.</p></div>
    <div class="card"><h3>Gas Safety Certificates</h3><p>Landlord and homeowner compliance.</p></div>
    <div class="card"><h3>Central Heating</h3><p>Installation, upgrades and maintenance.</p></div>
    <div class="card"><h3>Bathroom Plumbing</h3><p>Professional installations and repairs.</p></div>
  </div>
</section>

<section id="coverage">
  <div class="section-title">
    <h2>Areas We Cover</h2>
    <p>Serving North London & surrounding regions.</p>
  </div>

  <div class="coverage-grid">
    <div class="card">Barnet</div>
    <div class="card">East Barnet</div>
    <div class="card">New Barnet</div>
    <div class="card">Cockfosters</div>
    <div class="card">Southgate</div>
    <div class="card">Enfield</div>
    <div class="card">Finchley</div>
    <div class="card">Potters Bar</div>
    <div class="card">Borehamwood</div>
    <div class="card">Hertfordshire</div>
  </div>
</section>

<section>
  <div class="section-title">
    <h2>Why Choose MST?</h2>
  </div>

  <div class="why-grid">
    <div class="card"><h3>Gas Safe Registered</h3></div>
    <div class="card"><h3>Fully Insured</h3></div>
    <div class="card"><h3>Same-Day Response</h3></div>
    <div class="card"><h3>Transparent Pricing</h3></div>
    <div class="card"><h3>Trusted Local Experts</h3></div>
    <div class="card"><h3>Residential & Commercial</h3></div>
  </div>
</section>

<section id="reviews" class="reviews">
  <div class="section-title">
    <h2 style="color:white;">Customer Reviews</h2>
    <p style="color:#cbd5e1;">Trusted by local homeowners and businesses.</p>
  </div>

  <div class="services-grid">
    <div class="review-card">
      <p>"Outstanding boiler repair service — quick, professional and reliable."</p>
      <br><strong>- Local Barnet Customer</strong>
    </div>

    <div class="review-card">
      <p>"Excellent communication and fair pricing. Highly recommend MST."</p>
      <br><strong>- Hertfordshire Client</strong>
    </div>

    <div class="review-card">
      <p>"Fast emergency callout when we needed it most."</p>
      <br><strong>- North London Resident</strong>
    </div>
  </div>
</section>

<section id="contact">
  <div class="section-title">
    <h2>Contact MST</h2>
    <p>Get your free quote today.</p>
  </div>

  <div class="contact">
    <div>
      <h3>Company Details</h3>
      <p><strong>Phone:</strong> 0000 000000</p>
      <p><strong>Email:</strong> info@mstplumbingandheating.co.uk</p>
      <p><strong>Hours:</strong> Mon-Sun | Emergency Response Available</p>
      <p><strong>Location:</strong> Barnet, North London</p>
    </div>

    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <input type="tel" placeholder="Phone Number">
      <textarea rows="5" placeholder="Describe your enquiry"></textarea>
      <button class="btn btn-primary">Request Quote</button>
    </form>
  </div>
</section>

<footer>
  <p>© 2026 MST Plumbing & Heating | Professional Plumbing, Heating & Gas Services</p>
</footer>

</body>
</html>