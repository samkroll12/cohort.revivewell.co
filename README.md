<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>The Revive Cohort — Integrative Wellness Program | ReviveWell</title>
<meta name="description" content="A 6 or 12-month physician-led integrative wellness cohort. Functional labs, peptide therapy (GLP-1, NAD+, glutathione), and personalized protocols built around gut, sleep, and energy. 8–12 founding members." />
<meta property="og:title" content="The Revive Cohort — Integrative Wellness Program" />
<meta property="og:description" content="A physician-led 6 or 12-month integrative wellness cohort. Functional labs, peptides, and protocols for gut, sleep, and energy. 8–12 founding spots." />
<meta property="og:type" content="website" />
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet" />
<style>
  :root{
    --bg:#f5f1ea;
    --bg-2:#efe7da;
    --ink:#1c2a23;
    --ink-2:#3a4a40;
    --moss:#4a6b53;
    --moss-deep:#2f4a37;
    --accent:#c8794a;
    --accent-2:#e8b894;
    --line:#d8cdb8;
    --card:#fbf8f1;
    --shadow:0 1px 2px rgba(28,42,35,.04), 0 8px 32px rgba(28,42,35,.08);
  }
  *{box-sizing:border-box}
  html,body{margin:0;padding:0}
  body{
    font-family:'Inter',system-ui,-apple-system,sans-serif;
    background:var(--bg);
    color:var(--ink);
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
  }
  h1,h2,h3,h4{font-family:'Fraunces',Georgia,serif;font-weight:500;letter-spacing:-.02em;line-height:1.15;color:var(--moss-deep)}
  h1{font-size:clamp(2.4rem,5.5vw,4.4rem);margin:0 0 1rem}
  h2{font-size:clamp(1.8rem,3.5vw,2.8rem);margin:0 0 1rem}
  h3{font-size:clamp(1.2rem,2vw,1.5rem);margin:0 0 .5rem}
  p{margin:0 0 1rem;color:var(--ink-2)}
  a{color:var(--moss-deep);text-decoration:none}
  .container{max-width:1180px;margin:0 auto;padding:0 1.5rem}
  .container-narrow{max-width:780px;margin:0 auto;padding:0 1.5rem}

  /* Nav */
  nav{
    position:sticky;top:0;z-index:50;background:rgba(245,241,234,.92);
    backdrop-filter:blur(10px);border-bottom:1px solid var(--line);
  }
  .nav-inner{display:flex;align-items:center;justify-content:space-between;padding:1rem 1.5rem;max-width:1180px;margin:0 auto}
  .logo{font-family:'Fraunces',serif;font-size:1.3rem;font-weight:600;color:var(--moss-deep);letter-spacing:-.01em}
  .nav-links{display:flex;gap:2rem;font-size:.92rem}
  .nav-links a{color:var(--ink-2);font-weight:500}
  .nav-links a:hover{color:var(--accent)}
  .nav-cta{background:var(--moss-deep);color:#fbf8f1!important;padding:.55rem 1.1rem;border-radius:999px;font-weight:500;font-size:.88rem;transition:transform .2s}
  .nav-cta:hover{transform:translateY(-1px);background:var(--accent)}
  @media(max-width:760px){.nav-links a:not(.nav-cta){display:none}}

  /* Hero */
  .hero{padding:5rem 0 4rem;position:relative;overflow:hidden}
  .hero-grid{display:grid;grid-template-columns:1fr 1fr;gap:4rem;align-items:center}
  @media(max-width:900px){.hero-grid{grid-template-columns:1fr;gap:2.5rem}}
  .badge{
    display:inline-flex;align-items:center;gap:.5rem;
    background:var(--bg-2);border:1px solid var(--line);
    padding:.4rem .9rem;border-radius:999px;
    font-size:.78rem;font-weight:500;color:var(--moss-deep);
    margin-bottom:1.5rem;text-transform:uppercase;letter-spacing:.08em;
  }
  .badge .dot{width:6px;height:6px;border-radius:50%;background:var(--accent);animation:pulse 2s infinite}
  @keyframes pulse{0%,100%{opacity:1}50%{opacity:.4}}
  .hero h1 em{font-style:italic;color:var(--accent);font-weight:400}
  .hero-sub{font-size:1.15rem;max-width:540px;margin-bottom:2rem}
  .cta-row{display:flex;gap:1rem;flex-wrap:wrap;align-items:center}
  .btn{
    display:inline-flex;align-items:center;gap:.6rem;
    padding:.95rem 1.7rem;border-radius:999px;font-weight:500;font-size:.98rem;
    transition:all .2s;cursor:pointer;border:none;font-family:inherit;
  }
  .btn-primary{background:var(--moss-deep);color:#fbf8f1}
  .btn-primary:hover{background:var(--accent);transform:translateY(-1px);box-shadow:var(--shadow)}
  .btn-ghost{background:transparent;color:var(--moss-deep);border:1px solid var(--moss-deep)}
  .btn-ghost:hover{background:var(--moss-deep);color:#fbf8f1}
  .hero-stats{display:flex;gap:2.5rem;margin-top:2.5rem;padding-top:2rem;border-top:1px solid var(--line)}
  .stat strong{display:block;font-family:'Fraunces',serif;font-size:1.8rem;color:var(--moss-deep);font-weight:600}
  .stat span{font-size:.82rem;color:var(--ink-2);text-transform:uppercase;letter-spacing:.05em}

  .hero-visual{position:relative;aspect-ratio:4/5;border-radius:24px;overflow:hidden;background:linear-gradient(135deg,#d8d0bb 0%,#c8b896 100%);box-shadow:var(--shadow)}
  .hero-visual svg{width:100%;height:100%;display:block}
  .float-card{
    position:absolute;background:var(--card);border-radius:14px;padding:.9rem 1.1rem;
    box-shadow:var(--shadow);font-size:.85rem;display:flex;align-items:center;gap:.7rem;
  }
  .fc-1{top:8%;right:-8%}
  .fc-2{bottom:12%;left:-10%}
  .fc-icon{width:32px;height:32px;border-radius:50%;background:var(--bg-2);display:grid;place-items:center;color:var(--moss-deep);font-weight:600}
  .fc-text strong{display:block;color:var(--moss-deep);font-size:.88rem}
  .fc-text span{color:var(--ink-2);font-size:.75rem}
  @media(max-width:600px){.float-card{display:none}}

  /* Marquee / trust */
  .trust{padding:2rem 0;border-top:1px solid var(--line);border-bottom:1px solid var(--line);background:var(--bg-2)}
  .trust-row{display:flex;justify-content:space-around;align-items:center;flex-wrap:wrap;gap:2rem;font-size:.85rem;color:var(--ink-2);text-transform:uppercase;letter-spacing:.1em}

  /* Sections */
  section{padding:5rem 0}
  .section-label{display:inline-block;font-size:.8rem;text-transform:uppercase;letter-spacing:.15em;color:var(--accent);font-weight:600;margin-bottom:1rem}
  .lede{font-size:1.15rem;max-width:680px}

  /* Problem */
  .problem-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.5rem;margin-top:3rem}
  @media(max-width:900px){.problem-grid{grid-template-columns:1fr}}
  .problem-card{background:var(--card);padding:2rem;border-radius:18px;border:1px solid var(--line)}
  .problem-card h3{display:flex;align-items:center;gap:.7rem;color:var(--moss-deep)}
  .problem-card .num{
    display:grid;place-items:center;width:32px;height:32px;border-radius:50%;
    background:var(--accent);color:#fff;font-size:.85rem;font-family:'Inter',sans-serif;font-weight:600;
  }

  /* Pillars */
  .pillars{background:var(--moss-deep);color:#f5f1ea}
  .pillars h2{color:#f5f1ea}
  .pillars p{color:#d8cdb8}
  .pillar-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem;margin-top:3rem}
  @media(max-width:900px){.pillar-grid{grid-template-columns:1fr}}
  .pillar{background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.1);padding:2rem;border-radius:18px;backdrop-filter:blur(10px)}
  .pillar-icon{width:48px;height:48px;border-radius:12px;background:var(--accent);display:grid;place-items:center;margin-bottom:1.2rem}
  .pillar h3{color:#f5f1ea;font-size:1.4rem}
  .pillar ul{list-style:none;padding:0;margin:1rem 0 0;font-size:.92rem;color:#d8cdb8}
  .pillar ul li{padding:.4rem 0;border-bottom:1px solid rgba(255,255,255,.08);display:flex;align-items:center;gap:.6rem}
  .pillar ul li:last-child{border-bottom:none}
  .pillar ul li::before{content:'';width:5px;height:5px;border-radius:50%;background:var(--accent-2);flex-shrink:0}

  /* What's Inside */
  .inside{background:var(--bg)}
  .inside-grid{display:grid;grid-template-columns:1.2fr 1fr;gap:4rem;align-items:start;margin-top:3rem}
  @media(max-width:900px){.inside-grid{grid-template-columns:1fr;gap:2rem}}
  .inside-list{list-style:none;padding:0;margin:0}
  .inside-list li{padding:1.2rem 0;border-bottom:1px solid var(--line);display:flex;gap:1rem;align-items:flex-start}
  .inside-list li:last-child{border-bottom:none}
  .check{width:28px;height:28px;border-radius:50%;background:var(--moss-deep);color:#f5f1ea;display:grid;place-items:center;flex-shrink:0;font-size:.8rem;font-weight:600}
  .inside-list strong{display:block;color:var(--moss-deep);font-size:1rem;margin-bottom:.2rem}
  .inside-list span{color:var(--ink-2);font-size:.92rem}

  .timeline{background:var(--card);padding:2rem;border-radius:18px;border:1px solid var(--line);position:sticky;top:6rem}
  .timeline h4{font-family:'Fraunces',serif;font-size:1.2rem;color:var(--moss-deep);margin:0 0 1.2rem}
  .phase{display:flex;gap:1rem;padding:.8rem 0;border-bottom:1px dashed var(--line)}
  .phase:last-child{border-bottom:none}
  .phase-num{font-family:'Fraunces',serif;font-size:1.4rem;color:var(--accent);font-weight:500;line-height:1;min-width:32px}
  .phase-name{font-weight:600;color:var(--moss-deep);font-size:.95rem;display:block;margin-bottom:.1rem}
  .phase-desc{font-size:.85rem;color:var(--ink-2)}

  /* Pricing */
  .pricing{background:var(--bg-2)}
  .price-grid{display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;margin-top:3rem}
  @media(max-width:760px){.price-grid{grid-template-columns:1fr}}
  .price-card{
    background:var(--card);padding:2.5rem;border-radius:20px;border:1px solid var(--line);
    position:relative;display:flex;flex-direction:column;
  }
  .price-card.featured{border:2px solid var(--moss-deep);background:#fbf8f1}
  .featured-tag{
    position:absolute;top:-12px;right:2rem;background:var(--accent);color:#fff;
    padding:.3rem .9rem;border-radius:999px;font-size:.75rem;font-weight:600;text-transform:uppercase;letter-spacing:.08em;
  }
  .price-card h3{font-size:1.6rem}
  .price-tier{font-size:.85rem;color:var(--accent);text-transform:uppercase;letter-spacing:.1em;margin-bottom:.5rem;font-weight:600}
  .price-num{font-family:'Fraunces',serif;font-size:2.6rem;color:var(--moss-deep);font-weight:600;margin:1rem 0 .3rem;line-height:1}
  .price-sub{color:var(--ink-2);font-size:.9rem;margin-bottom:1.5rem}
  .price-features{list-style:none;padding:0;margin:1.5rem 0;flex-grow:1}
  .price-features li{padding:.5rem 0;display:flex;align-items:flex-start;gap:.6rem;font-size:.93rem;color:var(--ink-2)}
  .price-features li::before{content:'✓';color:var(--moss);font-weight:700;flex-shrink:0}

  /* FAQ */
  .faq-list{margin-top:3rem;max-width:780px;margin-left:auto;margin-right:auto}
  details{
    background:var(--card);border:1px solid var(--line);border-radius:14px;
    margin-bottom:.7rem;overflow:hidden;transition:all .2s;
  }
  details[open]{border-color:var(--moss);box-shadow:var(--shadow)}
  summary{padding:1.3rem 1.5rem;cursor:pointer;font-weight:500;color:var(--moss-deep);font-size:1rem;list-style:none;display:flex;justify-content:space-between;align-items:center}
  summary::-webkit-details-marker{display:none}
  summary::after{content:'+';font-size:1.4rem;color:var(--accent);transition:transform .2s;font-family:'Fraunces',serif;font-weight:300}
  details[open] summary::after{transform:rotate(45deg)}
  details > div{padding:0 1.5rem 1.3rem;color:var(--ink-2);font-size:.95rem;line-height:1.7}

  /* Apply */
  .apply{background:var(--moss-deep);color:#f5f1ea;text-align:center}
  .apply h2{color:#f5f1ea;font-size:clamp(2rem,4vw,3.4rem)}
  .apply p{color:#d8cdb8;font-size:1.1rem;max-width:600px;margin:0 auto 2rem}
  .apply-cards{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem;margin-top:3rem;max-width:780px;margin-left:auto;margin-right:auto;text-align:left}
  @media(max-width:760px){.apply-cards{grid-template-columns:1fr}}
  .apply-card{background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.1);padding:1.5rem;border-radius:14px}
  .apply-card .step-num{display:inline-grid;place-items:center;width:28px;height:28px;border-radius:50%;background:var(--accent);color:#fff;font-size:.85rem;font-weight:600;margin-bottom:.8rem}
  .apply-card h4{color:#f5f1ea;font-family:'Inter',sans-serif;font-size:1rem;font-weight:600;margin:0 0 .4rem}
  .apply-card span{color:#d8cdb8;font-size:.85rem}

  /* Waitlist */
  .waitlist-form{display:flex;gap:.7rem;max-width:480px;margin:2.5rem auto 0;flex-wrap:wrap;justify-content:center}
  .waitlist-form input{
    flex:1;min-width:240px;padding:.95rem 1.2rem;border-radius:999px;border:1px solid rgba(255,255,255,.2);
    background:rgba(255,255,255,.08);color:#f5f1ea;font-family:inherit;font-size:.95rem;
  }
  .waitlist-form input::placeholder{color:rgba(245,241,234,.5)}
  .waitlist-form input:focus{outline:none;border-color:var(--accent);background:rgba(255,255,255,.12)}
  .waitlist-form button{background:var(--accent);color:#fff}
  .waitlist-form button:hover{background:var(--accent-2);color:var(--moss-deep)}

  /* Footer */
  footer{background:var(--bg);padding:3rem 0 2rem;border-top:1px solid var(--line)}
  .foot-grid{display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:2rem;margin-bottom:2rem}
  @media(max-width:760px){.foot-grid{grid-template-columns:1fr 1fr}}
  .foot-col h5{font-family:'Inter',sans-serif;font-size:.82rem;text-transform:uppercase;letter-spacing:.1em;color:var(--moss-deep);margin:0 0 1rem;font-weight:600}
  .foot-col a{display:block;color:var(--ink-2);font-size:.9rem;padding:.25rem 0}
  .foot-col a:hover{color:var(--accent)}
  .foot-bottom{border-top:1px solid var(--line);padding-top:1.5rem;display:flex;justify-content:space-between;flex-wrap:wrap;gap:1rem;font-size:.82rem;color:var(--ink-2)}
  .disclaimer{max-width:780px;font-size:.78rem;color:var(--ink-2);line-height:1.6;margin:1.5rem 0}

  /* Animations */
  .fade-in{opacity:0;transform:translateY(20px);transition:opacity .8s ease, transform .8s ease}
  .fade-in.visible{opacity:1;transform:translateY(0)}
</style>
</head>
<body>

<nav>
  <div class="nav-inner">
    <div class="logo">ReviveWell</div>
    <div class="nav-links">
      <a href="#program">Program</a>
      <a href="#pillars">Pillars</a>
      <a href="#pricing">Pricing</a>
      <a href="#faq">FAQ</a>
      <a href="application.html" class="nav-cta">Apply →</a>
    </div>
  </div>
</nav>

<header class="hero">
  <div class="container">
    <div class="hero-grid">
      <div>
        <div class="badge"><span class="dot"></span>Founding Cohort · 8–12 spots</div>
        <h1>Rebuild your <em>energy</em>, sleep, and gut — backed by labs, not guesses.</h1>
        <p class="hero-sub">A 6 or 12-month physician-led integrative wellness cohort. Functional labs, peptide therapy, and personalized protocols delivered with weekly cohort support and 1:1 provider time.</p>
        <div class="cta-row">
          <a href="application.html" class="btn btn-primary">Apply for the cohort →</a>
          <a href="#program" class="btn btn-ghost">How it works</a>
        </div>
        <div class="hero-stats">
          <div class="stat"><strong>6–12mo</strong><span>Program length</span></div>
          <div class="stat"><strong>3 pillars</strong><span>Gut · Sleep · Energy</span></div>
          <div class="stat"><strong>8–12</strong><span>Founding members</span></div>
        </div>
      </div>
      <div class="hero-visual">
        <svg viewBox="0 0 400 500" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice">
          <defs>
            <linearGradient id="g1" x1="0" y1="0" x2="1" y2="1">
              <stop offset="0%" stop-color="#4a6b53"/>
              <stop offset="100%" stop-color="#2f4a37"/>
            </linearGradient>
            <radialGradient id="g2" cx="50%" cy="40%" r="60%">
              <stop offset="0%" stop-color="#e8b894" stop-opacity=".4"/>
              <stop offset="100%" stop-color="#c8794a" stop-opacity="0"/>
            </radialGradient>
          </defs>
          <rect width="400" height="500" fill="url(#g1)"/>
          <circle cx="200" cy="200" r="180" fill="url(#g2)"/>
          <!-- abstract botanical -->
          <g stroke="#e8b894" stroke-width="1.5" fill="none" opacity=".7">
            <path d="M 200 480 Q 200 350 200 220" />
            <path d="M 200 380 Q 150 360 130 320" />
            <path d="M 200 380 Q 250 360 270 320" />
            <path d="M 200 320 Q 160 300 145 270" />
            <path d="M 200 320 Q 240 300 255 270" />
            <path d="M 200 260 Q 175 245 165 220" />
            <path d="M 200 260 Q 225 245 235 220" />
          </g>
          <g fill="#e8b894" opacity=".8">
            <ellipse cx="130" cy="320" rx="22" ry="10" transform="rotate(-30 130 320)"/>
            <ellipse cx="270" cy="320" rx="22" ry="10" transform="rotate(30 270 320)"/>
            <ellipse cx="145" cy="270" rx="18" ry="8" transform="rotate(-25 145 270)"/>
            <ellipse cx="255" cy="270" rx="18" ry="8" transform="rotate(25 255 270)"/>
            <ellipse cx="165" cy="220" rx="14" ry="6" transform="rotate(-20 165 220)"/>
            <ellipse cx="235" cy="220" rx="14" ry="6" transform="rotate(20 235 220)"/>
            <circle cx="200" cy="200" r="14"/>
          </g>
          <g fill="#f5f1ea" opacity=".5">
            <circle cx="80" cy="100" r="1.5"/>
            <circle cx="320" cy="80" r="2"/>
            <circle cx="350" cy="180" r="1"/>
            <circle cx="60" cy="220" r="1.5"/>
            <circle cx="40" cy="380" r="1"/>
            <circle cx="360" cy="420" r="1.5"/>
          </g>
        </svg>
        <div class="float-card fc-1">
          <div class="fc-icon">L</div>
          <div class="fc-text"><strong>Lab-validated</strong><span>GI-MAP · DUTCH · OAT</span></div>
        </div>
        <div class="float-card fc-2">
          <div class="fc-icon">P</div>
          <div class="fc-text"><strong>Peptide protocols</strong><span>GLP-1 · NAD+ · Glutathione</span></div>
        </div>
      </div>
    </div>
  </div>
</header>

<section class="trust">
  <div class="container">
    <div class="trust-row">
      <span>Physician-led</span>
      <span>HIPAA-compliant</span>
      <span>HSA / FSA eligible</span>
      <span>Founding cohort 2026</span>
    </div>
  </div>
</section>

<section id="problem">
  <div class="container">
    <span class="section-label">The Problem</span>
    <h2>You've tried everything. The labs say "normal." You still feel off.</h2>
    <p class="lede">Conventional medicine treats numbers in isolation. The cohort treats the whole picture — gut, sleep, hormones, mitochondria — using the labs and protocols that find what standard panels miss.</p>
    <div class="problem-grid">
      <div class="problem-card">
        <h3><span class="num">1</span>Energy that won't return</h3>
        <p>Sleeping 8 hours and still tired. Coffee stops working. Workouts wreck you for days. Cortisol, mitochondria, and thyroid often need targeted support — and standard TSH won't catch it.</p>
      </div>
      <div class="problem-card">
        <h3><span class="num">2</span>A gut that runs the show</h3>
        <p>Bloating, irregularity, food sensitivities, brain fog. When the microbiome is dysregulated, every other system pays the cost. We map it with GI-MAP and rebuild it in phases.</p>
      </div>
      <div class="problem-card">
        <h3><span class="num">3</span>Sleep that doesn't restore</h3>
        <p>Falling asleep is one thing. Staying in deep, restorative sleep is another. Hormones, blood sugar, nervous system — when they're off, the body never gets to repair.</p>
      </div>
    </div>
  </div>
</section>

<section id="pillars" class="pillars">
  <div class="container">
    <span class="section-label" style="color:var(--accent-2)">Three Pillars · One Cohort</span>
    <h2>Built around the systems most people ignore — until they have to.</h2>
    <p class="lede">Every protocol is layered to support the next. Gut comes first because nothing else absorbs without it. Sleep comes next because nothing repairs without it. Energy is the outcome of doing those two right.</p>
    <div class="pillar-grid">
      <div class="pillar">
        <div class="pillar-icon">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M12 1v6m0 10v6m11-11h-6m-10 0H1"/></svg>
        </div>
        <h3>Gut</h3>
        <p style="color:#d8cdb8;font-size:.95rem">Map the microbiome. Reduce inflammation. Rebuild the lining.</p>
        <ul>
          <li>GI-MAP comprehensive stool analysis</li>
          <li>5R protocol (Remove, Replace, Reinoculate, Repair, Rebalance)</li>
          <li>GLP-2 peptide support where indicated</li>
          <li>Targeted antimicrobial / probiotic phasing</li>
          <li>Food reintroduction roadmap</li>
        </ul>
      </div>
      <div class="pillar">
        <div class="pillar-icon">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"/></svg>
        </div>
        <h3>Sleep</h3>
        <p style="color:#d8cdb8;font-size:.95rem">Track the signal. Tune the inputs. Restore deep sleep.</p>
        <ul>
          <li>Wearable data integration (Oura · WHOOP · 8sleep)</li>
          <li>Cortisol rhythm via DUTCH testing</li>
          <li>Light, temperature, glucose protocols</li>
          <li>Targeted nutraceuticals (Mg-glycinate, glycine, l-theanine)</li>
          <li>Hormone optimization layer (12-mo track)</li>
        </ul>
      </div>
      <div class="pillar">
        <div class="pillar-icon">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
        </div>
        <h3>Energy</h3>
        <p style="color:#d8cdb8;font-size:.95rem">Mitochondrial repair. Metabolic flexibility. Real, sustainable drive.</p>
        <ul>
          <li>OAT (Organic Acids) for mitochondrial markers</li>
          <li>NAD+ protocol — IV/IM/oral pathway</li>
          <li>Glutathione support for detox capacity</li>
          <li>GLP-1 metabolic support where appropriate</li>
          <li>Movement, fueling, and recovery framework</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="program" class="inside">
  <div class="container">
    <span class="section-label">What's Inside</span>
    <h2>Everything you need. Nothing you don't.</h2>
    <p class="lede">A real program — not a course, not a coaching call, not a supplement subscription. Provider-led care delivered in cohort format so you get the benefits of community plus 1:1 attention.</p>
    <div class="inside-grid">
      <ul class="inside-list">
        <li><div class="check">✓</div><div><strong>Comprehensive baseline labs</strong><span>GI-MAP, DUTCH, OAT, micronutrient, full metabolic, inflammation markers, hormones — included.</span></div></li>
        <li><div class="check">✓</div><div><strong>Personalized supplement protocol</strong><span>Built from your lab data. Adjusted at every retest. Pharmacy-grade through partner discount.</span></div></li>
        <li><div class="check">✓</div><div><strong>Peptide screening &amp; prescription path</strong><span>GLP-1, GLP-2, NAD+, glutathione — physician evaluation, licensed compounding pharmacy, ongoing monitoring.</span></div></li>
        <li><div class="check">✓</div><div><strong>Weekly cohort calls</strong><span>Live teaching, Q&amp;A, group accountability. Recordings posted in the private workspace.</span></div></li>
        <li><div class="check">✓</div><div><strong>1:1 provider visits</strong><span>4 visits in 6-month, 8 visits in 12-month. Plus async messaging.</span></div></li>
        <li><div class="check">✓</div><div><strong>Private cohort community</strong><span>Notion + secure messaging. Curriculum, protocols, and peer support — all in one place.</span></div></li>
        <li><div class="check">✓</div><div><strong>Outcome tracking dashboard</strong><span>See your gut, sleep, and energy markers move over the program.</span></div></li>
      </ul>
      <div class="timeline">
        <h4>The four-phase journey</h4>
        <div class="phase"><div class="phase-num">01</div><div><span class="phase-name">Discovery</span><span class="phase-desc">Onboarding, baseline labs, comprehensive intake</span></div></div>
        <div class="phase"><div class="phase-num">02</div><div><span class="phase-name">Foundation</span><span class="phase-desc">Gut repair, sleep architecture, supplement layer</span></div></div>
        <div class="phase"><div class="phase-num">03</div><div><span class="phase-name">Activation</span><span class="phase-desc">Peptide protocols, energy systems, mid-program retest</span></div></div>
        <div class="phase"><div class="phase-num">04</div><div><span class="phase-name">Integration</span><span class="phase-desc">Sustainability, exit labs, maintenance plan</span></div></div>
      </div>
    </div>
  </div>
</section>

<section id="pricing" class="pricing">
  <div class="container">
    <span class="section-label">Founding Cohort Pricing</span>
    <h2>Two tracks. Both physician-led. Founding rates locked.</h2>
    <p class="lede">Founding cohort pricing is ~25% below standard rates and never increases for renewals. Pay-in-full, 3-pay, or monthly options available.</p>
    <div class="price-grid">
      <div class="price-card">
        <div class="price-tier">Reset · 6 Months</div>
        <h3>The 6-Month Track</h3>
        <div class="price-num">$4,500<span style="font-size:1rem;color:var(--ink-2)"> – $5,500</span></div>
        <div class="price-sub">One-time, payment plans available · HSA/FSA eligible</div>
        <ul class="price-features">
          <li>Comprehensive baseline + exit labs</li>
          <li>Personalized supplement protocol</li>
          <li>Peptide path (if indicated)</li>
          <li>Weekly cohort calls (24 weeks)</li>
          <li>4 × 1:1 provider visits</li>
          <li>Private community access</li>
          <li>Outcome tracking dashboard</li>
        </ul>
        <a href="application.html" class="btn btn-ghost" style="justify-content:center">Apply for 6-month →</a>
      </div>
      <div class="price-card featured">
        <span class="featured-tag">Most chosen</span>
        <div class="price-tier">Restore · 12 Months</div>
        <h3>The 12-Month Track</h3>
        <div class="price-num">$9,500<span style="font-size:1rem;color:var(--ink-2)"> – $11,500</span></div>
        <div class="price-sub">One-time, payment plans available · HSA/FSA eligible</div>
        <ul class="price-features">
          <li>Everything in the 6-month track</li>
          <li>Quarterly retesting (4 panels total)</li>
          <li>Extended peptide cycling protocol</li>
          <li>Hormone optimization layer</li>
          <li>8 × 1:1 provider visits</li>
          <li>Bi-weekly 1:1 cadence + maintenance phase</li>
          <li>Live retreat day (in-person or virtual)</li>
        </ul>
        <a href="application.html" class="btn btn-primary" style="justify-content:center">Apply for 12-month →</a>
      </div>
    </div>
    <p style="text-align:center;margin-top:2rem;font-size:.88rem;color:var(--ink-2)">Cost of supplements (~$150–$300/mo) and peptides (~$200–$600/mo) not included in program fee. Pharmacy partner discounts apply.</p>
  </div>
</section>

<section id="faq">
  <div class="container-narrow">
    <span class="section-label" style="display:block;text-align:center">Common Questions</span>
    <h2 style="text-align:center">Before you apply</h2>
    <div class="faq-list">
      <details>
        <summary>Who is this cohort actually for?</summary>
        <div>High-functioning adults — usually 35–55 — who've hit a wall with conventional care. Common entry points: persistent fatigue, gut issues that won't resolve, sleep that doesn't restore, weight that won't budge, or hormone shifts that aren't being addressed by their primary doctor. You should be willing to do labs, journal data, and engage with the cohort weekly.</div>
      </details>
      <details>
        <summary>Who is this NOT for?</summary>
        <div>Anyone looking for a quick GLP-1 prescription, a generic supplement subscription, or a "just tell me what to take" experience. We don't treat acute illness, active eating disorders, or anyone currently pregnant or trying to conceive in the program window.</div>
      </details>
      <details>
        <summary>What about peptides — are they safe? Are they legal?</summary>
        <div>All peptides we prescribe are sourced through licensed compounding pharmacies in the US and require physician evaluation. We follow current regulatory guidance and adjust protocols as that landscape evolves. Not every participant gets every peptide — we screen for clinical fit and monitor closely throughout.</div>
      </details>
      <details>
        <summary>How is this different from a typical functional medicine practice?</summary>
        <div>Three things. First, cohort format — you get peer support and a structured arc instead of one-off appointments. Second, depth — labs, peptides, supplements, and behavioral protocols are all in one program rather than added piecemeal. Third, accountability — weekly check-ins and tracking mean things actually get done.</div>
      </details>
      <details>
        <summary>Do you accept insurance?</summary>
        <div>No. Program fees are out-of-pocket but HSA/FSA eligible in most cases. We provide superbills for medical visits where applicable. The pharmacy-grade supplements and peptide protocols are also out-of-pocket but at partner discount rates.</div>
      </details>
      <details>
        <summary>What's the time commitment?</summary>
        <div>Plan for ~3 hours per week: one cohort call (60–90 min), one shorter learning module, plus daily logging (5–10 min). 1:1 provider visits are scheduled separately. The first two weeks are heavier (intake, labs, baselines).</div>
      </details>
      <details>
        <summary>Can my partner / spouse join too?</summary>
        <div>If both are accepted, we offer 15% off the second seat. Both must complete the application independently — fit matters.</div>
      </details>
      <details>
        <summary>What states do you currently serve?</summary>
        <div>Telehealth licensure varies. Most US states are covered. We confirm during the application/discovery call. If we can't serve you clinically, we'll let you know within 48 hours.</div>
      </details>
      <details>
        <summary>What happens if I want to stop?</summary>
        <div>Full refund within the first 14 days, before labs are processed. After that, you may pause once during the program for up to 30 days. Refunds after labs are processed are pro-rated minus direct lab costs incurred.</div>
      </details>
    </div>
  </div>
</section>

<section id="apply" class="apply">
  <div class="container">
    <span class="section-label" style="color:var(--accent-2)">Founding Cohort · 8–12 Spots</span>
    <h2>Three steps to apply.</h2>
    <p>Applications close when we hit cohort capacity. After that, the waitlist opens for cohort #2 at standard pricing.</p>

    <div class="apply-cards">
      <div class="apply-card">
        <div class="step-num">1</div>
        <h4>Application</h4>
        <span>~10 minutes. Tells us your goals, history, and fit.</span>
      </div>
      <div class="apply-card">
        <div class="step-num">2</div>
        <h4>Discovery call</h4>
        <span>30-min conversation with our team. Mutual fit check.</span>
      </div>
      <div class="apply-card">
        <div class="step-num">3</div>
        <h4>Clinical intake + onboarding</h4>
        <span>If invited, complete intake forms and lab orders to begin.</span>
      </div>
    </div>

    <div style="margin-top:3rem">
      <a href="application.html" class="btn btn-primary" style="background:var(--accent);color:#fff;padding:1.1rem 2.5rem;font-size:1.05rem">Start your application →</a>
    </div>

    <div style="margin-top:4rem;padding-top:3rem;border-top:1px solid rgba(255,255,255,.1)">
      <h3 style="color:#f5f1ea;font-size:1.4rem">Not ready? Join the waitlist.</h3>
      <p>Get the founder's note, behind-the-scenes content, and first access to cohort #2.</p>
      <form class="waitlist-form" onsubmit="handleWaitlist(event)">
        <input type="email" name="email" placeholder="your@email.com" required />
        <button type="submit" class="btn">Join waitlist</button>
      </form>
      <div id="waitlist-msg" style="margin-top:1rem;font-size:.9rem;color:var(--accent-2)"></div>
    </div>
  </div>
</section>

<footer>
  <div class="container">
    <div class="foot-grid">
      <div class="foot-col">
        <div class="logo" style="margin-bottom:.7rem">ReviveWell</div>
        <p style="font-size:.88rem;color:var(--ink-2);max-width:280px">Physician-led integrative wellness. Labs, peptides, and protocols — built around how the body actually works.</p>
      </div>
      <div class="foot-col">
        <h5>Program</h5>
        <a href="#program">How it works</a>
        <a href="#pillars">The pillars</a>
        <a href="#pricing">Pricing</a>
        <a href="#faq">FAQ</a>
      </div>
      <div class="foot-col">
        <h5>Apply</h5>
        <a href="application.html">Application</a>
        <a href="#apply">Waitlist</a>
        <a href="mailto:info@revivewell.co">Contact</a>
      </div>
      <div class="foot-col">
        <h5>Legal</h5>
        <a href="#">Privacy</a>
        <a href="#">Terms</a>
        <a href="#">Disclaimers</a>
      </div>
    </div>
    <p class="disclaimer"><strong>Medical disclaimer:</strong> The information on this page is for educational purposes only and does not constitute medical advice. Statements about peptide therapy, supplements, and lab testing have not been evaluated by the FDA. The program does not diagnose, treat, cure, or prevent disease. Peptide prescriptions require physician evaluation and are dispensed through licensed compounding pharmacies. Individual results vary. Consult your healthcare provider before starting any new health protocol.</p>
    <div class="foot-bottom">
      <span>© 2026 ReviveWell. All rights reserved.</span>
      <span>Founding Cohort · Limited to 8–12 participants</span>
    </div>
  </div>
</footer>

<script>
  // Waitlist form handler — wire to email provider (ConvertKit, Klaviyo, etc.)
  function handleWaitlist(e){
    e.preventDefault();
    const form = e.target;
    const email = form.email.value;
    const msg = document.getElementById('waitlist-msg');
    // TODO: replace with actual email API endpoint (ConvertKit / Klaviyo)
    // fetch('YOUR_FORM_ENDPOINT', { method:'POST', body: JSON.stringify({email}) })
    msg.textContent = "You're on the list. Check your inbox for a confirmation.";
    form.reset();
  }

  // Fade-in on scroll
  const io = new IntersectionObserver((entries) => {
    entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('visible'); });
  }, { threshold: 0.15 });
  document.querySelectorAll('section, .hero-grid > div').forEach(el => {
    el.classList.add('fade-in');
    io.observe(el);
  });

  // Smooth-scroll anchors
  document.querySelectorAll('a[href^="#"]').forEach(a => {
    a.addEventListener('click', (e) => {
      const id = a.getAttribute('href').slice(1);
      const target = document.getElementById(id);
      if (target){ e.preventDefault(); target.scrollIntoView({behavior:'smooth', block:'start'}); }
    });
  });
</script>

</body>
</html>
