<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tino Ha</title>
  <style>
    /* Reset & Base */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background: white;
      color: #000;
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* Neon Blue Gradient */
    :root {
      --neon-blue-start: #00f7ff;
      --neon-blue-end: #0066ff;
      --neon-gradient: linear-gradient(135deg, var(--neon-blue-start), var(--neon-blue-end));
    }

    /* Hero */
    .hero {
      padding: 80px 5%;
      text-align: center;
      background: white;
    }
    .logo {
      width: 48px;
      height: 48px;
      margin-bottom: 24px;
      /* Thay bằng đường dẫn logo PNG của bạn */
      background: url('your-logo-blue.png') center/contain no-repeat;
    }
    h1 {
      font-size: 2.8rem;
      font-weight: 800;
      margin-bottom: 12px;
      background: var(--neon-gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }
    .subtitle {
      font-size: 1.2rem;
      color: #333;
      margin-bottom: 32px;
    }
    .cta-button {
      display: inline-block;
      padding: 12px 28px;
      background: var(--neon-gradient);
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 600;
      transition: opacity 0.3s;
    }
    .cta-button:hover { opacity: 0.9; }

    /* Section */
    .section {
      padding: 60px 5%;
      max-width: 800px;
      margin: 0 auto;
    }
    .section h2 {
      font-size: 1.8rem;
      margin-bottom: 24px;
      color: #000;
    }
    .about p {
      font-size: 1.1rem;
      color: #444;
    }

    /* Projects Grid */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 24px;
      margin-top: 20px;
    }
    .project-card {
      background: #f9f9f9;
      border-radius: 12px;
      padding: 20px;
      text-align: center;
      transition: transform 0.2s;
    }
    .project-card:hover { transform: translateY(-4px); }
    .project-card img {
      width: 100%;
      height: 128px;
      object-fit: contain;
      margin-bottom: 12px;
    }

    /* Icons Strip */
    .icons-strip {
      display: flex;
      justify-content: center;
      gap: 24px;
      padding: 40px 5%;
      background: #f5faff;
    }
    .icon-item {
      width: 64px;
      height: 64px;
    }

    /* Footer */
    .footer {
      text-align: center;
      padding: 40px 5%;
      color: #666;
      font-size: 0.95rem;
      border-top: 1px solid #eee;
    }
    .footer a {
      color: #0066ff;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <!-- Hero -->
  <div class="hero">
    <div class="logo"></div>
    <h1>Tino Ha</h1>
    <p class="subtitle">Creator × Researcher | AI × Blockchain</p>
    <a href="https://x.com/Haust" class="cta-button">Follow on X</a>
  </div>

  <!-- About -->
  <div class="section about">
    <h2>About</h2>
    <p>I build at the intersection of artificial intelligence and decentralized systems — where creativity meets verifiable truth.</p>
  </div>

  <!-- Projects -->
  <div class="section">
    <h2>Featured Work</h2>
    <div class="projects">
      <div class="project-card">
        <img src="project1.png" alt="Endless Dev">
        <h3>Endless Dev</h3>
        <p>Unlearning in Web3</p>
      </div>
      <div class="project-card">
        <img src="project2.png" alt="Spicenet">
        <h3>Spicenet</h3>
        <p>DeFi Explainer</p>
      </div>
      <div class="project-card">
        <img src="project3.png" alt="ChainOpera">
        <h3>ChainOpera AI</h3>
        <p>Creative Review</p>
      </div>
    </div>
  </div>

  <!-- Icons Strip -->
  <div class="icons-strip">
    <img class="icon-item" src="icon-ai.png" alt="AI">
    <img class="icon-item" src="icon-chain.png" alt="Blockchain">
    <img class="icon-item" src="icon-mask.png" alt="Privacy">
    <img class="icon-item" src="icon-orchestra.png" alt="Orchestration">
    <img class="icon-item" src="icon-zkp.png" alt="ZKP">
  </div>

  <!-- Footer -->
  <div class="footer">
    <p>Email: <a href="mailto:duchth1993@gmail.com">duchth1993@gmail.com</a></p>
    <p>X: <a href="https://x.com/ducpickbigwin">@ducpickbigwin</a></p>
    <p>Made with AI Studio · 2026</p>
  </div>
</body>
</html>
