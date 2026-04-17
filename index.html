<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Iron Road MC</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --accent: #D85A30;
    --accent-dark: #b84a22;
    --black: #111111;
    --dark: #1a1a1a;
    --dark2: #242424;
    --mid: #333333;
    --muted: #888888;
    --light: #cccccc;
    --white: #ffffff;
    --border: rgba(255,255,255,0.08);
    --radius: 10px;
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
    background: var(--black);
    color: var(--white);
    line-height: 1.65;
    font-size: 16px;
  }

  /* ── NAV ── */
  nav {
    position: sticky; top: 0; z-index: 100;
    background: rgba(17,17,17,0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
    padding: 0 5vw;
    display: flex; align-items: center; justify-content: space-between;
    height: 64px;
  }
  .nav-logo {
    display: flex; align-items: center; gap: 10px;
    font-size: 18px; font-weight: 700; letter-spacing: 0.03em;
    text-decoration: none; color: var(--white);
  }
  .logo-icon {
    width: 36px; height: 36px; border-radius: 50%;
    background: var(--accent);
    display: flex; align-items: center; justify-content: center;
    font-size: 16px;
  }
  .nav-links { display: flex; gap: 32px; list-style: none; }
  .nav-links a {
    color: var(--light); text-decoration: none;
    font-size: 14px; font-weight: 500;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--accent); }
  .nav-join {
    background: var(--accent); color: var(--white);
    padding: 8px 20px; border-radius: 6px;
    text-decoration: none; font-size: 14px; font-weight: 600;
    transition: background 0.2s;
  }
  .nav-join:hover { background: var(--accent-dark); }

  .hamburger {
    display: none; flex-direction: column; gap: 5px;
    cursor: pointer; background: none; border: none; padding: 4px;
  }
  .hamburger span {
    display: block; width: 24px; height: 2px;
    background: var(--white); border-radius: 2px;
    transition: all 0.3s;
  }
  .mobile-menu {
    display: none;
    background: var(--dark); border-bottom: 1px solid var(--border);
    padding: 20px 5vw;
    flex-direction: column; gap: 16px;
  }
  .mobile-menu a {
    color: var(--light); text-decoration: none;
    font-size: 16px; font-weight: 500;
  }
  .mobile-menu a:hover { color: var(--accent); }
  .mobile-menu.open { display: flex; }

  /* ── HERO ── */
  #home {
    min-height: 100vh;
    display: flex; align-items: center;
    padding: 80px 5vw;
    background: var(--black);
    position: relative; overflow: hidden;
  }
  .hero-bg {
    position: absolute; inset: 0;
    background:
      radial-gradient(ellipse 60% 50% at 80% 50%, rgba(216,90,48,0.08) 0%, transparent 70%),
      repeating-linear-gradient(
        45deg,
        transparent,
        transparent 60px,
        rgba(255,255,255,0.012) 60px,
        rgba(255,255,255,0.012) 61px
      );
  }
  .hero-content { position: relative; max-width: 680px; }
  .hero-badge {
    display: inline-flex; align-items: center; gap: 8px;
    background: rgba(216,90,48,0.15); border: 1px solid rgba(216,90,48,0.3);
    color: #f0936d; font-size: 13px; font-weight: 600;
    padding: 6px 14px; border-radius: 20px;
    margin-bottom: 28px; letter-spacing: 0.05em;
    text-transform: uppercase;
  }
  .hero-badge::before {
    content: ''; width: 6px; height: 6px;
    border-radius: 50%; background: var(--accent);
    animation: pulse 2s ease-in-out infinite;
  }
  @keyframes pulse {
    0%,100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.5; transform: scale(1.3); }
  }
  .hero h1 {
    font-size: clamp(42px, 7vw, 80px);
    font-weight: 800; line-height: 1.05;
    letter-spacing: -0.02em;
    margin-bottom: 24px;
  }
  .hero h1 span { color: var(--accent); }
  .hero-sub {
    font-size: 18px; color: #aaa; line-height: 1.7;
    margin-bottom: 40px; max-width: 520px;
  }
  .hero-btns { display: flex; gap: 14px; flex-wrap: wrap; }
  .btn-primary {
    background: var(--accent); color: var(--white);
    padding: 14px 30px; border-radius: 8px;
    text-decoration: none; font-size: 15px; font-weight: 700;
    transition: background 0.2s, transform 0.1s;
    display: inline-block;
  }
  .btn-primary:hover { background: var(--accent-dark); transform: translateY(-1px); }
  .btn-outline {
    background: transparent; color: var(--light);
    border: 1px solid rgba(255,255,255,0.25);
    padding: 14px 30px; border-radius: 8px;
    text-decoration: none; font-size: 15px; font-weight: 600;
    transition: border-color 0.2s, color 0.2s, transform 0.1s;
    display: inline-block;
  }
  .btn-outline:hover { border-color: var(--light); color: var(--white); transform: translateY(-1px); }
  .hero-stats {
    display: flex; gap: 40px; margin-top: 64px;
    padding-top: 40px; border-top: 1px solid var(--border);
  }
  .hero-stat-num { font-size: 32px; font-weight: 800; color: var(--white); }
  .hero-stat-label { font-size: 13px; color: var(--muted); margin-top: 2px; }

  /* ── SECTIONS ── */
  section { padding: 100px 5vw; }
  .section-label {
    font-size: 12px; font-weight: 700; letter-spacing: 0.12em;
    text-transform: uppercase; color: var(--accent);
    margin-bottom: 12px;
  }
  .section-title {
    font-size: clamp(28px, 4vw, 44px);
    font-weight: 800; line-height: 1.1; margin-bottom: 16px;
  }
  .section-sub { font-size: 17px; color: #999; max-width: 560px; line-height: 1.7; }

  /* ── ABOUT ── */
  #about { background: var(--dark); }
  .about-grid {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 60px; margin-top: 60px; align-items: start;
  }
  .about-text p { color: #bbb; margin-bottom: 20px; font-size: 16px; line-height: 1.8; }
  .about-values { display: flex; flex-direction: column; gap: 16px; margin-top: 8px; }
  .value-item {
    display: flex; align-items: flex-start; gap: 16px;
    background: var(--dark2); border: 1px solid var(--border);
    border-radius: var(--radius); padding: 20px;
  }
  .value-icon {
    width: 40px; height: 40px; border-radius: 8px;
    background: rgba(216,90,48,0.15);
    display: flex; align-items: center; justify-content: center;
    font-size: 18px; flex-shrink: 0;
  }
  .value-title { font-size: 15px; font-weight: 700; margin-bottom: 4px; }
  .value-desc { font-size: 13px; color: var(--muted); line-height: 1.6; }

  /* ── EVENTS ── */
  #events { background: var(--black); }
  .events-header { display: flex; justify-content: space-between; align-items: flex-end; margin-bottom: 40px; }
  .events-grid { display: flex; flex-direction: column; gap: 16px; }
  .event-card {
    background: var(--dark); border: 1px solid var(--border);
    border-radius: var(--radius);
    display: flex; align-items: center; gap: 24px;
    padding: 24px 28px;
    transition: border-color 0.2s, transform 0.15s;
    cursor: default;
  }
  .event-card:hover { border-color: rgba(216,90,48,0.4); transform: translateX(4px); }
  .event-date-box {
    text-align: center; min-width: 56px;
    padding-right: 24px; border-right: 1px solid var(--border);
  }
  .event-day { font-size: 28px; font-weight: 800; color: var(--accent); line-height: 1; }
  .event-month { font-size: 12px; color: var(--muted); text-transform: uppercase; letter-spacing: 0.07em; margin-top: 2px; }
  .event-info { flex: 1; }
  .event-name { font-size: 17px; font-weight: 700; margin-bottom: 4px; }
  .event-location { font-size: 13px; color: var(--muted); }
  .event-type {
    font-size: 11px; font-weight: 700; letter-spacing: 0.06em;
    text-transform: uppercase; padding: 5px 12px; border-radius: 20px;
  }
  .type-open { background: rgba(216,90,48,0.15); color: #f0936d; }
  .type-members { background: rgba(255,255,255,0.07); color: var(--muted); }

  /* ── GALLERY ── */
  #gallery { background: var(--dark); }
  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px; margin-top: 48px;
  }
  .gallery-item {
    aspect-ratio: 4/3;
    background: var(--dark2); border: 1px solid var(--border);
    border-radius: var(--radius); overflow: hidden;
    position: relative;
    display: flex; align-items: center; justify-content: center;
    cursor: pointer; transition: transform 0.2s, border-color 0.2s;
  }
  .gallery-item:hover { transform: scale(1.02); border-color: rgba(216,90,48,0.4); }
  .gallery-item:nth-child(1) { grid-column: span 2; }
  .gallery-placeholder {
    display: flex; flex-direction: column; align-items: center; gap: 10px;
    color: var(--muted); font-size: 13px; text-align: center;
  }
  .gallery-icon { font-size: 32px; opacity: 0.4; }
  .gallery-label {
    position: absolute; bottom: 12px; left: 12px; right: 12px;
    font-size: 13px; font-weight: 600; color: var(--white);
    background: rgba(0,0,0,0.6); padding: 6px 10px; border-radius: 6px;
  }

  /* ── MEMBERS ── */
  #members { background: var(--black); }
  .members-grid {
    display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px; margin-top: 48px;
  }
  .member-card {
    background: var(--dark); border: 1px solid var(--border);
    border-radius: var(--radius); padding: 24px;
    text-align: center;
    transition: border-color 0.2s, transform 0.15s;
  }
  .member-card:hover { border-color: rgba(216,90,48,0.35); transform: translateY(-3px); }
  .member-avatar {
    width: 60px; height: 60px; border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 20px; font-weight: 800; margin: 0 auto 14px;
  }
  .member-name { font-size: 16px; font-weight: 700; margin-bottom: 4px; }
  .member-role { font-size: 13px; color: var(--accent); font-weight: 600; }
  .member-since { font-size: 12px; color: var(--muted); margin-top: 6px; }

  /* ── JOIN ── */
  #join { background: var(--dark); }
  .join-wrap {
    max-width: 640px; margin: 0 auto; text-align: center;
  }
  .join-form { margin-top: 48px; text-align: left; }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .form-group { margin-bottom: 20px; }
  .form-group label {
    display: block; font-size: 13px; font-weight: 600;
    color: var(--light); margin-bottom: 8px;
  }
  .form-group input,
  .form-group select,
  .form-group textarea {
    width: 100%; background: var(--dark2);
    border: 1px solid rgba(255,255,255,0.12);
    border-radius: 8px; padding: 12px 16px;
    color: var(--white); font-size: 15px;
    font-family: inherit;
    transition: border-color 0.2s;
    appearance: none;
  }
  .form-group input:focus,
  .form-group select:focus,
  .form-group textarea:focus {
    outline: none; border-color: var(--accent);
  }
  .form-group textarea { resize: vertical; min-height: 120px; }
  .form-group select option { background: var(--dark2); }
  .form-submit {
    width: 100%; background: var(--accent); color: var(--white);
    border: none; padding: 16px; border-radius: 8px;
    font-size: 16px; font-weight: 700; cursor: pointer;
    transition: background 0.2s, transform 0.1s;
    margin-top: 8px;
  }
  .form-submit:hover { background: var(--accent-dark); transform: translateY(-1px); }
  .form-note { font-size: 13px; color: var(--muted); text-align: center; margin-top: 16px; }
  .success-msg {
    display: none; text-align: center;
    background: rgba(30,180,100,0.1); border: 1px solid rgba(30,180,100,0.3);
    border-radius: var(--radius); padding: 24px; margin-top: 16px;
    color: #5de8a0;
  }

  /* ── CONTACT ── */
  #contact { background: var(--black); }
  .contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; margin-top: 48px; }
  .contact-item {
    background: var(--dark); border: 1px solid var(--border);
    border-radius: var(--radius); padding: 28px;
  }
  .contact-icon { font-size: 24px; margin-bottom: 12px; }
  .contact-label { font-size: 12px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.1em; color: var(--muted); margin-bottom: 6px; }
  .contact-value { font-size: 16px; font-weight: 600; }
  .contact-value a { color: var(--accent); text-decoration: none; }
  .contact-value a:hover { text-decoration: underline; }
  .social-links { display: flex; gap: 12px; margin-top: 48px; }
  .social-link {
    background: var(--dark); border: 1px solid var(--border);
    border-radius: 8px; padding: 12px 20px;
    color: var(--light); text-decoration: none; font-size: 14px; font-weight: 600;
    transition: border-color 0.2s, color 0.2s;
  }
  .social-link:hover { border-color: var(--accent); color: var(--accent); }

  /* ── FOOTER ── */
  footer {
    background: var(--dark); border-top: 1px solid var(--border);
    padding: 40px 5vw;
    display: flex; justify-content: space-between; align-items: center;
    flex-wrap: wrap; gap: 16px;
  }
  .footer-logo { font-size: 16px; font-weight: 800; display: flex; align-items: center; gap: 8px; }
  .footer-copy { font-size: 13px; color: var(--muted); }
  .footer-links { display: flex; gap: 20px; }
  .footer-links a { font-size: 13px; color: var(--muted); text-decoration: none; }
  .footer-links a:hover { color: var(--accent); }

  /* ── RESPONSIVE ── */
  @media (max-width: 768px) {
    .nav-links, .nav-join { display: none; }
    .hamburger { display: flex; }
    .about-grid { grid-template-columns: 1fr; gap: 40px; }
    .form-row { grid-template-columns: 1fr; }
    .contact-grid { grid-template-columns: 1fr; }
    .gallery-grid { grid-template-columns: 1fr 1fr; }
    .gallery-item:nth-child(1) { grid-column: span 2; }
    .hero-stats { gap: 24px; flex-wrap: wrap; }
    .events-header { flex-direction: column; align-items: flex-start; gap: 16px; }
    footer { flex-direction: column; align-items: flex-start; }
  }
  @media (max-width: 480px) {
    .gallery-grid { grid-template-columns: 1fr; }
    .gallery-item:nth-child(1) { grid-column: span 1; }
    .members-grid { grid-template-columns: 1fr 1fr; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <a class="nav-logo" href="#home">
    <div class="logo-icon">&#9650;</div>
    Iron Road MC
  </a>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#events">Events</a></li>
    <li><a href="#gallery">Gallery</a></li>
    <li><a href="#members">Members</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <a class="nav-join" href="#join">Join the club</a>
  <button class="hamburger" onclick="toggleMenu()" aria-label="Toggle menu">
    <span></span><span></span><span></span>
  </button>
</nav>
<div class="mobile-menu" id="mobileMenu">
  <a href="#about" onclick="closeMenu()">About</a>
  <a href="#events" onclick="closeMenu()">Events</a>
  <a href="#gallery" onclick="closeMenu()">Gallery</a>
  <a href="#members" onclick="closeMenu()">Members</a>
  <a href="#contact" onclick="closeMenu()">Contact</a>
  <a href="#join" onclick="closeMenu()" style="color:var(--accent);font-weight:700;">Join the club</a>
</div>

<!-- HERO -->
<section id="home">
  <div class="hero-bg"></div>
  <div class="hero-content">
    <div class="hero-badge">Est. 2004 &mdash; Vilnius, Lithuania</div>
    <h1>Ride together.<br><span>Live free.</span></h1>
    <p class="hero-sub">Iron Road Motorcycle Club is a brotherhood of riders united by the open road, shared respect, and a passion for the machine. We ride hard, look out for each other, and welcome those who share our spirit.</p>
    <div class="hero-btns">
      <a href="#join" class="btn-primary">Join the club</a>
      <a href="#events" class="btn-outline">Upcoming rides</a>
    </div>
    <div class="hero-stats">
      <div>
        <div class="hero-stat-num">84</div>
        <div class="hero-stat-label">Active members</div>
      </div>
      <div>
        <div class="hero-stat-num">20+</div>
        <div class="hero-stat-label">Years on the road</div>
      </div>
      <div>
        <div class="hero-stat-num">12</div>
        <div class="hero-stat-label">Rides this year</div>
      </div>
      <div>
        <div class="hero-stat-num">3</div>
        <div class="hero-stat-label">Countries ridden</div>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="section-label">Our story</div>
  <div class="section-title">More than a club.<br>A family.</div>
  <div class="about-grid">
    <div class="about-text">
      <p>Iron Road MC was founded in 2004 by a small group of Vilnius riders who believed that motorcycling is more than a hobby — it's a way of life built on freedom, brotherhood, and mutual respect.</p>
      <p>Over two decades we've grown from a handful of friends to one of Lithuania's most respected motorcycle clubs, with members from all walks of life united by two wheels and an open horizon.</p>
      <p>We organize regular group rides across the Baltics, charity events, and an annual rally that draws riders from across Europe. Every member is a volunteer, every decision is made together.</p>
      <a href="#join" class="btn-primary" style="margin-top:8px; display:inline-block;">Become a member</a>
    </div>
    <div class="about-values">
      <div class="value-item">
        <div class="value-icon">&#9679;</div>
        <div>
          <div class="value-title">Brotherhood</div>
          <div class="value-desc">We look out for each other on and off the road. Iron Road members are family first, riders second.</div>
        </div>
      </div>
      <div class="value-item">
        <div class="value-icon">&#9650;</div>
        <div>
          <div class="value-title">Respect</div>
          <div class="value-desc">For the road, for other riders, for the communities we pass through. We ride with purpose and dignity.</div>
        </div>
      </div>
      <div class="value-item">
        <div class="value-icon">&#9632;</div>
        <div>
          <div class="value-title">Freedom</div>
          <div class="value-desc">No cages, no excuses. The open road is where we find clarity, community, and ourselves.</div>
        </div>
      </div>
      <div class="value-item">
        <div class="value-icon">&#9670;</div>
        <div>
          <div class="value-title">Craft</div>
          <div class="value-desc">We love machines. Understanding, maintaining, and improving your bike is part of being Iron Road.</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EVENTS -->
<section id="events">
  <div class="events-header">
    <div>
      <div class="section-label">Get out there</div>
      <div class="section-title">Upcoming rides &amp; events</div>
    </div>
    <a href="#contact" class="btn-outline" style="white-space:nowrap;">Get the newsletter</a>
  </div>
  <div class="events-grid">
    <div class="event-card">
      <div class="event-date-box">
        <div class="event-day">03</div>
        <div class="event-month">May</div>
      </div>
      <div class="event-info">
        <div class="event-name">Spring rally — Klaip&#279;da coastal run</div>
        <div class="event-location">Vilnius &#8594; Klaip&#279;da &middot; ~320 km each way</div>
      </div>
      <div class="event-type type-open">Open ride</div>
    </div>
    <div class="event-card">
      <div class="event-date-box">
        <div class="event-day">17</div>
        <div class="event-month">May</div>
      </div>
      <div class="event-info">
        <div class="event-name">Monthly club night</div>
        <div class="event-location">Garage HQ, Vilnius &middot; 19:00 start</div>
      </div>
      <div class="event-type type-members">Members only</div>
    </div>
    <div class="event-card">
      <div class="event-date-box">
        <div class="event-day">07</div>
        <div class="event-month">Jun</div>
      </div>
      <div class="event-info">
        <div class="event-name">Baltic Moto Fest 2026</div>
        <div class="event-location">Pan&#279;v&#279;&#382;ys fairgrounds &middot; 2-day event</div>
      </div>
      <div class="event-type type-open">Open ride</div>
    </div>
    <div class="event-card">
      <div class="event-date-box">
        <div class="event-day">21</div>
        <div class="event-month">Jun</div>
      </div>
      <div class="event-info">
        <div class="event-name">Midsummer night ride — Trakai</div>
        <div class="event-location">Vilnius &#8594; Trakai &#8594; Vilnius &middot; Evening departure</div>
      </div>
      <div class="event-type type-open">Open ride</div>
    </div>
    <div class="event-card">
      <div class="event-date-box">
        <div class="event-day">12</div>
        <div class="event-month">Jul</div>
      </div>
      <div class="event-info">
        <div class="event-name">Annual Iron Road rally</div>
        <div class="event-location">Druskininkai &middot; 3-day club gathering</div>
      </div>
      <div class="event-type type-members">Members only</div>
    </div>
  </div>
</section>

<!-- GALLERY -->
<section id="gallery">
  <div class="section-label">On the road</div>
  <div class="section-title">Gallery</div>
  <p class="section-sub">Moments from our rides, rallies, and wrenching sessions. Replace these placeholders with your own photos.</p>
  <div class="gallery-grid">
    <div class="gallery-item">
      <div class="gallery-placeholder">
        <div class="gallery-icon">&#128247;</div>
        <div>Add your hero photo here<br><small>Recommended: 1200 &times; 600px</small></div>
      </div>
      <div class="gallery-label">Spring rally 2025 &mdash; Klaip&#279;da</div>
    </div>
    <div class="gallery-item">
      <div class="gallery-placeholder">
        <div class="gallery-icon">&#128247;</div>
        <div>Photo 2</div>
      </div>
      <div class="gallery-label">Trakai evening ride</div>
    </div>
    <div class="gallery-item">
      <div class="gallery-placeholder">
        <div class="gallery-icon">&#128247;</div>
        <div>Photo 3</div>
      </div>
      <div class="gallery-label">Annual rally 2024</div>
    </div>
    <div class="gallery-item">
      <div class="gallery-placeholder">
        <div class="gallery-icon">&#128247;</div>
        <div>Photo 4</div>
      </div>
      <div class="gallery-label">Garage night</div>
    </div>
    <div class="gallery-item">
      <div class="gallery-placeholder">
        <div class="gallery-icon">&#128247;</div>
        <div>Photo 5</div>
      </div>
      <div class="gallery-label">Baltic Moto Fest 2025</div>
    </div>
  </div>
</section>

<!-- MEMBERS / OFFICERS -->
<section id="members">
  <div class="section-label">The crew</div>
  <div class="section-title">Club officers</div>
  <p class="section-sub">The people who keep Iron Road MC rolling. Update names, roles, and initials below to match your real officers.</p>
  <div class="members-grid">
    <div class="member-card">
      <div class="member-avatar" style="background:rgba(216,90,48,0.18);color:#f0936d;">AK</div>
      <div class="member-name">Andrius K.</div>
      <div class="member-role">President</div>
      <div class="member-since">Member since 2004</div>
    </div>
    <div class="member-card">
      <div class="member-avatar" style="background:rgba(93,202,165,0.15);color:#5dcaa5;">MB</div>
      <div class="member-name">Marius B.</div>
      <div class="member-role">Vice president</div>
      <div class="member-since">Member since 2007</div>
    </div>
    <div class="member-card">
      <div class="member-avatar" style="background:rgba(55,138,221,0.15);color:#85b7eb;">RP</div>
      <div class="member-name">Rasa P.</div>
      <div class="member-role">Secretary</div>
      <div class="member-since">Member since 2011</div>
    </div>
    <div class="member-card">
      <div class="member-avatar" style="background:rgba(127,119,221,0.15);color:#afa9ec;">TJ</div>
      <div class="member-name">Tomas J.</div>
      <div class="member-role">Road captain</div>
      <div class="member-since">Member since 2009</div>
    </div>
    <div class="member-card">
      <div class="member-avatar" style="background:rgba(216,90,48,0.12);color:#f0936d;">EV</div>
      <div class="member-name">Edvinas V.</div>
      <div class="member-role">Treasurer</div>
      <div class="member-since">Member since 2015</div>
    </div>
    <div class="member-card">
      <div class="member-avatar" style="background:rgba(255,255,255,0.07);color:#888;">SK</div>
      <div class="member-name">Saulius K.</div>
      <div class="member-role">Sergeant-at-arms</div>
      <div class="member-since">Member since 2013</div>
    </div>
  </div>
</section>

<!-- JOIN -->
<section id="join">
  <div class="join-wrap">
    <div class="section-label">Ride with us</div>
    <div class="section-title">Apply for membership</div>
    <p class="section-sub" style="margin: 0 auto 8px;">Applications are reviewed by the club council. We accept new members twice a year — spring and autumn. Fill in the form and we'll be in touch.</p>

    <div class="join-form">
      <div class="form-row">
        <div class="form-group">
          <label for="fname">First name</label>
          <input type="text" id="fname" placeholder="Jonas">
        </div>
        <div class="form-group">
          <label for="lname">Last name</label>
          <input type="text" id="lname" placeholder="Petrauskas">
        </div>
      </div>
      <div class="form-group">
        <label for="email">Email address</label>
        <input type="email" id="email" placeholder="jonas@example.com">
      </div>
      <div class="form-group">
        <label for="phone">Phone number</label>
        <input type="tel" id="phone" placeholder="+370 600 00000">
      </div>
      <div class="form-group">
        <label for="bike">What do you ride?</label>
        <input type="text" id="bike" placeholder="e.g. Harley-Davidson Sportster 883">
      </div>
      <div class="form-group">
        <label for="experience">Years of riding experience</label>
        <select id="experience">
          <option value="">Select...</option>
          <option>Less than 1 year</option>
          <option>1&ndash;3 years</option>
          <option>3&ndash;7 years</option>
          <option>7&ndash;15 years</option>
          <option>15+ years</option>
        </select>
      </div>
      <div class="form-group">
        <label for="message">Tell us about yourself and why you want to join</label>
        <textarea id="message" placeholder="A few words about your riding background, what draws you to Iron Road MC, and anything else you'd like us to know..."></textarea>
      </div>
      <button class="form-submit" onclick="submitForm()">Send application</button>
      <p class="form-note">We respect your privacy. Your details are only shared with club officers.</p>
      <div class="success-msg" id="successMsg">
        <div style="font-size:28px;margin-bottom:8px;">&#10003;</div>
        <div style="font-size:18px;font-weight:700;margin-bottom:8px;">Application received!</div>
        <div style="color:#5de8a0;">We'll review your application and get back to you within 2 weeks. Ride safe!</div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="section-label">Get in touch</div>
  <div class="section-title">Contact us</div>
  <p class="section-sub">Have a question? Want to join a ride as a guest? Reach out — we don't bite.</p>
  <div class="contact-grid">
    <div class="contact-item">
      <div class="contact-icon">&#9993;</div>
      <div class="contact-label">Email</div>
      <div class="contact-value"><a href="mailto:info@ironroadmc.lt">info@ironroadmc.lt</a></div>
    </div>
    <div class="contact-item">
      <div class="contact-icon">&#128205;</div>
      <div class="contact-label">Garage HQ</div>
      <div class="contact-value">Vilnius, Lithuania</div>
    </div>
    <div class="contact-item">
      <div class="contact-icon">&#128337;</div>
      <div class="contact-label">Club nights</div>
      <div class="contact-value">3rd Saturday of every month, 19:00</div>
    </div>
    <div class="contact-item">
      <div class="contact-icon">&#128241;</div>
      <div class="contact-label">WhatsApp / Signal</div>
      <div class="contact-value"><a href="tel:+37060000000">+370 600 00000</a></div>
    </div>
  </div>
  <div class="social-links">
    <a href="#" class="social-link">Facebook</a>
    <a href="#" class="social-link">Instagram</a>
    <a href="#" class="social-link">YouTube</a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">
    <div class="logo-icon" style="width:28px;height:28px;font-size:12px;border-radius:50%;background:var(--accent);display:flex;align-items:center;justify-content:center;">&#9650;</div>
    Iron Road MC
  </div>
  <div class="footer-copy">&copy; 2026 Iron Road MC &mdash; Vilnius, Lithuania. All rights reserved.</div>
  <div class="footer-links">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#events">Events</a>
    <a href="#join">Join</a>
  </div>
</footer>

<script>
  function toggleMenu() {
    document.getElementById('mobileMenu').classList.toggle('open');
  }
  function closeMenu() {
    document.getElementById('mobileMenu').classList.remove('open');
  }
  function submitForm() {
    var fname = document.getElementById('fname').value.trim();
    var email = document.getElementById('email').value.trim();
    if (!fname || !email) {
      alert('Please fill in at least your name and email.');
      return;
    }
    document.querySelector('.join-form form') && null;
    document.getElementById('successMsg').style.display = 'block';
    document.querySelector('.form-submit').style.display = 'none';
    document.getElementById('successMsg').scrollIntoView({ behavior: 'smooth', block: 'center' });
  }
  document.querySelectorAll('a[href^="#"]').forEach(function(a) {
    a.addEventListener('click', function(e) {
      var target = document.querySelector(this.getAttribute('href'));
      if (target) {
        e.preventDefault();
        target.scrollIntoView({ behavior: 'smooth' });
        closeMenu();
      }
    });
  });
</script>
</body>
</html>
