---
layout: default
title: MHIBX
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

:root{
  --bg:#050816;
  --card:#0f172a;
  --text:#f8fafc;
  --muted:#94a3b8;
  --primary:#38bdf8;
  --border:rgba(255,255,255,.08);
}

body{
  background:
    radial-gradient(circle at top right, rgba(56,189,248,.15), transparent 30%),
    radial-gradient(circle at bottom left, rgba(139,92,246,.12), transparent 30%),
    var(--bg);
  color:var(--text);
  font-family:'Inter',sans-serif;
}

.wrapper{
  max-width:1100px;
  margin:auto;
  padding:40px 24px;
}

.hero{
  min-height:90vh;
  display:flex;
  align-items:center;
}

.hero h1{
  font-size:clamp(3rem,10vw,7rem);
  line-height:.95;
  font-weight:800;
  letter-spacing:-3px;
  margin-bottom:24px;
}

.hero p{
  max-width:650px;
  font-size:1.2rem;
  color:var(--muted);
  line-height:1.8;
}

.badge{
  display:inline-flex;
  align-items:center;
  gap:10px;
  padding:10px 18px;
  border-radius:999px;
  border:1px solid var(--border);
  background:rgba(255,255,255,.03);
  margin-bottom:30px;
  color:var(--primary);
  font-size:.95rem;
}

.buttons{
  display:flex;
  gap:16px;
  margin-top:40px;
  flex-wrap:wrap;
}

.btn{
  padding:14px 24px;
  border-radius:14px;
  font-weight:600;
  text-decoration:none !important;
  transition:.25s;
}

.btn-primary{
  background:linear-gradient(135deg,#38bdf8,#818cf8);
  color:white !important;
}

.btn-secondary{
  border:1px solid var(--border);
  color:var(--text) !important;
  background:rgba(255,255,255,.03);
}

.btn:hover{
  transform:translateY(-3px);
}

.section{
  padding:120px 0;
}

.section-title{
  font-size:2.5rem;
  margin-bottom:20px;
  letter-spacing:-1px;
}

.section-desc{
  color:var(--muted);
  max-width:700px;
  line-height:1.9;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:24px;
  margin-top:50px;
}

.card{
  background:rgba(15,23,42,.65);
  border:1px solid var(--border);
  border-radius:24px;
  padding:28px;
  backdrop-filter:blur(10px);
  transition:.3s;
}

.card:hover{
  transform:translateY(-6px);
  border-color:rgba(56,189,248,.35);
  box-shadow:0 0 40px rgba(56,189,248,.08);
}

.card h3{
  margin-top:0;
  margin-bottom:18px;
  font-size:1.2rem;
}

.card p,
.card li{
  color:var(--muted);
}

.skills{
  display:flex;
  flex-wrap:wrap;
  gap:12px;
  margin-top:25px;
}

.skill{
  padding:10px 16px;
  background:rgba(255,255,255,.04);
  border:1px solid var(--border);
  border-radius:999px;
  font-size:.9rem;
}

.project-tag{
  display:inline-block;
  margin-bottom:14px;
  color:var(--primary);
  font-size:.9rem;
}

.contact{
  text-align:center;
  padding-bottom:120px;
}

.contact-links{
  display:flex;
  justify-content:center;
  flex-wrap:wrap;
  gap:16px;
  margin-top:35px;
}

.contact-links a{
  padding:14px 22px;
  border-radius:14px;
  border:1px solid var(--border);
  text-decoration:none !important;
  color:var(--muted) !important;
  transition:.25s;
}

.contact-links a:hover{
  border-color:var(--primary);
  color:white !important;
}

.footer{
  text-align:center;
  padding:40px 0;
  color:var(--muted);
  border-top:1px solid var(--border);
}

@media(max-width:768px){

  .hero{
    min-height:auto;
    padding-top:60px;
  }

  .section{
    padding:80px 0;
  }

  .hero p{
    font-size:1rem;
  }

}
</style>

<div class="wrapper">

<section class="hero">

<div>

<div class="badge">
⚡ IT Support • Linux • Cybersecurity
</div>

<h1>
Muhammad<br>
Hibatullah Wafi
</h1>

<p>
Building digital systems, learning cybersecurity,
and creating internet-based projects.
Focused on Linux environments, IT support,
automation, and modern digital infrastructure.
</p>

<div class="buttons">
<a class="btn btn-primary" href="#projects">View Projects</a>
<a class="btn btn-secondary" href="#contact">Contact Me</a>
</div>

</div>

</section>

<section class="section">

<h2 class="section-title">
About Me
</h2>

<p class="section-desc">
I'm a technology enthusiast passionate about IT support,
Linux systems, troubleshooting, and cybersecurity fundamentals.
I enjoy building digital projects, learning independently,
and experimenting with infrastructure, automation,
and internet-based businesses.
</p>

<div class="skills">

<div class="skill">Linux</div>
<div class="skill">IT Support</div>
<div class="skill">Networking</div>
<div class="skill">Cybersecurity</div>
<div class="skill">Cloudflare</div>
<div class="skill">GitHub</div>
<div class="skill">WordPress</div>
<div class="skill">Troubleshooting</div>

</div>

</section>

<section class="section" id="projects">

<h2 class="section-title">
Featured Projects
</h2>

<div class="grid">

<div class="card">

<div class="project-tag">
DIGITAL BUSINESS
</div>

<h3>
Insider Top Up
</h3>

<p>
A gaming top-up platform focused on automation,
fast delivery, payment systems,
and customer experience.
</p>

</div>

<div class="card">

<div class="project-tag">
PERSONAL LAB
</div>

<h3>
Learning Environment
</h3>

<p>
Self-hosted environment for Linux practice,
Git workflows, networking,
and cybersecurity experiments.
</p>

</div>

</div>

</section>

<section class="contact" id="contact">

<h2 class="section-title">
Let's Connect
</h2>

<p class="section-desc" style="margin:auto;">
Feel free to reach out for collaboration,
networking, or discussions about technology and projects.
</p>

<div class="contact-links">

<a href="https://github.com/mhibx">
GitHub
</a>

<a href="https://t.me/mwafi95">
Telegram
</a>

<a href="mailto:yourmail@example.com">
Email
</a>

</div>

</section>

<div class="footer">
© 2026 MHIBX — Built with GitHub Pages
</div>

</div>
