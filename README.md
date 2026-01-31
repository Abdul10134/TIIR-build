<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>TIIR Build | Premier Main Contractor Somalia</title>
  
  <meta name="description" content="TIIR Build is Somalia's leading main contractor delivering civil works, fit-out, and complex construction projects to international standards." />
  <meta name="keywords" content="Construction Somalia, Main Contractor Mogadishu, Civil Works, TIIR Build, Fit-out, Infrastructure Somalia" />
  
  <style>
    :root {
      --bg: #070b14;
      --card: #0c1426;
      --muted: #9fb0d0;
      --text: #eaf0ff;
      --line: rgba(255,255,255,.08);
      --accent: #d6b15e; /* Construction Gold */
      --accent-dark: #b08d3e;
      --radius: 16px;
      --max: 1100px;
    }

    * { box-sizing: border-box; scroll-behavior: smooth; }
    
    body {
      margin: 0;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    a { color: inherit; text-decoration: none; transition: 0.2s; }
    .wrap { max-width: var(--max); margin: auto; padding: 0 24px; }

    /* Header */
    header {
      position: sticky; top: 0; z-index: 100;
      background: rgba(7, 11, 20, 0.85);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid var(--line);
    }
    .nav { display: flex; justify-content: space-between; align-items: center; padding: 18px 0; }
    .brand { display: flex; align-items: center; gap: 12px; font-weight: 800; font-size: 20px; letter-spacing: 0.5px; }
    .logo { 
      width: 34px; height: 34px; border-radius: 8px; 
      background: linear-gradient(135deg, var(--accent), var(--accent-dark)); 
    }
    .nav-links a { margin-left: 20px; font-size: 14px; color: var(--muted); font-weight: 500; }
    .nav-links a:hover { color: var(--accent); }

    /* Hero */
    .hero { padding: 100px 0 80px; text-align: left; }
    h1 { font-size: clamp(38px, 7vw, 60px); line-height: 1.1; margin: 0 0 20px; font-weight: 800; }
    .hero p { max-width: 650px; font-size: 18px; color: var(--muted); margin-bottom: 30px; }
    
    .btn {
      display: inline-block; padding: 14px 28px; border-radius: 10px;
      font-weight: 600; transition: 0.3s; cursor: pointer; border: 1px solid var(--accent);
    }
    .btn-primary { background: var(--accent); color: #070b14; }
    .btn-primary:hover { background: transparent; color: var(--accent); transform: translateY(-2px); }

    /* Sections */
    section { padding: 80px 0; border-top: 1px solid var(--line); }
    h2 { font-size: 32px; margin-bottom: 40px; color: #fff; }

    /* Grid & Cards */
    .grid {
      display: grid; gap: 20px;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    }
    .card {
      padding: 30px; border-radius: var(--radius);
      background: rgba(255, 255, 255, 0.02);
      border: 1px solid var(--line);
      transition: 0.3s;
    }
    .card:hover { border-color: var(--accent); background: rgba(255, 255, 255, 0.04); }
    .card strong { display: block; font-size: 18px; margin-bottom: 10px; color: var(--accent); }
    .card p { margin: 0; font-size: 15px; color: var(--muted); }

    /* Portfolio Tags */
    .tags { display: flex; flex-wrap: wrap; gap: 10px; }
    .tag { 
      padding: 8px 16px; border-radius: 50px; background: var(--card); 
      font-size: 13px; border: 1px solid var(--line); color: var(--text);
    }

    footer { padding: 40px 0; border-top: 1px solid var(--line); color: var(--muted); font-size: 13px; }

    @media (max-width: 768px) {
      .nav-links { display: none; }
      .hero { padding: 60px 0; }
    }
  </style>
</head>
<body>

<header>
  <div class="wrap nav">
    <div class="brand">
      <div class="logo"></div>
      TIIR BUILD
    </div>
    <nav class="nav-links">
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#sectors">Sectors</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<main>
  <section class="hero">
    <div class="wrap">
      <h1>Building Somalia<br>with Certainty and Pride.</h1>
      <p>
        TIIR Build is a next-generation Somali main contractor focused on disciplined delivery, 
        rigorous site governance, and international safety standards.
      </p>
      <a class="btn btn-primary" href="#contact">Start a Conversation</a>
    </div>
  </section>

  <section id="about">
    <div class="wrap">
      <h2>Reliability in Execution</h2>
      <p style="max-width: 800px; font-size: 18px;">
        We operate with clear accountability from mobilisation through handover. 
        By combining modern construction practices with deep local knowledge, 
        TIIR Build delivers complex projects where others see challenges.
      </p>
    </div>
  </section>

  <section id="services">
    <div class="wrap">
      <h2>Our Services</h2>
      <div class="grid">
        <div class="card">
          <strong>Main Contracting</strong>
          <p>Full project lifecycle management including cost control, quality assurance, and safety governance.</p>
        </div>
        <div class="card">
          <strong>Civil & Structural</strong>
          <p>High-specification foundations, structural concrete works, and critical infrastructure development.</p>
        </div>
        <div class="card">
          <strong>Fit-out & Interiors</strong>
          <p>Premium internal finishes for hospitality and commercial sectors with coordinated MEP interfaces.</p>
        </div>
        <div class="card">
          <strong>Procurement</strong>
          <p>Global material sourcing and international logistics managed for seamless site delivery in Somalia.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="sectors">
    <div class="wrap">
      <h2>Sectors We Serve</h2>
      <div class="tags">
        <span class="tag">Residential & Villas</span>
        <span class="tag">Hospitality & Hotels</span>
        <span class="tag">Commercial Offices</span>
        <span class="tag">Secure Facilities</span>
        <span class="tag">Healthcare & Education</span>
        <span class="tag">Infrastructure</span>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="wrap">
      <h2>Contact Us</h2>
      <div class="card" style="max-width: 500px;">
        <strong>Get in touch</strong>
        <p>Email: <a href="mailto:info@tiirbuild.com" style="color:#fff">info@tiirbuild.com</a></p>
        <p>Headquarters: Mogadishu, Somalia</p>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">
    <p>© <span id="year"></span> TIIR Build. All rights reserved. | Somalia's Premier Main Contractor</p>
  </div>
</footer>

<script>
  document.getElementById("year").textContent = new Date().getFullYear();
</script>

</body>
</html>
