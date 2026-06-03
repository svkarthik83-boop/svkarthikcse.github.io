<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>S.V. Karthik — Assistant Professor, CSE</title>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,700;1,9..144,400&family=DM+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --purple: #7F77DD; --purple-light: #EEEDFE; --purple-dark: #3C3489;
    --teal: #1D9E75; --teal-light: #E1F5EE;
    --coral: #D85A30; --coral-light: #FAECE7;
    --amber: #BA7517; --amber-light: #FAEEDA;
    --pink: #D4537E; --pink-light: #FBEAF0;
    --blue: #378ADD; --blue-light: #E6F1FB;
    --green: #639922; --green-light: #EAF3DE;
    --bg: #FAFAF8; --card: #FFFFFF;
    --text: #1a1a1a; --text-muted: #6b6b6b; --border: rgba(0,0,0,0.08);
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: 'DM Sans', sans-serif; background: var(--bg); color: var(--text); overflow-x: hidden; }

  /* NAV */
  nav { position: fixed; top: 0; left: 0; right: 0; z-index: 100; display: flex; align-items: center; justify-content: space-between; padding: 1rem 3rem; background: rgba(250,250,248,0.88); backdrop-filter: blur(12px); border-bottom: 1px solid var(--border); }
  .nav-logo { font-family: 'Fraunces', serif; font-size: 1.3rem; font-weight: 700; color: var(--purple-dark); letter-spacing: -0.5px; }
  .nav-links { display: flex; gap: 1.8rem; list-style: none; }
  .nav-links a { text-decoration: none; font-size: 0.88rem; font-weight: 500; color: var(--text-muted); transition: color 0.2s; }
  .nav-links a:hover { color: var(--purple); }

  /* HERO */
  #hero { min-height: 100vh; display: flex; align-items: center; padding: 8rem 3rem 4rem; position: relative; overflow: hidden; }
  .hero-blobs { position: absolute; inset: 0; pointer-events: none; z-index: 0; }
  .blob { position: absolute; border-radius: 50%; filter: blur(80px); opacity: 0.35; animation: float 8s ease-in-out infinite; }
  .blob-1 { width: 480px; height: 480px; background: #AFA9EC; top: -80px; right: -80px; animation-delay: 0s; }
  .blob-2 { width: 360px; height: 360px; background: #5DCAA5; bottom: 0; left: 30%; animation-delay: -3s; }
  .blob-3 { width: 280px; height: 280px; background: #FAC775; top: 40%; left: -60px; animation-delay: -5s; }
  @keyframes float { 0%,100%{transform:translate(0,0) scale(1);} 33%{transform:translate(20px,-30px) scale(1.03);} 66%{transform:translate(-15px,15px) scale(0.97);} }
  .hero-content { position: relative; z-index: 1; max-width: 700px; }
  .hero-badge { display: inline-flex; align-items: center; gap: 6px; background: var(--teal-light); color: #0F6E56; font-size: 0.82rem; font-weight: 600; padding: 6px 14px; border-radius: 999px; margin-bottom: 1.5rem; }
  .hero-badge span { display: inline-block; width: 7px; height: 7px; border-radius: 50%; background: var(--teal); animation: pulse 2s ease infinite; }
  @keyframes pulse { 0%,100%{opacity:1;transform:scale(1);} 50%{opacity:0.5;transform:scale(1.3);} }
  h1.hero-title { font-family: 'Fraunces', serif; font-size: clamp(2.8rem, 6vw, 4.5rem); font-weight: 700; line-height: 1.08; letter-spacing: -1.5px; margin-bottom: 1.25rem; }
  h1.hero-title em { font-style: italic; font-weight: 300; color: var(--purple); }
  .hero-sub { font-size: 1.1rem; color: var(--text-muted); line-height: 1.7; max-width: 560px; margin-bottom: 2.2rem; }
  .hero-actions { display: flex; gap: 1rem; flex-wrap: wrap; }
  .btn-primary { background: var(--purple-dark); color: #fff; padding: 0.75rem 1.75rem; border-radius: 999px; font-size: 0.95rem; font-weight: 600; text-decoration: none; transition: background 0.2s, transform 0.15s; }
  .btn-primary:hover { background: var(--purple); transform: translateY(-1px); }
  .btn-outline { border: 1.5px solid var(--border); color: var(--text); padding: 0.75rem 1.75rem; border-radius: 999px; font-size: 0.95rem; font-weight: 600; text-decoration: none; background: transparent; transition: background 0.2s, border-color 0.2s; }
  .btn-outline:hover { background: var(--purple-light); border-color: var(--purple); }
  .hero-stats { display: flex; gap: 2.5rem; margin-top: 3rem; flex-wrap: wrap; }
  .stat-item { display: flex; flex-direction: column; }
  .stat-num { font-family: 'Fraunces', serif; font-size: 2rem; font-weight: 700; line-height: 1; }
  .stat-label { font-size: 0.82rem; color: var(--text-muted); margin-top: 3px; }

  /* SECTION */
  section { padding: 5rem 3rem; }
  .section-tag { display: inline-flex; align-items: center; gap: 6px; font-size: 0.78rem; font-weight: 600; letter-spacing: 1.2px; text-transform: uppercase; color: var(--text-muted); margin-bottom: 0.6rem; }
  .section-tag::before { content: ''; display: block; width: 18px; height: 2px; background: currentColor; }
  h2.section-title { font-family: 'Fraunces', serif; font-size: clamp(2rem, 4vw, 3rem); font-weight: 700; letter-spacing: -1px; line-height: 1.1; margin-bottom: 0.5rem; }
  .section-desc { font-size: 1.05rem; color: var(--text-muted); max-width: 560px; line-height: 1.7; margin-bottom: 3rem; }

  /* ABOUT */
  #about { background: var(--card); }
  .about-grid { display: grid; grid-template-columns: 1fr 1.4fr; gap: 4rem; align-items: start; max-width: 1100px; }
  .about-img-wrap { position: relative; }
  .about-img-placeholder { width: 100%; aspect-ratio: 4/5; border-radius: 24px; background: linear-gradient(135deg, var(--purple-light) 0%, var(--teal-light) 100%); display: flex; align-items: center; justify-content: center; font-family: 'Fraunces', serif; font-size: 5rem; font-weight: 700; color: var(--purple-dark); overflow: hidden; position: relative; }
  .about-img-placeholder::after { content: ''; position: absolute; inset: 0; background: radial-gradient(ellipse at 70% 20%, rgba(255,255,255,0.4) 0%, transparent 60%); }
  .about-sticker { position: absolute; padding: 10px 16px; border-radius: 14px; font-size: 0.8rem; font-weight: 600; box-shadow: 0 4px 24px rgba(0,0,0,0.1); }
  .sticker-1 { background: var(--amber-light); color: #633806; bottom: 1.5rem; left: -1.5rem; transform: rotate(-4deg); }
  .sticker-2 { background: var(--coral-light); color: #4A1B0C; top: 1.5rem; right: -1.5rem; transform: rotate(3deg); }
  .about-text p { font-size: 1.05rem; line-height: 1.8; color: var(--text-muted); margin-bottom: 1rem; }
  .about-text p strong { color: var(--text); font-weight: 600; }
  .roles-list { margin-top: 1.2rem; display: flex; flex-direction: column; gap: 6px; }
  .role-item { display: flex; align-items: center; gap: 8px; font-size: 0.9rem; color: var(--text-muted); }
  .role-dot { width: 6px; height: 6px; border-radius: 50%; flex-shrink: 0; }
  .interest-tags { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 1.5rem; }
  .tag { padding: 6px 14px; border-radius: 999px; font-size: 0.82rem; font-weight: 600; }

  /* SKILLS */
  #skills { background: var(--bg); }
  .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; max-width: 1100px; }
  .skill-card { background: var(--card); border: 1px solid var(--border); border-radius: 18px; padding: 1.5rem; transition: transform 0.2s, box-shadow 0.2s; }
  .skill-card:hover { transform: translateY(-4px); box-shadow: 0 12px 32px rgba(0,0,0,0.07); }
  .skill-icon { width: 46px; height: 46px; border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 1.3rem; margin-bottom: 1rem; }
  .skill-card h3 { font-size: 0.95rem; font-weight: 600; margin-bottom: 0.35rem; }
  .skill-card p { font-size: 0.82rem; color: var(--text-muted); line-height: 1.5; }

  /* PROJECTS & PUBS */
  #projects { background: var(--card); }
  .projects-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; max-width: 1100px; }
  .project-card { border-radius: 20px; overflow: hidden; border: 1px solid var(--border); background: var(--bg); transition: transform 0.2s, box-shadow 0.2s; display: flex; flex-direction: column; }
  .project-card:hover { transform: translateY(-5px); box-shadow: 0 16px 40px rgba(0,0,0,0.09); }
  .project-header { padding: 2rem; display: flex; align-items: flex-start; justify-content: space-between; gap: 1rem; }
  .project-emoji { font-size: 2.2rem; }
  .project-type { font-size: 0.75rem; font-weight: 600; letter-spacing: 0.5px; padding: 4px 10px; border-radius: 999px; }
  .project-body { padding: 0 2rem 2rem; flex: 1; }
  .project-body h3 { font-family: 'Fraunces', serif; font-size: 1.2rem; font-weight: 700; margin-bottom: 0.5rem; letter-spacing: -0.3px; }
  .project-body p { font-size: 0.9rem; color: var(--text-muted); line-height: 1.65; margin-bottom: 1.2rem; }
  .project-tags { display: flex; flex-wrap: wrap; gap: 6px; }
  .project-tag { font-size: 0.75rem; font-weight: 500; padding: 3px 10px; border-radius: 999px; background: var(--card); border: 1px solid var(--border); color: var(--text-muted); }
  .pub-list { display: flex; flex-direction: column; gap: 1rem; max-width: 1100px; }
  .pub-item { background: var(--bg); border: 1px solid var(--border); border-radius: 16px; padding: 1.25rem 1.5rem; display: flex; gap: 1.5rem; align-items: flex-start; transition: transform 0.2s; }
  .pub-item:hover { transform: translateX(4px); }
  .pub-year { font-family: 'Fraunces', serif; font-size: 1.4rem; font-weight: 700; color: var(--purple); min-width: 50px; line-height: 1; padding-top: 2px; }
  .pub-content h4 { font-size: 0.92rem; font-weight: 600; margin-bottom: 0.25rem; line-height: 1.4; }
  .pub-content p { font-size: 0.82rem; color: var(--text-muted); }
  .pub-venue { display: inline-block; margin-top: 0.4rem; font-size: 0.75rem; font-weight: 600; padding: 3px 10px; border-radius: 999px; }

  /* FDP / EVENTS */
  #activities { background: var(--bg); }
  .activities-tabs { display: flex; gap: 8px; margin-bottom: 2rem; flex-wrap: wrap; }
  .tab-btn { padding: 8px 18px; border-radius: 999px; border: 1.5px solid var(--border); background: transparent; font-family: 'DM Sans', sans-serif; font-size: 0.85rem; font-weight: 600; color: var(--text-muted); cursor: pointer; transition: all 0.2s; }
  .tab-btn.active { background: var(--purple-dark); color: #fff; border-color: var(--purple-dark); }
  .tab-btn:hover:not(.active) { border-color: var(--purple); color: var(--purple); }
  .tab-panel { display: none; }
  .tab-panel.active { display: block; }
  .event-list { display: flex; flex-direction: column; gap: 10px; max-width: 1100px; }
  .event-item { background: var(--card); border: 1px solid var(--border); border-radius: 14px; padding: 1rem 1.25rem; display: flex; justify-content: space-between; align-items: flex-start; gap: 1rem; transition: transform 0.18s; }
  .event-item:hover { transform: translateX(4px); }
  .event-title { font-size: 0.9rem; font-weight: 600; margin-bottom: 3px; }
  .event-venue { font-size: 0.8rem; color: var(--text-muted); }
  .event-date { font-size: 0.78rem; font-weight: 600; padding: 4px 10px; border-radius: 999px; white-space: nowrap; flex-shrink: 0; }

  /* RESULTS */
  #results { background: var(--card); }
  .results-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1rem; max-width: 1100px; }
  .result-card { border-radius: 18px; padding: 1.5rem; text-align: center; }
  .result-pct { font-family: 'Fraunces', serif; font-size: 2.5rem; font-weight: 700; line-height: 1; margin-bottom: 0.5rem; }
  .result-subject { font-size: 0.82rem; font-weight: 600; margin-bottom: 4px; }
  .result-meta { font-size: 0.75rem; color: var(--text-muted); }

  /* TESTIMONIALS */
  #testimonials { background: var(--purple-dark); color: #fff; }
  #testimonials .section-tag { color: rgba(255,255,255,0.55); }
  #testimonials .section-tag::before { background: rgba(255,255,255,0.55); }
  #testimonials h2.section-title { color: #fff; }
  #testimonials .section-desc { color: rgba(255,255,255,0.65); }
  .testimonials-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.25rem; max-width: 1100px; }
  .testimonial-card { background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.15); border-radius: 20px; padding: 1.75rem; }
  .testimonial-quote { font-family: 'Fraunces', serif; font-size: 2.5rem; color: #AFA9EC; line-height: 0.5; margin-bottom: 1rem; }
  .testimonial-card p { font-size: 0.95rem; line-height: 1.7; color: rgba(255,255,255,0.85); margin-bottom: 1.5rem; }
  .testimonial-author { display: flex; align-items: center; gap: 12px; }
  .author-avatar { width: 38px; height: 38px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 0.85rem; font-weight: 600; flex-shrink: 0; }
  .author-info p { font-size: 0.88rem; font-weight: 600; color: #fff; }
  .author-info span { font-size: 0.78rem; color: rgba(255,255,255,0.55); }

  /* CONTACT */
  #contact { background: var(--bg); }
  .contact-wrapper { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; max-width: 1100px; align-items: start; }
  .contact-info { display: flex; flex-direction: column; gap: 1.25rem; }
  .contact-link { display: flex; align-items: center; gap: 14px; padding: 1rem 1.25rem; background: var(--card); border: 1px solid var(--border); border-radius: 16px; text-decoration: none; color: var(--text); transition: transform 0.2s, box-shadow 0.2s; }
  .contact-link:hover { transform: translateX(4px); box-shadow: 0 8px 24px rgba(0,0,0,0.06); }
  .contact-icon { width: 40px; height: 40px; border-radius: 10px; display: flex; align-items: center; justify-content: center; font-size: 1.1rem; flex-shrink: 0; }
  .contact-link-info p { font-size: 0.88rem; font-weight: 600; }
  .contact-link-info span { font-size: 0.8rem; color: var(--text-muted); }
  .contact-form { display: flex; flex-direction: column; gap: 1rem; }
  .form-group { display: flex; flex-direction: column; gap: 6px; }
  .form-group label { font-size: 0.85rem; font-weight: 600; color: var(--text-muted); }
  .form-group input, .form-group textarea { padding: 0.75rem 1rem; border: 1.5px solid var(--border); border-radius: 12px; font-family: 'DM Sans', sans-serif; font-size: 0.95rem; background: var(--card); color: var(--text); transition: border-color 0.2s; resize: vertical; outline: none; }
  .form-group input:focus, .form-group textarea:focus { border-color: var(--purple); }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
  .form-submit { background: var(--purple-dark); color: #fff; border: none; padding: 0.85rem 2rem; border-radius: 999px; font-family: 'DM Sans', sans-serif; font-size: 0.95rem; font-weight: 600; cursor: pointer; transition: background 0.2s, transform 0.15s; align-self: flex-start; }
  .form-submit:hover { background: var(--purple); transform: translateY(-1px); }

  footer { background: var(--text); color: rgba(255,255,255,0.5); padding: 2rem 3rem; display: flex; justify-content: space-between; align-items: center; font-size: 0.85rem; }
  footer span { color: rgba(255,255,255,0.9); font-family: 'Fraunces', serif; font-weight: 700; font-size: 1rem; }

  .reveal { opacity: 0; transform: translateY(30px); transition: opacity 0.6s ease, transform 0.6s ease; }
  .reveal.visible { opacity: 1; transform: none; }

  @media (max-width: 768px) {
    nav { padding: 1rem 1.5rem; }
    .nav-links { display: none; }
    section { padding: 4rem 1.5rem; }
    #hero { padding: 7rem 1.5rem 3rem; }
    .about-grid, .contact-wrapper { grid-template-columns: 1fr; gap: 2rem; }
    .form-row { grid-template-columns: 1fr; }
    footer { flex-direction: column; gap: 0.5rem; text-align: center; }
  }
</style>
</head>
<body>

<nav>
  <div class="nav-logo">S.V. Karthik</div>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Publications</a></li>
    <li><a href="#activities">Activities</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <a href="#contact" class="btn-primary" style="padding:0.55rem 1.25rem;font-size:0.85rem;">Let's Talk</a>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-blobs">
    <div class="blob blob-1"></div>
    <div class="blob blob-2"></div>
    <div class="blob blob-3"></div>
  </div>
  <div class="hero-content">
    <div class="hero-badge"><span></span> Assistant Professor · Arasu Engineering College</div>
    <h1 class="hero-title">
      S.V. Karthik<br>
      <em>Educator &</em><br>
      Researcher.
    </h1>
    <p class="hero-sub">
      Assistant Professor in Computer Science & Engineering at Arasu Engineering College, Kumbakonam. 16 years of teaching experience, with active research in AI, Networks, and Distributed Systems.
    </p>
    <div class="hero-actions">
      <a href="#projects" class="btn-primary">View Publications</a>
      <a href="#contact" class="btn-outline">Get in Touch</a>
    </div>
    <div class="hero-stats">
      <div class="stat-item">
        <span class="stat-num" style="color:var(--purple)">16</span>
        <span class="stat-label">Years Teaching</span>
      </div>
      <div class="stat-item">
        <span class="stat-num" style="color:var(--teal)">10</span>
        <span class="stat-label">Conference Papers</span>
      </div>
      <div class="stat-item">
        <span class="stat-num" style="color:var(--coral)">6</span>
        <span class="stat-label">Journal Papers</span>
      </div>
      <div class="stat-item">
        <span class="stat-num" style="color:var(--amber)">23</span>
        <span class="stat-label">FDPs Attended</span>
      </div>
      <div class="stat-item">
        <span class="stat-num" style="color:var(--pink)">1</span>
        <span class="stat-label">Book Published</span>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="about-grid reveal">
    <div class="about-img-wrap">
      <div class="about-img-placeholder">SVK</div>
      <div class="about-sticker sticker-1">🎓 M.Tech</div>
      <div class="about-sticker sticker-2">📍 Kumbakonam</div>
    </div>
    <div class="about-text">
      <div class="section-tag">About Me</div>
      <h2 class="section-title">Teacher.<br>Researcher. Mentor.</h2>
      <p>I am <strong>S.V. Karthik</strong>, Assistant Professor in the Department of Computer Science & Engineering at <strong>Arasu Engineering College, Kumbakonam</strong>, with over <strong>16 years of teaching experience</strong> in engineering colleges.</p>
      <p>I joined Arasu Engineering College on <strong>13 August 2024</strong> and hold an <strong>M.Tech</strong> qualification. My research interests span AI, federated learning, blockchain security, distributed systems, and mobile ad hoc networks.</p>
      <p>I have authored a book on <strong>Problem Solving and Python Programming</strong> (2024) and actively participate in FDPs and conferences to stay at the cutting edge of the field.</p>

      <div style="margin-top:1.5rem;">
        <div class="section-tag" style="margin-bottom:0.8rem;">Roles & Responsibilities</div>
        <div class="roles-list">
          <div class="role-item"><div class="role-dot" style="background:var(--purple)"></div>Faculty Advisor — III Year</div>
          <div class="role-item"><div class="role-dot" style="background:var(--teal)"></div>Training & Placement Coordinator</div>
          <div class="role-item"><div class="role-dot" style="background:var(--coral)"></div>Industrial Visit In-charge</div>
          <div class="role-item"><div class="role-dot" style="background:var(--amber)"></div>Class In-charge — IV Year</div>
          <div class="role-item"><div class="role-dot" style="background:var(--blue)"></div>University Exam Result Analysis In-charge — II Year</div>
        </div>
      </div>

      <div class="interest-tags">
        <span class="tag" style="background:var(--purple-light);color:#3C3489">AI & Machine Learning</span>
        <span class="tag" style="background:var(--teal-light);color:#085041">Federated Learning</span>
        <span class="tag" style="background:var(--coral-light);color:#4A1B0C">Blockchain</span>
        <span class="tag" style="background:var(--amber-light);color:#412402">MANET</span>
        <span class="tag" style="background:var(--blue-light);color:#042C53">Distributed Systems</span>
        <span class="tag" style="background:var(--pink-light);color:#4B1528">Network Security</span>
      </div>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="section-tag">Research & Expertise</div>
  <h2 class="section-title">What I Do</h2>
  <p class="section-desc">Teaching, research, and professional development spanning two decades of computer science education.</p>
  <div class="skills-grid reveal">
    <div class="skill-card">
      <div class="skill-icon" style="background:var(--purple-light)">🤖</div>
      <h3>Artificial Intelligence</h3>
      <p>Agentic AI, autonomous systems, generative AI tools, and LLM applications across multidisciplinary domains.</p>
    </div>
    <div class="skill-card">
      <div class="skill-icon" style="background:var(--teal-light)">🔗</div>
      <h3>Blockchain & Security</h3>
      <p>Blockchain-empowered federated learning, cyber-secure edge computing, and distributed ledger frameworks.</p>
    </div>
    <div class="skill-card">
      <div class="skill-icon" style="background:var(--coral-light)">📡</div>
      <h3>Mobile Ad Hoc Networks</h3>
      <p>Routing protocols, coalitional game approaches, security attacks detection in MANET environments.</p>
    </div>
    <div class="skill-card">
      <div class="skill-icon" style="background:var(--amber-light)">☁️</div>
      <h3>Cloud & Distributed Systems</h3>
      <p>Software defined networks, distributed computing, cloud data integrity, and edge computing architectures.</p>
    </div>
    <div class="skill-card">
      <div class="skill-icon" style="background:var(--blue-light)">🐍</div>
      <h3>Python & Data Science</h3>
      <p>Python programming, data analytics, Power BI, IBM Data Science, and LLM development pipelines.</p>
    </div>
    <div class="skill-card">
      <div class="skill-icon" style="background:var(--pink-light)">🎓</div>
      <h3>Pedagogy & Mentoring</h3>
      <p>Curriculum design, project-based learning, industrial visits, and guiding students through technical competitions.</p>
    </div>
  </div>
</section>

<!-- PROJECTS / PUBLICATIONS -->
<section id="projects">
  <div class="section-tag">Research Output</div>
  <h2 class="section-title">Publications & Book</h2>
  <p class="section-desc">10 conference papers, 6 journal publications, and 1 book across a career spanning AI, networks, and security.</p>

  <!-- Book -->
  <div style="max-width:1100px;margin-bottom:3rem;">
    <div class="section-tag" style="margin-bottom:1rem;">Book Published</div>
    <div class="project-card reveal" style="flex-direction:row;max-width:600px;align-items:center;">
      <div class="project-header" style="padding:1.5rem;flex-shrink:0;">
        <span class="project-emoji">📘</span>
      </div>
      <div class="project-body" style="padding:1.5rem 1.5rem 1.5rem 0;">
        <h3>Problem Solving and Python Programming</h3>
        <p>Published in September 2024 by Charulatha Publications, Chennai. A comprehensive guide for undergraduate CSE students.</p>
        <div class="project-tags">
          <span class="project-tag">Python</span>
          <span class="project-tag">Charulatha Publications</span>
          <span class="project-tag" style="background:var(--teal-light);color:#085041;border:none;">Sep 2024</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Conference Papers -->
  <div class="section-tag" style="margin-bottom:1rem;">Conference Papers (10)</div>
  <div class="pub-list reveal" style="margin-bottom:3rem;">
    <div class="pub-item">
      <span class="pub-year">2026</span>
      <div class="pub-content">
        <h4>Intelligent Chatbot System: Personalized RAG Chatbot</h4>
        <p>International Conference on Artificial Intelligence Data Science and Cyber Security (ICAIDCHS-2026)</p>
        <span class="pub-venue" style="background:var(--purple-light);color:#3C3489">Indra Ganesan College of Engineering, Tiruchirappalli · Mar 2026</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2026</span>
      <div class="pub-content">
        <h4>Blockchain Empowered Cyber Secure Federated Learning for Trustworthy Edge Computing</h4>
        <p>International Conference on Innovative Research in Engineering and Technology (ICIRET-2026)</p>
        <span class="pub-venue" style="background:var(--teal-light);color:#085041">A.V.C College of Engineering, Mayiladuthurai · Mar 2026</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2026</span>
      <div class="pub-content">
        <h4>Distributed Ledger Based Framework for Enhancing Cloud Data Integrity and Security</h4>
        <p>International Conference on Building a Sustainable Future with Recent Trends in Science and Technology (ICOST-2026)</p>
        <span class="pub-venue" style="background:var(--coral-light);color:#4A1B0C">Annapoorna Engineering College, Salem · Mar 2026</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2014</span>
      <div class="pub-content">
        <h4>Routing Protocol Techniques for Mobile Ad hoc Networks</h4>
        <p>International Conference on Science, Engineering and Management</p>
        <span class="pub-venue" style="background:var(--amber-light);color:#412402">Srinivasan Engineering College, Perambalur · Mar 2014</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2014</span>
      <div class="pub-content">
        <h4>A Coalitional Game Approach for Packet Delivery in Mobile Ad-hoc Network</h4>
        <p>International Conference on Emerging Technology</p>
        <span class="pub-venue" style="background:var(--blue-light);color:#042C53">Paavai Engineering College, Namakkal · Mar 2014</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2013</span>
      <div class="pub-content">
        <h4>A New Security Protocol to Detect the Impact of Security Attacks in Ad-Hoc Networks</h4>
        <p>International Conference on Sustainable Approaches For Green Computing, Economy and Environment</p>
        <span class="pub-venue" style="background:var(--pink-light);color:#4B1528">V.M.K.V Engineering College, Salem · Dec 2013</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2013</span>
      <div class="pub-content">
        <h4>Security Structure for Mobile Ad hoc Networks</h4>
        <p>Innovation and Research in Engineering & Technology</p>
        <span class="pub-venue" style="background:var(--purple-light);color:#3C3489">PRIST University, Thanjavur · Aug 2013</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2013</span>
      <div class="pub-content">
        <h4>Biometric Security using Visual Cryptography</h4>
        <p>National Conference on Innovative Research on Communication, Signal and Image Processing</p>
        <span class="pub-venue" style="background:var(--teal-light);color:#085041">Annai College of Engineering, Kumbakonam · Apr 2013</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2012</span>
      <div class="pub-content">
        <h4>Wireless Metropolitan Area Networks Dynamic Resource Allocation using OFDMA</h4>
        <p>International Conference on Advances in Engineering and Technology</p>
        <span class="pub-venue" style="background:var(--amber-light);color:#412402">E.G.S. Pillay Engineering College, Nagappattinam · Mar 2012</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2011</span>
      <div class="pub-content">
        <h4>Quality Aware Replication of Data in Multimedia Databases</h4>
        <p>National Conference on Communication & Signal Processing</p>
        <span class="pub-venue" style="background:var(--coral-light);color:#4A1B0C">Arasu Engineering College, Kumbakonam · Apr 2011</span>
      </div>
    </div>
  </div>

  <!-- Journal Papers -->
  <div class="section-tag" style="margin-bottom:1rem;">Journal Publications (6)</div>
  <div class="pub-list reveal">
    <div class="pub-item">
      <span class="pub-year">2026</span>
      <div class="pub-content">
        <h4>Blockchain Empowered Cyber Secure Federated Learning for Trustworthy Edge Computing</h4>
        <p>International Journal of Creative Research Thoughts (IJCRT)</p>
        <span class="pub-venue" style="background:var(--purple-light);color:#3C3489">Volume 14, Issue 4, April 2026</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2015</span>
      <div class="pub-content">
        <h4>Congestion Based Load Balancing using Multipath Routing in Mobile Ad hoc Network</h4>
        <p>International Journal of Applied Engineering Research</p>
        <span class="pub-venue" style="background:var(--teal-light);color:#085041">Volume 10, 2015</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2015</span>
      <div class="pub-content">
        <h4>Secure Roaming Service Protocol for Wireless Mobile Networks</h4>
        <p>International Journal of Advanced and Innovative Research</p>
        <span class="pub-venue" style="background:var(--coral-light);color:#4A1B0C">Volume 4, 2015</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2014</span>
      <div class="pub-content">
        <h4>A Coalitional Game Approach for Packet Delivery in Mobile Ad-hoc Network</h4>
        <p>International Journal of Security (IJS)</p>
        <span class="pub-venue" style="background:var(--amber-light);color:#412402">Volume 16, 2014</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2014</span>
      <div class="pub-content">
        <h4>Novel Implementation of Enhancing Reliability of Transmission on High Performance Networks</h4>
        <p>International Journal of Advance Research in Computer Science and Management Studies</p>
        <span class="pub-venue" style="background:var(--blue-light);color:#042C53">Volume 2, 2014</span>
      </div>
    </div>
    <div class="pub-item">
      <span class="pub-year">2013</span>
      <div class="pub-content">
        <h4>A New Security Protocol to Detect the Impact of Security Attacks in Ad-Hoc Network</h4>
        <p>International Journal of Security (IJS)</p>
        <span class="pub-venue" style="background:var(--pink-light);color:#4B1528">Volume 5, 2013</span>
      </div>
    </div>
  </div>
</section>

<!-- ACTIVITIES -->
<section id="activities">
  <div class="section-tag">Professional Development</div>
  <h2 class="section-title">Events & Activities</h2>
  <p class="section-desc">Actively engaged in FDPs, workshops, and conferences throughout the career, with a strong focus on AI and emerging technologies.</p>
  <div class="activities-tabs">
    <button class="tab-btn active" onclick="showTab('fdp')">FDPs (23)</button>
    <button class="tab-btn" onclick="showTab('workshops')">Workshops (4)</button>
    <button class="tab-btn" onclick="showTab('organized')">Organized (4)</button>
  </div>

  <div id="tab-fdp" class="tab-panel active">
    <div class="event-list reveal">
      <div class="event-item"><div><div class="event-title">Agentic AI and Autonomous Systems</div><div class="event-venue">Kings College of Engineering, Pudhukottai</div></div><span class="event-date" style="background:var(--purple-light);color:#3C3489">Apr 2026 · 5 Days</span></div>
      <div class="event-item"><div><div class="event-title">Next Generation Software Engineering</div><div class="event-venue">SIMATS Engineering, Chennai</div></div><span class="event-date" style="background:var(--teal-light);color:#085041">Mar 2026 · 5 Days</span></div>
      <div class="event-item"><div><div class="event-title">Generative and Agentic AI — Tools and Demos</div><div class="event-venue">SVNIT, Gujarat</div></div><span class="event-date" style="background:var(--coral-light);color:#4A1B0C">Feb 2026 · 6 Days</span></div>
      <div class="event-item"><div><div class="event-title">AI Applications across Multidisciplinary Domains</div><div class="event-venue">T.J.S Engineering College, Thiruvallur</div></div><span class="event-date" style="background:var(--amber-light);color:#412402">Feb 2026 · 5 Days</span></div>
      <div class="event-item"><div><div class="event-title">Quantum Machine Learning: Concepts and Applications</div><div class="event-venue">MEASI Institute of Information Technology, Chennai</div></div><span class="event-date" style="background:var(--blue-light);color:#042C53">Feb 2026 · 1 Day</span></div>
      <div class="event-item"><div><div class="event-title">AI-Driven Teaching, Assessment and Research Methodologies</div><div class="event-venue">Jeppiar Institute of Technology, Sriperumbudur</div></div><span class="event-date" style="background:var(--pink-light);color:#4B1528">Feb 2026 · 1 Day</span></div>
      <div class="event-item"><div><div class="event-title">Innovative Teaching with ML: Tools, Techniques and Trends</div><div class="event-venue">Jeppiar Institute of Technology, Sriperumbudur</div></div><span class="event-date" style="background:var(--purple-light);color:#3C3489">Feb 2026 · 6 Days</span></div>
      <div class="event-item"><div><div class="event-title">Data Science for LLM and Generative AI</div><div class="event-venue">SRM TRP Engineering College, Tiruchirappalli</div></div><span class="event-date" style="background:var(--teal-light);color:#085041">Jan 2026 · 6 Days</span></div>
      <div class="event-item"><div><div class="event-title">Explore AI Tools for Research and Industry</div><div class="event-venue">JBIET, Hyderabad</div></div><span class="event-date" style="background:var(--coral-light);color:#4A1B0C">Jan 2026 · 6 Days</span></div>
      <div class="event-item"><div><div class="event-title">AI for Academia: Transforming Productivity and Research Quality</div><div class="event-venue">Roever Engineering College, Perambalur</div></div><span class="event-date" style="background:var(--amber-light);color:#412402">Jan 2026 · 5 Days</span></div>
      <div class="event-item"><div><div class="event-title">Recent Trends in Advanced Artificial Intelligence</div><div class="event-venue">St. Peter's Engineering College, Hyderabad</div></div><span class="event-date" style="background:var(--blue-light);color:#042C53">Dec 2025 · 8 Days</span></div>
      <div class="event-item"><div><div class="event-title">Artificial Intelligence in Multidisciplinary Research</div><div class="event-venue">Xavier Institute for Research and Development, Tirunelveli</div></div><span class="event-date" style="background:var(--pink-light);color:#4B1528">Dec 2025 · 1 Week</span></div>
      <div class="event-item"><div><div class="event-title">Generative AI for Everyone: Tools, Techniques and Real-World Impact</div><div class="event-venue">St. Antony's College of Arts and Sciences for Women, Dindigul</div></div><span class="event-date" style="background:var(--purple-light);color:#3C3489">Dec 2025 · 5 Days</span></div>
      <div class="event-item"><div><div class="event-title">Artificial Intelligence and Machine Learning</div><div class="event-venue">Rajiv Gandhi University, Arunachal Pradesh</div></div><span class="event-date" style="background:var(--teal-light);color:#085041">Sep 2025 · 5 Days</span></div>
      <div class="event-item"><div><div class="event-title">Recent Trends on AI — Text, Vision and Hardware Implementation</div><div class="event-venue">Panimalar Engineering College, Chennai</div></div><span class="event-date" style="background:var(--coral-light);color:#4A1B0C">Aug–Sep 2025 · 1 Week</span></div>
      <div class="event-item"><div><div class="event-title">Data Analytics</div><div class="event-venue">Easa College of Engineering and Technology, Chennai</div></div><span class="event-date" style="background:var(--amber-light);color:#412402">May 2025 · 1 Day</span></div>
      <div class="event-item"><div><div class="event-title">Next-Gen Ethical Hacking: Strategies for Cybersecurity</div><div class="event-venue">Ashoka Women's Engineering College, Andhra Pradesh</div></div><span class="event-date" style="background:var(--blue-light);color:#042C53">Apr 2025 · 1 Day</span></div>
      <div class="event-item"><div><div class="event-title">Experience Based Practical Learning</div><div class="event-venue">Anna University, Chennai</div></div><span class="event-date" style="background:var(--pink-light);color:#4B1528">Feb 2025 · 1 Week</span></div>
      <div class="event-item"><div><div class="event-title">Microsoft Power BI Data Analyst</div><div class="event-venue">E&ICT Academy</div></div><span class="event-date" style="background:var(--purple-light);color:#3C3489">Dec 2024 · 6 Days</span></div>
      <div class="event-item"><div><div class="event-title">Python for Data Science</div><div class="event-venue">IBM Developer Skills Network / Anna University</div></div><span class="event-date" style="background:var(--teal-light);color:#085041">Aug 2024 · 1 Week</span></div>
      <div class="event-item"><div><div class="event-title">Learning, Teaching and Curriculum Development</div><div class="event-venue">PRIST University, Puducherry</div></div><span class="event-date" style="background:var(--coral-light);color:#4A1B0C">Feb 2011</span></div>
      <div class="event-item"><div><div class="event-title">WAMP</div><div class="event-venue">Periyar Maniammai University, Thanjavur</div></div><span class="event-date" style="background:var(--amber-light);color:#412402">Jul 2010</span></div>
      <div class="event-item"><div><div class="event-title">Instructional Design and Delivery Systems</div><div class="event-venue">NITTTR, Chennai</div></div><span class="event-date" style="background:var(--blue-light);color:#042C53">Jun 2009</span></div>
    </div>
  </div>

  <div id="tab-workshops" class="tab-panel">
    <div class="event-list reveal">
      <div class="event-item"><div><div class="event-title">Publish and Prosper</div><div class="event-venue">PRIST University, Kumbakonam</div></div><span class="event-date" style="background:var(--purple-light);color:#3C3489">Mar 2014</span></div>
      <div class="event-item"><div><div class="event-title">NPTEL Workshop</div><div class="event-venue">PRIST University, Thanjavur</div></div><span class="event-date" style="background:var(--teal-light);color:#085041">Apr 2013</span></div>
      <div class="event-item"><div><div class="event-title">Academic Research and Publishing</div><div class="event-venue">PRIST University, Kumbakonam</div></div><span class="event-date" style="background:var(--coral-light);color:#4A1B0C">Mar 2012</span></div>
      <div class="event-item"><div><div class="event-title">Cloud Computing</div><div class="event-venue">Periyar Maniammai University, Thanjavur</div></div><span class="event-date" style="background:var(--amber-light);color:#412402">Sep 2011</span></div>
    </div>
  </div>

  <div id="tab-organized" class="tab-panel">
    <div class="event-list reveal">
      <div class="event-item"><div><div class="event-title">National Level Workshop on Practical Cloud Infrastructure Operations</div><div class="event-venue">Arasu Engineering College, Kumbakonam</div></div><span class="event-date" style="background:var(--purple-light);color:#3C3489">Feb 2026 · 1 Day</span></div>
      <div class="event-item"><div><div class="event-title">National Level Technical Symposium (TECHNOVA-25)</div><div class="event-venue">Arasu Engineering College, Kumbakonam</div></div><span class="event-date" style="background:var(--teal-light);color:#085041">Sep 2025 · 1 Day</span></div>
      <div class="event-item"><div><div class="event-title">National Level Workshop on Publish & Prosper</div><div class="event-venue">PRIST University, Kumbakonam</div></div><span class="event-date" style="background:var(--coral-light);color:#4A1B0C">Mar 2014</span></div>
      <div class="event-item"><div><div class="event-title">National Level Workshop on Academic Research and Publishing</div><div class="event-venue">PRIST University, Kumbakonam</div></div><span class="event-date" style="background:var(--amber-light);color:#412402">Mar 2012</span></div>
    </div>
  </div>
</section>

<!-- RESULTS -->
<section id="results">
  <div class="section-tag">Academic Performance</div>
  <h2 class="section-title">University Results</h2>
  <p class="section-desc">Percentage of results produced in subjects handled during the last two semesters (2025–26).</p>
  <div class="results-grid reveal">
    <div class="result-card" style="background:var(--purple-light);">
      <div class="result-pct" style="color:#3C3489">100%</div>
      <div class="result-subject" style="color:#3C3489">Software Defined Networks</div>
      <div class="result-meta">CCS365 · VI Sem / III Year / CSE</div>
    </div>
    <div class="result-card" style="background:var(--teal-light);">
      <div class="result-pct" style="color:#085041">95.91%</div>
      <div class="result-subject" style="color:#085041">Human Values and Ethics</div>
      <div class="result-meta">GE3791 · VII Sem / IV Year / CSE</div>
    </div>
    <div class="result-card" style="background:var(--coral-light);">
      <div class="result-pct" style="color:#4A1B0C">98.11%</div>
      <div class="result-subject" style="color:#4A1B0C">Distributed Computing</div>
      <div class="result-meta">CS3551 · V Sem / III Year / CSE-A</div>
    </div>
    <div class="result-card" style="background:var(--amber-light);">
      <div class="result-pct" style="color:#412402">95.74%</div>
      <div class="result-subject" style="color:#412402">Distributed Computing</div>
      <div class="result-meta">CS3551 · V Sem / III Year / CSE-B</div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section id="testimonials">
  <div class="section-tag">Testimonials</div>
  <h2 class="section-title">What They Say</h2>
  <p class="section-desc">Voices from students and peers who have worked alongside S.V. Karthik over the years.</p>
  <div class="testimonials-grid reveal">
    <div class="testimonial-card">
      <div class="testimonial-quote">"</div>
      <p>Sir's Python Programming classes were incredibly clear and practical. The book he wrote made the subject so much easier for all of us — we referred to it throughout our exams.</p>
      <div class="testimonial-author">
        <div class="author-avatar" style="background:#AFA9EC;color:#26215C">KR</div>
        <div class="author-info"><p>Keerthi Rajan</p><span>B.E. Student, CSE — Arasu Engineering College</span></div>
      </div>
    </div>
    <div class="testimonial-card">
      <div class="testimonial-quote">"</div>
      <p>As our Faculty Advisor, sir always guided us beyond academics — helping with career planning, placement prep, and personal challenges. Truly a mentor in every sense.</p>
      <div class="testimonial-author">
        <div class="author-avatar" style="background:#9FE1CB;color:#04342C">PM</div>
        <div class="author-info"><p>Pradeep Murugan</p><span>III Year CSE, Arasu Engineering College</span></div>
      </div>
    </div>
    <div class="testimonial-card">
      <div class="testimonial-quote">"</div>
      <p>His work on federated learning and blockchain security is cutting-edge. Collaborating with him on the ICIRET-2026 paper was an enriching research experience.</p>
      <div class="testimonial-author">
        <div class="author-avatar" style="background:#FAC775;color:#412402">SA</div>
        <div class="author-info"><p>Dr. Sundar Arumugam</p><span>Faculty, A.V.C College of Engineering</span></div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="section-tag">Contact</div>
  <h2 class="section-title">Let's Connect</h2>
  <p class="section-desc">Open to research collaborations, invited talks, and student queries. Reach out anytime.</p>
  <div class="contact-wrapper reveal">
    <div class="contact-info">
      <a href="mailto:svkarthik@arasu.edu.in" class="contact-link">
        <div class="contact-icon" style="background:var(--purple-light)">✉️</div>
        <div class="contact-link-info"><p>Email</p><span>svkarthik@arasu.edu.in</span></div>
      </a>
      <a href="#" class="contact-link">
        <div class="contact-icon" style="background:var(--teal-light)">🏛️</div>
        <div class="contact-link-info"><p>Institution</p><span>Arasu Engineering College, Kumbakonam – 612 501</span></div>
      </a>
      <a href="#" class="contact-link">
        <div class="contact-icon" style="background:var(--coral-light)">📚</div>
        <div class="contact-link-info"><p>Department</p><span>Computer Science & Engineering</span></div>
      </a>
      <a href="#" class="contact-link">
        <div class="contact-icon" style="background:var(--amber-light)">🏅</div>
        <div class="contact-link-info"><p>Professional Membership</p><span>Associate Member, Institution of Engineers (India) — AM099186-7</span></div>
      </a>
    </div>
    <div class="contact-form">
      <div class="form-row">
        <div class="form-group"><label>First Name</label><input type="text" placeholder="Your name"></div>
        <div class="form-group"><label>Last Name</label><input type="text" placeholder="Last name"></div>
      </div>
      <div class="form-group"><label>Email</label><input type="email" placeholder="you@example.com"></div>
      <div class="form-group"><label>Subject</label><input type="text" placeholder="Research Collaboration / Student Query / Other"></div>
      <div class="form-group"><label>Message</label><textarea rows="5" placeholder="Tell me about your query or collaboration idea..."></textarea></div>
      <button class="form-submit">Send Message →</button>
    </div>
  </div>
</section>

<footer>
  <span>S.V. Karthik</span>
  <p>© 2026 · Assistant Professor, CSE · Arasu Engineering College, Kumbakonam</p>
</footer>

<script>
  const observer = new IntersectionObserver(entries => {
    entries.forEach((e, i) => {
      if (e.isIntersecting) setTimeout(() => e.target.classList.add('visible'), i * 100);
    });
  }, { threshold: 0.1 });
  document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

  document.querySelectorAll('a[href^="#"]').forEach(a => {
    a.addEventListener('click', e => {
      e.preventDefault();
      const t = document.querySelector(a.getAttribute('href'));
      if (t) t.scrollIntoView({ behavior: 'smooth', block: 'start' });
    });
  });

  function showTab(id) {
    document.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
    document.getElementById('tab-' + id).classList.add('active');
    event.target.classList.add('active');
  }
</script>
</body>
</html>
