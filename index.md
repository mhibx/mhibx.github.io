<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MHIBX | Portfolio</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    :root {
      --bg: #0f172a;
      --card: #111827;
      --primary: #38bdf8;
      --text: #f8fafc;
      --muted: #94a3b8;
      --border: rgba(255,255,255,0.08);
    }

    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to bottom, #020617, #0f172a);
      color: var(--text);
      line-height: 1.7;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
    }

    header {
      position: sticky;
      top: 0;
      backdrop-filter: blur(12px);
      background: rgba(2, 6, 23, 0.7);
      border-bottom: 1px solid var(--border);
      z-index: 100;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 0;
    }

    .logo {
      font-weight: 700;
      font-size: 1.2rem;
      color: var(--primary);
    }

    .nav-links {
      display: flex;
      gap: 1.5rem;
      font-size: 0.95rem;
      color: var(--muted);
    }

    .nav-links a:hover {
      color: var(--text);
      transition: 0.2s;
    }

    .hero {
      min-height: 90vh;
      display: flex;
      align-items: center;
    }

    .hero-content {
      max-width: 750px;
    }

    .tag {
      display: inline-block;
      padding: 0.45rem 0.9rem;
      border: 1px solid var(--border);
      border-radius: 999px;
      color: var(--primary);
      margin-bottom: 1.5rem;
      font-size: 0.9rem;
      background: rgba(56, 189, 248, 0.08);
    }

    h1 {
      font-size: 4rem;
      line-height: 1.1;
      margin-bottom: 1rem;
    }

    .hero p {
      color: var(--muted);
      font-size: 1.1rem;
      margin-bottom: 2rem;
      max-width: 650px;
    }

    .buttons {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .btn {
      padding: 0.9rem 1.4rem;
      border-radius: 12px;
      font-weight: 600;
      transition: 0.2s;
    }

    .btn-primary {
      background: var(--primary);
      color: #020617;
    }

    .btn-primary:hover {
      transform: translateY(-2px);
    }

    .btn-secondary {
      border: 1px solid var(--border);
      color: var(--text);
    }

    .btn-secondary:hover {
      background: rgba(255,255,255,0.05);
    }

    section {
      padding: 5rem 0;
    }

    .section-title {
      font-size: 2rem;
      margin-bottom: 2rem;
    }

    .about p {
      color: var(--muted);
      max-width: 800px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: rgba(17, 24, 39, 0.7);
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: 1.5rem;
      transition: 0.25s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: rgba(56, 189, 248, 0.4);
    }

    .card h3 {
      margin-bottom: 1rem;
      font-size: 1.1rem;
    }

    .card p,
    .card li {
      color: var(--muted);
      font-size: 0.95rem;
    }

    ul {
      padding-left: 1.2rem;
    }

    .project-card {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .project-title {
      font-size: 1.2rem;
      font-weight: 600;
    }

    .contact-box {
      background: rgba(17, 24, 39, 0.7);
      border: 1px solid var(--border);
      padding: 2rem;
      border-radius: 24px;
      text-align: center;
    }

    .contact-links {
      margin-top: 1.5rem;
      display: flex;
      justify-content: center;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .contact-links a {
      padding: 0.8rem 1.2rem;
      border-radius: 12px;
      border: 1px solid var(--border);
      color: var(--muted);
    }

    .contact-links a:hover {
      color: var(--text);
      border-color: var(--primary);
    }

    footer {
      padding: 2rem 0;
      text-align: center;
      color: var(--muted);
      border-top: 1px solid var(--border);
      margin-top: 3rem;
    }

    @media (max-width: 768px) {
      h1 {
        font-size: 2.7rem;
      }

      .nav-links {
        display: none;
      }

      .hero {
        padding: 3rem 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <nav>
        <div class="logo">MHIBX</div>

        <div class="nav-links">
          <a href="#about">About</a>
          <a href="#skills">Skills</a>
          <a href="#projects">Projects</a>
          <a href="#contact">Contact</a>
        </div>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <div class="hero-content">
        <div class="tag">IT Support • Linux • Cybersecurity</div>

        <h1>Muhammad Hibatullah</h1>

        <p>
          Passionate about IT support, Linux systems, troubleshooting,
          digital infrastructure, and building internet-based projects.
          Currently learning and growing in system administration and cybersecurity.
        </p>

        <div class="buttons">
          <a href="#projects" class="btn btn-primary">View Projects</a>
          <a href="#contact" class="btn btn-secondary">Contact Me</a>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="about">
    <div class="container">
      <h2 class="section-title">About Me</h2>

      <p>
        Hello! I'm Muhammad Hibatullah, a technology enthusiast focused on
        IT support, Linux environments, networking basics, and cybersecurity fundamentals.
        I enjoy learning independently and building digital systems that improve efficiency
        and user experience.
        <br><br>
        Besides technology, I also develop digital business projects including gaming top-up services
        and online-based ventures.
      </p>
    </div>
  </section>

  <section id="skills">
    <div class="container">
      <h2 class="section-title">Skills</h2>

      <div class="grid">
        <div class="card">
          <h3>Technical Skills</h3>

          <ul>
            <li>Windows & Linux Administration</li>
            <li>Basic Networking (LAN/WAN)</li>
            <li>Hardware Troubleshooting</li>
            <li>Technical Support</li>
            <li>Basic Cybersecurity</li>
          </ul>
        </div>

        <div class="card">
          <h3>Tools & Platforms</h3>

          <ul>
            <li>Ubuntu Linux</li>
            <li>Git & GitHub</li>
            <li>Cloudflare</li>
            <li>WordPress</li>
            <li>VS Code</li>
          </ul>
        </div>

        <div class="card">
          <h3>Soft Skills</h3>

          <ul>
            <li>Problem Solving</li>
            <li>Communication</li>
            <li>Analytical Thinking</li>
            <li>Fast Learner</li>
            <li>Documentation</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2 class="section-title">Projects</h2>

      <div class="grid">
        <div class="card project-card">
          <div class="project-title">Insider Top Up</div>

          <p>
            A digital gaming top-up platform focused on automation,
            fast delivery, and customer experience.
          </p>
        </div>

        <div class="card project-card">
          <div class="project-title">Personal Learning Lab</div>

          <p>
            Self-hosted learning environment for Linux setup,
            networking practice, Git workflows, and security testing.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <div class="contact-box">
        <h2 class="section-title">Contact Me</h2>

        <p>
          Feel free to reach out for collaboration, networking, or discussion.
        </p>

        <div class="contact-links">
          <a href="https://github.com/mhibx" target="_blank">GitHub</a>
          <a href="https://t.me/mwafi95" target="_blank">Telegram</a>
          <a href="mailto:yourmail@example.com">Email</a>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      © 2026 Muhammad Hibatullah — Built with GitHub Pages
    </div>
  </footer>

</body>
</html>
