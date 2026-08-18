<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bright — Simple Landing Page</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      color: #1a1a2e;
      line-height: 1.6;
    }

    /* Navigation */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 8%;
      background: #ffffff;
      position: sticky;
      top: 0;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      z-index: 10;
    }
    .logo { font-size: 1.5rem; font-weight: 700; color: #5643fd; }
    .nav-links a {
      margin-left: 28px;
      text-decoration: none;
      color: #444;
      font-weight: 500;
      transition: color 0.2s;
    }
    .nav-links a:hover { color: #5643fd; }

    /* Hero */
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 100px 8%;
      background: linear-gradient(135deg, #6e5bff 0%, #a78bfa 100%);
      color: #fff;
    }
    .hero h1 { font-size: 3rem; margin-bottom: 20px; max-width: 700px; }
    .hero p { font-size: 1.2rem; margin-bottom: 32px; max-width: 550px; opacity: 0.95; }
    .btn {
      display: inline-block;
      padding: 14px 34px;
      background: #fff;
      color: #5643fd;
      text-decoration: none;
      font-weight: 600;
      border-radius: 30px;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .btn:hover { transform: translateY(-3px); box-shadow: 0 8px 20px rgba(0,0,0,0.2); }

    /* Features */
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 30px;
      padding: 80px 8%;
      background: #f8f8fc;
    }
    .card {
      background: #fff;
      padding: 40px 30px;
      border-radius: 16px;
      text-align: center;
      box-shadow: 0 4px 20px rgba(0,0,0,0.04);
      transition: transform 0.2s;
    }
    .card:hover { transform: translateY(-6px); }
    .card .icon { font-size: 2.5rem; margin-bottom: 16px; }
    .card h3 { margin-bottom: 12px; font-size: 1.3rem; }
    .card p { color: #666; }

    /* Footer */
    footer {
      text-align: center;
      padding: 40px 8%;
      background: #1a1a2e;
      color: #cfcfe6;
    }
    footer a { color: #a78bfa; text-decoration: none; }

    @media (max-width: 600px) {
      .hero h1 { font-size: 2.1rem; }
      .nav-links { display: none; }
    }
  </style>
</head>
<body>

  <nav>
    <div class="logo">Bright</div>
    <div class="nav-links">
      #features
      #about
      #contact
    </div>
  </nav>

  <header class="hero">
    <h1>Build something people love</h1>
    <p>A clean, fast, and modern starting point for your next big idea. No clutter — just what you need to launch.</p>
    #contact
  </header>

  <section class="features" id="features">
    <div class="card">
      <div class="icon">⚡</div>
      <h3>Lightning Fast</h3>
      <p>Optimised, lightweight code that loads in the blink of an eye.</p>
    </div>
    <div class="card">
      <div class="icon">🎨</div>
      <h3>Beautiful Design</h3>
      <p>A modern, responsive layout that looks great on any device.</p>
    </div>
    <div class="card">
      <div class="icon">🔧</div>
      <h3>Easy to Customise</h3>
      <p>Simple, well-structured code you can tweak in minutes.</p>
    </div>
  </section>

  <footer id="contact">
    <p>© 2026 Bright. Made with care. — hello@bright.com</p>
  </footer>

</body>
</html>
