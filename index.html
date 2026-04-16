<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name — Backend Engineer</title>
<script src="https://unpkg.com/htmx.org@1.9.10"></script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Mono:ital,wght@0,300;0,400;0,500;1,300&family=Syne:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0a0a;
    --surface: #111111;
    --surface2: #1a1a1a;
    --border: #2a2a2a;
    --accent: #c8f542;
    --accent2: #42f5b3;
    --text: #f0ede6;
    --muted: #666;
    --font-display: 'Syne', sans-serif;
    --font-mono: 'DM Mono', monospace;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--font-mono);
    font-size: 15px;
    line-height: 1.7;
    overflow-x: hidden;
  }

  /* ── NAV ── */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.2rem 4rem;
    background: rgba(10,10,10,0.85);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
  }

  .nav-logo {
    font-family: var(--font-display);
    font-weight: 800;
    font-size: 1.1rem;
    color: var(--accent);
    letter-spacing: -0.02em;
  }

  .nav-links {
    display: flex;
    gap: 2.5rem;
    list-style: none;
  }

  .nav-links a {
    color: var(--muted);
    text-decoration: none;
    font-size: 0.8rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    transition: color 0.2s;
  }

  .nav-links a:hover { color: var(--accent); }

  /* ── HERO ── */
  #hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 8rem 4rem 4rem;
    position: relative;
    overflow: hidden;
  }

  .hero-grid-bg {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(var(--border) 1px, transparent 1px),
      linear-gradient(90deg, var(--border) 1px, transparent 1px);
    background-size: 60px 60px;
    opacity: 0.35;
    mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 30%, transparent 100%);
  }

  .hero-tag {
    font-size: 0.75rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 1.5rem;
    opacity: 0;
    animation: fadeUp 0.6s 0.2s forwards;
  }

  .hero-name {
    font-family: var(--font-display);
    font-weight: 800;
    font-size: clamp(3.5rem, 9vw, 7rem);
    line-height: 0.95;
    letter-spacing: -0.03em;
    margin-bottom: 1.5rem;
    opacity: 0;
    animation: fadeUp 0.6s 0.35s forwards;
  }

  .hero-name span { color: var(--accent); }

  .hero-desc {
    max-width: 520px;
    color: var(--muted);
    font-size: 0.95rem;
    line-height: 1.8;
    margin-bottom: 2.5rem;
    opacity: 0;
    animation: fadeUp 0.6s 0.5s forwards;
  }

  .hero-cta {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    opacity: 0;
    animation: fadeUp 0.6s 0.65s forwards;
  }

  .btn {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 0.75rem 1.5rem;
    border-radius: 2px;
    font-family: var(--font-mono);
    font-size: 0.8rem;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    text-decoration: none;
    cursor: pointer;
    transition: all 0.2s;
    border: none;
  }

  .btn-primary {
    background: var(--accent);
    color: #0a0a0a;
    font-weight: 500;
  }

  .btn-primary:hover { background: #d8ff52; transform: translateY(-1px); }

  .btn-outline {
    background: transparent;
    color: var(--text);
    border: 1px solid var(--border);
  }

  .btn-outline:hover { border-color: var(--accent); color: var(--accent); }

  .hero-scroll-hint {
    position: absolute;
    bottom: 2.5rem;
    left: 4rem;
    font-size: 0.7rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--muted);
    display: flex;
    align-items: center;
    gap: 10px;
    opacity: 0;
    animation: fadeUp 0.6s 1s forwards;
  }

  .scroll-line {
    display: block;
    width: 40px;
    height: 1px;
    background: var(--muted);
  }

  /* ── SECTION LAYOUT ── */
  section {
    padding: 6rem 4rem;
    max-width: 1100px;
    margin: 0 auto;
  }

  .section-label {
    font-size: 0.7rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 0.75rem;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .section-label::before {
    content: '';
    display: block;
    width: 24px;
    height: 1px;
    background: var(--accent);
  }

  .section-title {
    font-family: var(--font-display);
    font-size: clamp(2rem, 4vw, 3rem);
    font-weight: 700;
    letter-spacing: -0.03em;
    margin-bottom: 3rem;
    line-height: 1.1;
  }

  /* ── ABOUT ── */
  #about {
    border-top: 1px solid var(--border);
  }

  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: start;
  }

  .about-text p {
    color: var(--muted);
    margin-bottom: 1rem;
    font-size: 0.9rem;
    line-height: 1.9;
  }

  .about-text p strong {
    color: var(--text);
    font-weight: 500;
  }

  .skills-list {
    list-style: none;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 0.5rem;
  }

  .skills-list li {
    font-size: 0.8rem;
    color: var(--muted);
    padding: 0.5rem 0.75rem;
    border: 1px solid var(--border);
    border-radius: 2px;
    display: flex;
    align-items: center;
    gap: 8px;
    transition: border-color 0.2s, color 0.2s;
  }

  .skills-list li:hover { border-color: var(--accent2); color: var(--accent2); }

  .skills-list li::before {
    content: '▸';
    color: var(--accent);
    font-size: 0.65rem;
  }

  /* ── PROJECTS ── */
  #projects {
    border-top: 1px solid var(--border);
  }

  .project-filters {
    display: flex;
    gap: 0.5rem;
    margin-bottom: 2rem;
    flex-wrap: wrap;
  }

  .filter-btn {
    padding: 0.4rem 1rem;
    background: transparent;
    border: 1px solid var(--border);
    color: var(--muted);
    font-family: var(--font-mono);
    font-size: 0.75rem;
    letter-spacing: 0.06em;
    cursor: pointer;
    border-radius: 2px;
    transition: all 0.2s;
    text-transform: uppercase;
  }

  .filter-btn:hover, .filter-btn.active {
    border-color: var(--accent);
    color: var(--accent);
    background: rgba(200, 245, 66, 0.05);
  }

  .htmx-indicator {
    display: none;
    color: var(--muted);
    font-size: 0.8rem;
    padding: 2rem 0;
    letter-spacing: 0.1em;
  }

  .htmx-request .htmx-indicator { display: block; }
  .htmx-request .project-grid { opacity: 0.3; transition: opacity 0.2s; }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    transition: opacity 0.3s;
  }

  .project-card {
    background: var(--bg);
    padding: 1.75rem;
    transition: background 0.2s;
    position: relative;
    overflow: hidden;
  }

  .project-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.3s;
  }

  .project-card:hover { background: var(--surface); }
  .project-card:hover::before { transform: scaleX(1); }

  .project-tag {
    font-size: 0.65rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--accent2);
    margin-bottom: 0.75rem;
  }

  .project-title {
    font-family: var(--font-display);
    font-size: 1.2rem;
    font-weight: 600;
    margin-bottom: 0.75rem;
    color: var(--text);
  }

  .project-desc {
    font-size: 0.82rem;
    color: var(--muted);
    line-height: 1.8;
    margin-bottom: 1.25rem;
  }

  .project-tech {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-bottom: 1.25rem;
  }

  .tech-pill {
    font-size: 0.65rem;
    padding: 0.25rem 0.6rem;
    background: var(--surface2);
    color: var(--muted);
    border-radius: 2px;
    letter-spacing: 0.04em;
  }

  .project-links {
    display: flex;
    gap: 1rem;
  }

  .project-link {
    font-size: 0.75rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--muted);
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 5px;
    transition: color 0.2s;
  }

  .project-link:hover { color: var(--accent); }

  /* ── CONTACT ── */
  #contact {
    border-top: 1px solid var(--border);
    text-align: center;
  }

  #contact .section-label { justify-content: center; }
  #contact .section-label::before { display: none; }

  .contact-tagline {
    color: var(--muted);
    max-width: 420px;
    margin: 0 auto 2.5rem;
    font-size: 0.9rem;
  }

  .contact-links {
    display: flex;
    justify-content: center;
    gap: 1rem;
    flex-wrap: wrap;
  }

  /* ── FOOTER ── */
  footer {
    border-top: 1px solid var(--border);
    padding: 2rem 4rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: var(--muted);
    font-size: 0.75rem;
    letter-spacing: 0.05em;
  }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(20px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  /* ── RESPONSIVE ── */
  @media (max-width: 768px) {
    nav { padding: 1rem 1.5rem; }
    .nav-links { gap: 1.5rem; }
    #hero, section { padding-left: 1.5rem; padding-right: 1.5rem; }
    .hero-scroll-hint { left: 1.5rem; }
    .about-grid { grid-template-columns: 1fr; gap: 2rem; }
    footer { flex-direction: column; gap: 0.5rem; text-align: center; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">scoutthemutt.dev</div>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<div id="hero">
  <div class="hero-grid-bg"></div>
  <p class="hero-tag">Backend Engineer · Available for opportunities</p>
  <h1 class="hero-name">Owen<br><span>OBrien</span></h1>
  <p class="hero-desc">
    Senior CS student building robust, scalable backend systems.
    Passionate about distributed architecture, APIs, and writing
    code that other engineers actually enjoy maintaining.
  </p>
  <div class="hero-cta">
    <a href="#projects" class="btn btn-primary">View Projects</a>
    <a href="#contact" class="btn btn-outline">Get In Touch</a>
  </div>
  <span class="hero-scroll-hint">
    <span class="scroll-line"></span>
    Scroll to explore
  </span>
</div>

<!-- ABOUT -->
<section id="about">
  <p class="section-label">About me</p>
  <h2 class="section-title">Who I Am</h2>
  <div class="about-grid">
    <div class="about-text">
      <p>
        I'm a <strong>senior undergraduate student</strong> studying Computer Science,
        with a focus on system and web security. I enjoy working close to the
        infrastructure, finding vulnerabilities, and developing solutions to hard problems.
      </p>
      <p>
        When I'm not coding, I'm exploring different types of security research, and experimenting with new languages.
        I pride myself on being a strong learner and collaborator, and I'm always looking for opportunities to grow and 
        contribute to impactful projects.
      </p>
      <p>
        I'm currently looking for <strong>backend engineering internships and
        new-grad roles either with or without a focus on system security</strong>, starting in 2026.
      </p>
    </div>
    <div>
      <p class="section-label" style="margin-bottom:1rem;">Tech Stack</p>
      <ul class="skills-list">
        <li>Python</li>
        <li>Java</li>
        <li>C</li>
        <li>SQL</li>
        <li>JavaScript</li>
        <li>Bash</li>
        <li>Linux</li>
        <li>Git</li>
      </ul>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <p class="section-label">Work</p>
  <h2 class="section-title">Projects</h2>

  <!-- HTMX-powered filter buttons -->
  <div class="project-filters">
    <button class="filter-btn active"
      hx-get="/projects?filter=all"
      hx-target="#project-list"
      hx-swap="innerHTML"
      hx-indicator="#project-list"
      onclick="setActive(this)">All</button>
    <button class="filter-btn"
      hx-get="/projects?filter=api"
      hx-target="#project-list"
      hx-swap="innerHTML"
      hx-indicator="#project-list"
      onclick="setActive(this)">APIs</button>
    <button class="filter-btn"
      hx-get="/projects?filter=systems"
      hx-target="#project-list"
      hx-swap="innerHTML"
      hx-indicator="#project-list"
      onclick="setActive(this)">Systems</button>
    <button class="filter-btn"
      hx-get="/projects?filter=data"
      hx-target="#project-list"
      hx-swap="innerHTML"
      hx-indicator="#project-list"
      onclick="setActive(this)">Data</button>
  </div>

  <div id="project-list">
    <p class="htmx-indicator">Loading projects...</p>
    <div class="project-grid">

      <div class="project-card">
        <p class="project-tag">API · Systems</p>
        <h3 class="project-title">Counter Strike Player Tracking App</h3>
        <p class="project-desc">
          A web application that tracks player stats and performance in Counter Strike 2.
          The backend is built with Flask and SQLite. It scrapes data from the Steam API 
          and provides endpoints for retrieving player profiles, and match history. My 
          next update will add performance analytics.
        </p>
        <div class="project-tech">
          <span class="tech-pill">Python</span>
          <span class="tech-pill">SQLite</span>
          <span class="tech-pill">HTMX</span>
        </div>
        <div class="project-links">
          <a href="https://github.com/ScoutTheMutt/CS2-Player-Tracking-Web-App" class="project-link">↗ GitHub</a>
          <a href="#" class="project-link">↗ Demo</a>
        </div>
      </div>

      <div class="project-card">
        <p class="project-tag">Data · API</p>
        <h3 class="project-title">Project Two</h3>
        <p class="project-desc">
          Describe the purpose of this project, the scale of data involved, and what made it technically interesting or challenging to build.
        </p>
        <div class="project-tech">
          <span class="tech-pill">Python</span>
          <span class="tech-pill">Redis</span>
          <span class="tech-pill">FastAPI</span>
        </div>
        <div class="project-links">
          <a href="#" class="project-link">↗ GitHub</a>
        </div>
      </div>

      <div class="project-card">
        <p class="project-tag">Systems</p>
        <h3 class="project-title">Project Three</h3>
        <p class="project-desc">
          What system-level concepts does this project demonstrate? Concurrency, networking, file I/O? Give the reader a sense of the technical depth.
        </p>
        <div class="project-tech">
          <span class="tech-pill">C</span>
          <span class="tech-pill">Linux</span>
          <span class="tech-pill">POSIX</span>
        </div>
        <div class="project-links">
          <a href="#" class="project-link">↗ GitHub</a>
        </div>
      </div>

    </div><!-- /project-grid -->
  </div><!-- /project-list -->

</section>

<!-- CONTACT -->
<section id="contact">
  <p class="section-label">Contact</p>
  <h2 class="section-title">Let's Talk</h2>
  <p class="contact-tagline">
    Open to backend engineering internships and new-grad roles.
    Always happy to chat about interesting technical problems.
  </p>
  <div class="contact-links">
    <a href="mailto:oobrien199@gmail.com" class="btn btn-primary">Email Me</a>
    <a href="https://github.com/scoutthemutt" class="btn btn-outline" target="_blank">GitHub</a>
    <a href="https://linkedin.com/in/owenobrien2026" class="btn btn-outline" target="_blank">LinkedIn</a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <span>© 2025 Owen O'Brien</span>
  <span>Built with HTML + HTMX</span>
</footer>

<script>
  function setActive(btn) {
    document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
  }

  // Smooth scroll for nav links
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
      const target = document.querySelector(this.getAttribute('href'));
      if (target) { e.preventDefault(); target.scrollIntoView({ behavior: 'smooth' }); }
    });
  });
</script>

</body>
</html>
