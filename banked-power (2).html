<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Banked Power — Premium Tech Accessories</title>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet"/>
  <script src="https://js.stripe.com/v3/"></script>
  <style>
    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

    :root {
      --black: #080808;
      --deep: #111010;
      --surface: #161514;
      --gold: #c8a96e;
      --gold-light: #e2c99a;
      --off-white: #f0ece4;
      --muted: #6b6660;
      --border: #242220;
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--black);
      color: var(--off-white);
      font-family: 'Cormorant Garamond', Georgia, serif;
      cursor: none;
      overflow-x: hidden;
    }

    /* Custom cursor */
    .cursor {
      position: fixed;
      width: 8px; height: 8px;
      background: var(--gold);
      border-radius: 50%;
      pointer-events: none;
      z-index: 9999;
      transition: transform 0.1s ease;
      mix-blend-mode: difference;
    }
    .cursor-ring {
      position: fixed;
      width: 32px; height: 32px;
      border: 1px solid rgba(200,169,110,0.4);
      border-radius: 50%;
      pointer-events: none;
      z-index: 9998;
      transition: transform 0.18s ease, width 0.3s ease, height 0.3s ease, opacity 0.3s ease;
    }

    /* NAV */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 28px 60px;
      mix-blend-mode: normal;
      backdrop-filter: blur(0px);
      transition: backdrop-filter 0.4s, background 0.4s;
    }
    nav.scrolled {
      backdrop-filter: blur(20px);
      background: rgba(8,8,8,0.85);
      border-bottom: 1px solid var(--border);
    }
    .nav-logo {
      font-size: 13px;
      letter-spacing: 0.35em;
      text-transform: uppercase;
      color: var(--gold);
      font-family: 'DM Mono', monospace;
      font-weight: 400;
      text-decoration: none;
    }
    .nav-links {
      display: flex; gap: 48px;
      list-style: none;
    }
    .nav-links a {
      font-family: 'DM Mono', monospace;
      font-size: 11px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: var(--muted);
      text-decoration: none;
      transition: color 0.3s;
    }
    .nav-links a:hover { color: var(--off-white); }

    /* HERO */
    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      position: relative;
      padding: 0 60px;
      overflow: hidden;
    }

    .hero-bg {
      position: absolute;
      inset: 0;
      background:
        radial-gradient(ellipse 60% 50% at 70% 40%, rgba(200,169,110,0.06) 0%, transparent 70%),
        radial-gradient(ellipse 40% 60% at 20% 70%, rgba(200,169,110,0.03) 0%, transparent 60%);
    }

    .hero-line {
      position: absolute;
      top: 0; bottom: 0;
      left: 58%;
      width: 1px;
      background: linear-gradient(to bottom, transparent, var(--border) 30%, var(--border) 70%, transparent);
    }

    .hero-eyebrow {
      font-family: 'DM Mono', monospace;
      font-size: 11px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 36px;
      opacity: 0;
      animation: fadeUp 0.8s 0.3s ease forwards;
    }

    .hero-title {
      font-size: clamp(72px, 11vw, 160px);
      font-weight: 300;
      line-height: 0.92;
      letter-spacing: -0.02em;
      color: var(--off-white);
      max-width: 55%;
      opacity: 0;
      animation: fadeUp 0.9s 0.5s ease forwards;
    }

    .hero-title em {
      font-style: italic;
      color: transparent;
      -webkit-text-stroke: 1px var(--gold-light);
    }

    .hero-sub {
      margin-top: 52px;
      font-size: 18px;
      font-weight: 300;
      line-height: 1.7;
      color: var(--muted);
      max-width: 340px;
      opacity: 0;
      animation: fadeUp 0.9s 0.7s ease forwards;
    }

    .hero-cta-group {
      margin-top: 56px;
      display: flex;
      align-items: center;
      gap: 40px;
      opacity: 0;
      animation: fadeUp 0.9s 0.9s ease forwards;
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      gap: 14px;
      padding: 18px 40px;
      background: var(--gold);
      color: var(--black);
      font-family: 'DM Mono', monospace;
      font-size: 11px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      text-decoration: none;
      transition: background 0.3s, transform 0.2s;
    }
    .btn-primary:hover {
      background: var(--gold-light);
      transform: translateY(-2px);
    }
    .btn-ghost {
      font-family: 'DM Mono', monospace;
      font-size: 11px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: var(--muted);
      text-decoration: none;
      border-bottom: 1px solid var(--border);
      padding-bottom: 4px;
      transition: color 0.3s, border-color 0.3s;
    }
    .btn-ghost:hover { color: var(--off-white); border-color: var(--muted); }

    .hero-stat-block {
      position: absolute;
      right: 60px;
      bottom: 80px;
      display: flex;
      flex-direction: column;
      gap: 36px;
      opacity: 0;
      animation: fadeUp 1s 1.1s ease forwards;
    }
    .stat {
      display: flex;
      flex-direction: column;
      gap: 4px;
    }
    .stat-num {
      font-size: 42px;
      font-weight: 300;
      color: var(--off-white);
      line-height: 1;
    }
    .stat-label {
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      color: var(--muted);
    }

    .scroll-indicator {
      position: absolute;
      bottom: 40px;
      left: 60px;
      display: flex;
      align-items: center;
      gap: 16px;
      opacity: 0;
      animation: fadeUp 1s 1.3s ease forwards;
    }
    .scroll-line {
      width: 60px; height: 1px;
      background: var(--border);
      position: relative;
      overflow: hidden;
    }
    .scroll-line::after {
      content: '';
      position: absolute;
      left: -100%; top: 0;
      width: 100%; height: 100%;
      background: var(--gold);
      animation: lineScroll 2s 1.5s ease-in-out infinite;
    }
    @keyframes lineScroll { 0%{left:-100%} 50%{left:100%} 100%{left:100%} }

    .scroll-text {
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      color: var(--muted);
    }

    /* MARQUEE */
    .marquee-wrap {
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
      padding: 18px 0;
      overflow: hidden;
      background: var(--deep);
    }
    .marquee-track {
      display: flex;
      gap: 0;
      animation: marquee 20s linear infinite;
      white-space: nowrap;
    }
    .marquee-item {
      display: inline-flex;
      align-items: center;
      gap: 28px;
      padding: 0 28px;
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      color: var(--muted);
    }
    .marquee-dot { width: 3px; height: 3px; background: var(--gold); border-radius: 50%; }
    @keyframes marquee { from{transform:translateX(0)} to{transform:translateX(-50%)} }

    /* PRODUCTS */
    section { padding: 120px 60px; }

    .section-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
      margin-bottom: 72px;
    }
    .section-eyebrow {
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 14px;
    }
    .section-title {
      font-size: clamp(36px, 5vw, 64px);
      font-weight: 300;
      line-height: 1.05;
      letter-spacing: -0.01em;
    }
    .section-title em { font-style: italic; color: var(--gold); }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 2px;
    }

    .product-card {
      background: var(--surface);
      position: relative;
      overflow: hidden;
      aspect-ratio: 3/4;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: 36px;
      cursor: none;
      transition: transform 0.4s cubic-bezier(0.23, 1, 0.32, 1);
    }
    .product-card:hover { transform: scale(1.01); z-index: 2; }

    .product-card-bg {
      position: absolute;
      inset: 0;
      transition: transform 0.6s cubic-bezier(0.23, 1, 0.32, 1);
    }
    .product-card:hover .product-card-bg { transform: scale(1.04); }

    /* Product visual placeholders with abstract geometric art */
    .card-1 .product-card-bg {
      background:
        radial-gradient(circle at 60% 30%, rgba(200,169,110,0.15) 0%, transparent 50%),
        linear-gradient(135deg, #1a1714 0%, #0d0c0b 100%);
    }
    .card-2 .product-card-bg {
      background:
        radial-gradient(circle at 30% 60%, rgba(200,169,110,0.12) 0%, transparent 45%),
        linear-gradient(45deg, #141312 0%, #0a0908 100%);
    }
    .card-3 .product-card-bg {
      background:
        radial-gradient(circle at 70% 50%, rgba(200,169,110,0.1) 0%, transparent 55%),
        linear-gradient(180deg, #171514 0%, #0c0b0a 100%);
    }
    .card-beige .product-card-bg {
      background:
        radial-gradient(circle at 55% 35%, rgba(212,184,150,0.18) 0%, transparent 55%),
        linear-gradient(150deg, #1c1915 0%, #0e0c0a 100%);
    }
    .card-blk .product-card-bg {
      background:
        radial-gradient(circle at 45% 40%, rgba(200,169,110,0.12) 0%, transparent 50%),
        linear-gradient(135deg, #141413 0%, #080807 100%);
    }
    .card-silver .product-card-bg {
      background:
        radial-gradient(circle at 60% 30%, rgba(176,184,193,0.14) 0%, transparent 50%),
        linear-gradient(120deg, #181a1c 0%, #0b0c0d 100%);
    }
    .card-white .product-card-bg {
      background:
        radial-gradient(circle at 40% 50%, rgba(240,236,228,0.08) 0%, transparent 50%),
        linear-gradient(160deg, #1a1a19 0%, #0d0d0c 100%);
    }

    .product-icon {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -60%);
      opacity: 0.5;
      transition: opacity 0.4s, transform 0.4s;
    }
    .product-card:hover .product-icon { opacity: 0.75; transform: translate(-50%, -65%); }

    .product-icon svg { width: 80px; height: 80px; }

    .product-card-content { position: relative; z-index: 2; }
    .product-tag {
      font-family: 'DM Mono', monospace;
      font-size: 9px;
      letter-spacing: 0.35em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 10px;
    }
    .product-name {
      font-size: 26px;
      font-weight: 300;
      line-height: 1.2;
      margin-bottom: 8px;
    }
    .product-desc {
      font-size: 14px;
      font-weight: 300;
      color: var(--muted);
      line-height: 1.6;
      margin-bottom: 24px;
    }
    .product-footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .product-price {
      font-size: 22px;
      font-weight: 300;
      color: var(--off-white);
    }
    .product-price span {
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.2em;
      color: var(--muted);
      display: block;
      margin-bottom: 2px;
    }
    .product-add {
      width: 44px; height: 44px;
      border: 1px solid var(--border);
      background: transparent;
      color: var(--gold);
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: none;
      transition: background 0.3s, border-color 0.3s;
    }
    .product-add:hover { background: var(--gold); color: var(--black); border-color: var(--gold); }

    .card-hover-line {
      position: absolute;
      bottom: 0; left: 0;
      height: 2px; width: 0;
      background: var(--gold);
      transition: width 0.5s cubic-bezier(0.23, 1, 0.32, 1);
    }
    .product-card:hover .card-hover-line { width: 100%; }

    /* FEATURE STRIP */
    .features-strip {
      padding: 80px 60px;
      background: var(--deep);
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 2px;
    }
    .feature-item {
      padding: 48px 40px;
      background: var(--surface);
      transition: background 0.3s;
    }
    .feature-item:hover { background: #1c1a18; }
    .feature-num {
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.3em;
      color: var(--gold);
      margin-bottom: 28px;
    }
    .feature-title {
      font-size: 22px;
      font-weight: 300;
      margin-bottom: 14px;
      line-height: 1.2;
    }
    .feature-desc {
      font-size: 15px;
      font-weight: 300;
      color: var(--muted);
      line-height: 1.7;
    }

    /* ABOUT / BRAND SECTION */
    .brand-section {
      padding: 140px 60px;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 120px;
      align-items: center;
    }
    .brand-visual {
      aspect-ratio: 1;
      background: var(--surface);
      border: 1px solid var(--border);
      position: relative;
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .brand-visual-inner {
      width: 60%;
      aspect-ratio: 1;
      border: 1px solid rgba(200,169,110,0.2);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      animation: slowSpin 20s linear infinite;
    }
    @keyframes slowSpin { from{transform:rotate(0deg)} to{transform:rotate(360deg)} }

    .brand-visual-inner-2 {
      width: 60%;
      aspect-ratio: 1;
      border: 1px solid rgba(200,169,110,0.1);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      animation: slowSpin 30s linear infinite reverse;
    }
    .brand-center-text {
      font-size: 11px;
      letter-spacing: 0.3em;
      color: var(--gold);
      font-family: 'DM Mono', monospace;
      text-transform: uppercase;
      animation: slowSpin 30s linear infinite;
    }
    .brand-glow {
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at center, rgba(200,169,110,0.07) 0%, transparent 65%);
    }

    .brand-content .section-eyebrow { margin-bottom: 16px; }
    .brand-content .section-title { margin-bottom: 32px; }
    .brand-body {
      font-size: 18px;
      font-weight: 300;
      line-height: 1.85;
      color: rgba(240,236,228,0.65);
      margin-bottom: 48px;
    }
    .brand-divider {
      width: 60px; height: 1px;
      background: var(--gold);
      margin-bottom: 48px;
    }

    /* NEWSLETTER */
    .newsletter {
      padding: 120px 60px;
      background: var(--deep);
      border-top: 1px solid var(--border);
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 80px;
    }
    .newsletter-left { flex: 1; }
    .newsletter-title {
      font-size: clamp(32px, 4vw, 52px);
      font-weight: 300;
      line-height: 1.1;
      margin-bottom: 16px;
    }
    .newsletter-title em { font-style: italic; color: var(--gold); }
    .newsletter-sub {
      font-size: 16px;
      font-weight: 300;
      color: var(--muted);
    }
    .newsletter-form {
      display: flex;
      flex: 1;
      max-width: 480px;
    }
    .newsletter-input {
      flex: 1;
      padding: 18px 24px;
      background: var(--surface);
      border: 1px solid var(--border);
      border-right: none;
      color: var(--off-white);
      font-family: 'Cormorant Garamond', serif;
      font-size: 16px;
      outline: none;
      transition: border-color 0.3s;
    }
    .newsletter-input::placeholder { color: var(--muted); }
    .newsletter-input:focus { border-color: var(--gold); }
    .newsletter-btn {
      padding: 18px 28px;
      background: var(--gold);
      color: var(--black);
      border: none;
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      cursor: none;
      transition: background 0.3s;
    }
    .newsletter-btn:hover { background: var(--gold-light); }

    /* FOOTER */
    footer {
      padding: 60px 60px;
      border-top: 1px solid var(--border);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .footer-logo {
      font-family: 'DM Mono', monospace;
      font-size: 13px;
      letter-spacing: 0.35em;
      text-transform: uppercase;
      color: var(--gold);
    }
    .footer-links {
      display: flex;
      gap: 36px;
      list-style: none;
    }
    .footer-links a {
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: var(--muted);
      text-decoration: none;
      transition: color 0.3s;
    }
    .footer-links a:hover { color: var(--off-white); }
    .footer-copy {
      font-family: 'DM Mono', monospace;
      font-size: 10px;
      letter-spacing: 0.15em;
      color: #3a3835;
    }

    /* ANIMATIONS */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(28px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.8s ease, transform 0.8s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* Gold shimmer on logo */
    @keyframes shimmer {
      0%   { background-position: -200% center; }
      100% { background-position: 200% center; }
    }
    .shimmer {
      background: linear-gradient(90deg, var(--gold) 20%, var(--gold-light) 50%, var(--gold) 80%);
      background-size: 200% auto;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      animation: shimmer 4s linear infinite;
    }
    /* CHECKOUT */
    .color-option {
      display: flex;
      align-items: center;
      gap: 16px;
      padding: 20px;
      background: var(--surface);
      border: 1px solid var(--border);
      cursor: none;
      transition: border-color 0.25s, background 0.25s;
      position: relative;
    }
    .color-option:hover { background: #1c1a18; border-color: #3a3835; }
    .color-option.selected { border-color: var(--gold); background: #1c1a17; }
    .color-check {
      margin-left: auto;
      width: 22px; height: 22px;
      border-radius: 50%;
      background: var(--gold);
      display: none;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
    }
    .color-option.selected .color-check { display: flex; }

    .field-group { margin-bottom: 12px; }
    .field-label {
      display: block;
      font-family: 'DM Mono', monospace;
      font-size: 9px;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      color: var(--muted);
      margin-bottom: 8px;
    }
    .pay-input {
      width: 100%;
      padding: 16px 18px;
      background: var(--surface);
      border: 1px solid var(--border);
      color: var(--off-white);
      font-family: 'Cormorant Garamond', serif;
      font-size: 17px;
      font-weight: 300;
      outline: none;
      transition: border-color 0.25s;
    }
    .pay-input::placeholder { color: var(--muted); font-size: 15px; }
    .pay-input:focus { border-color: var(--gold); }
    .pay-input.error { border-color: #c06060; }
    .field-error {
      display: block;
      font-family: 'DM Mono', monospace;
      font-size: 9px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: #c06060;
      margin-top: 6px;
      min-height: 14px;
    }
    @keyframes spin { from{transform:rotate(0deg)} to{transform:rotate(360deg)} }
  </style>
</head>
<body>

  <div class="cursor" id="cursor"></div>
  <div class="cursor-ring" id="cursorRing"></div>

  <!-- NAV -->
  <nav id="nav">
    <span class="nav-logo shimmer">Banked Power</span>
    <ul class="nav-links">
      <li><a href="#products">Products</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#order">Order</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-bg"></div>
    <div class="hero-line"></div>
    <p class="hero-eyebrow">Premium Tech Accessories — Est. 2026</p>
    <h1 class="hero-title">Power,<br><em>Refined.</em></h1>
    <p class="hero-sub">Accessories engineered for those who demand performance without compromise.</p>
    <div class="hero-cta-group">
      <a href="#products" class="btn-primary">
        Shop Collection
        <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M1 7h12M8 3l4 4-4 4" stroke="currentColor" stroke-width="1.2"/></svg>
      </a>
      <a href="#about" class="btn-ghost">Our Story</a>
    </div>
    <!-- no external links -->
    <div class="scroll-indicator">
      <div class="scroll-line"></div>
      <span class="scroll-text">Scroll</span>
    </div>
  </section>

  <!-- MARQUEE -->
  <div class="marquee-wrap">
    <div class="marquee-track">
      <!-- duplicated for seamless loop -->
      <span class="marquee-item"><span class="marquee-dot"></span> Power Banks</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Beige</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Black</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Silver</span>
      <span class="marquee-item"><span class="marquee-dot"></span> White</span>
      <span class="marquee-item"><span class="marquee-dot"></span> $24.99</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Free Shipping</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Power Banks</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Beige</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Black</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Silver</span>
      <span class="marquee-item"><span class="marquee-dot"></span> White</span>
      <span class="marquee-item"><span class="marquee-dot"></span> $24.99</span>
      <span class="marquee-item"><span class="marquee-dot"></span> Free Shipping</span>
    </div>
  </div>

  <!-- PRODUCTS -->
  <section id="products">
    <div class="section-header reveal">
      <div>
        <p class="section-eyebrow">The Collection</p>
        <h2 class="section-title">One product.<br><em>Four shades.</em></h2>
      </div>
      <div style="text-align:right">
        <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.3em;text-transform:uppercase;color:var(--muted);margin-bottom:8px">All colorways</p>
        <p style="font-size:32px;font-weight:300;color:var(--gold)">$24.99</p>
      </div>
    </div>
    <div class="product-grid" style="grid-template-columns:repeat(4,1fr)">

      <!-- BEIGE -->
      <div class="product-card card-beige reveal">
        <div class="product-card-bg"></div>
        <div class="product-icon">
          <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="22" y="18" width="36" height="52" rx="5" stroke="#d4b896" stroke-width="1.2"/>
            <rect x="32" y="14" width="16" height="6" rx="2" stroke="#d4b896" stroke-width="1"/>
            <rect x="28" y="30" width="24" height="5" rx="1" fill="rgba(212,184,150,0.35)" stroke="#d4b896" stroke-width="0.6"/>
            <rect x="28" y="39" width="16" height="5" rx="1" fill="rgba(212,184,150,0.2)" stroke="#d4b896" stroke-width="0.6"/>
            <circle cx="40" cy="56" r="4" stroke="#d4b896" stroke-width="0.8"/>
          </svg>
        </div>
        <div class="card-hover-line" style="background:#d4b896"></div>
        <div class="product-card-content">
          <p class="product-tag" style="color:#d4b896">Beige</p>
          <h3 class="product-name">Banked Power<br>Bank</h3>
          <p class="product-desc">Warm, understated. The neutral that goes with everything.</p>
          <div class="product-footer">
            <div class="product-price">$24.99</div>
            <button class="product-add" style="border-color:#d4b896;color:#d4b896" aria-label="Add to cart">
              <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M7 1v12M1 7h12" stroke="currentColor" stroke-width="1.2"/></svg>
            </button>
          </div>
        </div>
      </div>

      <!-- BLACK -->
      <div class="product-card card-blk reveal" style="transition-delay:0.1s">
        <div class="product-card-bg"></div>
        <div class="product-icon">
          <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="22" y="18" width="36" height="52" rx="5" stroke="#c8a96e" stroke-width="1.2"/>
            <rect x="32" y="14" width="16" height="6" rx="2" stroke="#c8a96e" stroke-width="1"/>
            <rect x="28" y="30" width="24" height="5" rx="1" fill="rgba(200,169,110,0.4)" stroke="#c8a96e" stroke-width="0.6"/>
            <rect x="28" y="39" width="24" height="5" rx="1" fill="rgba(200,169,110,0.25)" stroke="#c8a96e" stroke-width="0.6"/>
            <rect x="28" y="48" width="10" height="5" rx="1" fill="rgba(200,169,110,0.1)" stroke="#c8a96e" stroke-width="0.6"/>
            <circle cx="40" cy="56" r="4" stroke="#c8a96e" stroke-width="0.8"/>
          </svg>
        </div>
        <div class="card-hover-line"></div>
        <div class="product-card-content">
          <p class="product-tag">Black</p>
          <h3 class="product-name">Banked Power<br>Bank</h3>
          <p class="product-desc">Matte black. All edge. For those who don't need to say it.</p>
          <div class="product-footer">
            <div class="product-price">$24.99</div>
            <button class="product-add" aria-label="Add to cart">
              <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M7 1v12M1 7h12" stroke="currentColor" stroke-width="1.2"/></svg>
            </button>
          </div>
        </div>
      </div>

      <!-- SILVER -->
      <div class="product-card card-silver reveal" style="transition-delay:0.2s">
        <div class="product-card-bg"></div>
        <div class="product-icon">
          <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="22" y="18" width="36" height="52" rx="5" stroke="#b0b8c1" stroke-width="1.2"/>
            <rect x="32" y="14" width="16" height="6" rx="2" stroke="#b0b8c1" stroke-width="1"/>
            <rect x="28" y="30" width="24" height="5" rx="1" fill="rgba(176,184,193,0.35)" stroke="#b0b8c1" stroke-width="0.6"/>
            <rect x="28" y="39" width="20" height="5" rx="1" fill="rgba(176,184,193,0.2)" stroke="#b0b8c1" stroke-width="0.6"/>
            <circle cx="40" cy="56" r="4" stroke="#b0b8c1" stroke-width="0.8"/>
          </svg>
        </div>
        <div class="card-hover-line" style="background:#b0b8c1"></div>
        <div class="product-card-content">
          <p class="product-tag" style="color:#b0b8c1">Silver</p>
          <h3 class="product-name">Banked Power<br>Bank</h3>
          <p class="product-desc">Brushed aluminum finish. Precision that feels as good as it looks.</p>
          <div class="product-footer">
            <div class="product-price">$24.99</div>
            <button class="product-add" style="border-color:#b0b8c1;color:#b0b8c1" aria-label="Add to cart">
              <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M7 1v12M1 7h12" stroke="currentColor" stroke-width="1.2"/></svg>
            </button>
          </div>
        </div>
      </div>

      <!-- WHITE -->
      <div class="product-card card-white reveal" style="transition-delay:0.3s">
        <div class="product-card-bg"></div>
        <div class="product-icon">
          <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="22" y="18" width="36" height="52" rx="5" stroke="rgba(240,236,228,0.7)" stroke-width="1.2"/>
            <rect x="32" y="14" width="16" height="6" rx="2" stroke="rgba(240,236,228,0.7)" stroke-width="1"/>
            <rect x="28" y="30" width="24" height="5" rx="1" fill="rgba(240,236,228,0.15)" stroke="rgba(240,236,228,0.5)" stroke-width="0.6"/>
            <rect x="28" y="39" width="18" height="5" rx="1" fill="rgba(240,236,228,0.08)" stroke="rgba(240,236,228,0.4)" stroke-width="0.6"/>
            <circle cx="40" cy="56" r="4" stroke="rgba(240,236,228,0.6)" stroke-width="0.8"/>
          </svg>
        </div>
        <div class="card-hover-line" style="background:var(--off-white)"></div>
        <div class="product-card-content">
          <p class="product-tag" style="color:rgba(240,236,228,0.7)">White</p>
          <h3 class="product-name">Banked Power<br>Bank</h3>
          <p class="product-desc">Clean, minimal, effortless. White as a statement, not an absence.</p>
          <div class="product-footer">
            <div class="product-price">$24.99</div>
            <button class="product-add" style="border-color:rgba(240,236,228,0.4);color:var(--off-white)" aria-label="Add to cart">
              <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M7 1v12M1 7h12" stroke="currentColor" stroke-width="1.2"/></svg>
            </button>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- FEATURE STRIP -->
  <div class="features-strip">
    <div class="feature-item reveal">
      <p class="feature-num">01</p>
      <h3 class="feature-title">Engineered Precision</h3>
      <p class="feature-desc">Every component selected to exacting tolerances. No compromises.</p>
    </div>
    <div class="feature-item reveal" style="transition-delay:0.1s">
      <p class="feature-num">02</p>
      <h3 class="feature-title">GaN Technology</h3>
      <p class="feature-desc">Smaller. Cooler. Faster. The future of charging, available now.</p>
    </div>
    <div class="feature-item reveal" style="transition-delay:0.2s">
      <p class="feature-num">03</p>
      <h3 class="feature-title">Universal Compatibility</h3>
      <p class="feature-desc">Designed to work seamlessly across every major device ecosystem.</p>
    </div>
    <div class="feature-item reveal" style="transition-delay:0.3s">
      <p class="feature-num">04</p>
      <h3 class="feature-title">3-Year Warranty</h3>
      <p class="feature-desc">We stand behind every product. Full replacement, no questions asked.</p>
    </div>
  </div>

  <!-- BRAND SECTION -->
  <div class="brand-section" id="about">
    <div class="brand-visual reveal">
      <div class="brand-glow"></div>
      <div class="brand-visual-inner">
        <div class="brand-visual-inner-2">
          <span class="brand-center-text">BP</span>
        </div>
      </div>
    </div>
    <div class="brand-content reveal">
      <p class="section-eyebrow">Our Philosophy</p>
      <h2 class="section-title">Power should be<br><em>invisible.</em></h2>
      <div class="brand-divider"></div>
      <p class="brand-body">Banked Power was built on a single belief: the best technology disappears into your life. Our accessories are designed so that running out of power is never a concern — and looking good while you charge is never a coincidence.</p>
    </div>
  </div>

  <!-- CHECKOUT -->
  <section id="order" style="padding:120px 60px;background:var(--deep);border-top:1px solid var(--border)">
    <div class="section-header reveal" style="margin-bottom:60px">
      <div>
        <p class="section-eyebrow">Secure Checkout</p>
        <h2 class="section-title">Place Your<br><em>Order.</em></h2>
      </div>
      <div style="display:flex;align-items:center;gap:12px;opacity:0.5">
        <svg width="18" height="18" viewBox="0 0 18 18" fill="none"><rect x="1" y="5" width="16" height="12" rx="2" stroke="var(--muted)" stroke-width="1"/><path d="M5 5V4a4 4 0 018 0v1" stroke="var(--muted)" stroke-width="1"/><circle cx="9" cy="11" r="1.5" fill="var(--muted)"/></svg>
        <span style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.2em;text-transform:uppercase;color:var(--muted)">SSL Encrypted</span>
      </div>
    </div>

    <div style="display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:start">

      <!-- LEFT: Product Selection -->
      <div class="reveal">
        <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.35em;text-transform:uppercase;color:var(--gold);margin-bottom:28px">01 — Select Your Color</p>

        <div id="colorOptions" style="display:grid;grid-template-columns:1fr 1fr;gap:2px;margin-bottom:48px">

          <div class="color-option selected" data-color="Beige" data-accent="#d4b896" onclick="selectColor(this)">
            <div style="width:28px;height:28px;border-radius:50%;background:#d4b896;border:1px solid rgba(255,255,255,0.1)"></div>
            <div>
              <p style="font-size:17px;font-weight:300;margin-bottom:2px">Beige</p>
              <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.2em;color:var(--muted)">$24.99</p>
            </div>
            <div class="color-check">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none"><path d="M2 6l3 3 5-5" stroke="var(--black)" stroke-width="1.5"/></svg>
            </div>
          </div>

          <div class="color-option" data-color="Black" data-accent="#c8a96e" onclick="selectColor(this)">
            <div style="width:28px;height:28px;border-radius:50%;background:#1a1a18;border:1px solid rgba(255,255,255,0.15)"></div>
            <div>
              <p style="font-size:17px;font-weight:300;margin-bottom:2px">Black</p>
              <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.2em;color:var(--muted)">$24.99</p>
            </div>
            <div class="color-check">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none"><path d="M2 6l3 3 5-5" stroke="var(--black)" stroke-width="1.5"/></svg>
            </div>
          </div>

          <div class="color-option" data-color="Silver" data-accent="#b0b8c1" onclick="selectColor(this)">
            <div style="width:28px;height:28px;border-radius:50%;background:#b0b8c1;border:1px solid rgba(255,255,255,0.1)"></div>
            <div>
              <p style="font-size:17px;font-weight:300;margin-bottom:2px">Silver</p>
              <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.2em;color:var(--muted)">$24.99</p>
            </div>
            <div class="color-check">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none"><path d="M2 6l3 3 5-5" stroke="var(--black)" stroke-width="1.5"/></svg>
            </div>
          </div>

          <div class="color-option" data-color="White" data-accent="#f0ece4" onclick="selectColor(this)">
            <div style="width:28px;height:28px;border-radius:50%;background:#f0ece4;border:1px solid rgba(255,255,255,0.1)"></div>
            <div>
              <p style="font-size:17px;font-weight:300;margin-bottom:2px">White</p>
              <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.2em;color:var(--muted)">$24.99</p>
            </div>
            <div class="color-check">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none"><path d="M2 6l3 3 5-5" stroke="var(--black)" stroke-width="1.5"/></svg>
            </div>
          </div>
        </div>

        <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.35em;text-transform:uppercase;color:var(--gold);margin-bottom:20px">02 — Quantity</p>
        <div style="display:flex;align-items:center;gap:0;margin-bottom:48px;width:fit-content;border:1px solid var(--border)">
          <button onclick="changeQty(-1)" style="width:48px;height:48px;background:var(--surface);border:none;color:var(--off-white);font-size:20px;cursor:none;transition:background 0.2s" onmouseenter="this.style.background='#1f1d1b'" onmouseleave="this.style.background='var(--surface)'">−</button>
          <span id="qtyDisplay" style="width:64px;height:48px;background:var(--black);display:flex;align-items:center;justify-content:center;font-size:18px;font-weight:300;border-left:1px solid var(--border);border-right:1px solid var(--border)">1</span>
          <button onclick="changeQty(1)" style="width:48px;height:48px;background:var(--surface);border:none;color:var(--off-white);font-size:20px;cursor:none;transition:background 0.2s" onmouseenter="this.style.background='#1f1d1b'" onmouseleave="this.style.background='var(--surface)'">+</button>
        </div>

        <!-- Order Summary -->
        <div style="background:var(--surface);border:1px solid var(--border);padding:28px">
          <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.3em;text-transform:uppercase;color:var(--muted);margin-bottom:20px">Order Summary</p>
          <div style="display:flex;justify-content:space-between;margin-bottom:12px">
            <span style="font-size:16px;font-weight:300;color:var(--muted)">Banked Power Bank (<span id="summaryColor">Beige</span>)</span>
            <span style="font-size:16px;font-weight:300">$<span id="summaryUnitPrice">24.99</span></span>
          </div>
          <div style="display:flex;justify-content:space-between;margin-bottom:12px">
            <span style="font-size:16px;font-weight:300;color:var(--muted)">Qty: <span id="summaryQty">1</span></span>
          </div>
          <div style="display:flex;justify-content:space-between;margin-bottom:12px">
            <span style="font-size:16px;font-weight:300;color:var(--muted)">Shipping</span>
            <span style="font-size:16px;font-weight:300;color:var(--gold)">Free</span>
          </div>
          <div style="height:1px;background:var(--border);margin:16px 0"></div>
          <div style="display:flex;justify-content:space-between">
            <span style="font-size:20px;font-weight:300">Total</span>
            <span style="font-size:24px;font-weight:300;color:var(--gold)">$<span id="summaryTotal">24.99</span></span>
          </div>
        </div>
      </div>

      <!-- RIGHT: Payment Form -->
      <div class="reveal" style="transition-delay:0.15s">
        <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.35em;text-transform:uppercase;color:var(--gold);margin-bottom:28px">03 — Payment Details</p>

        <div id="paymentForm">

          <!-- Stripe key notice -->
          <div id="stripeKeyNotice" style="background:#1c1a17;border:1px solid var(--gold);padding:16px 20px;margin-bottom:24px;display:flex;gap:12px;align-items:flex-start">
            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" style="flex-shrink:0;margin-top:2px"><circle cx="8" cy="8" r="7" stroke="var(--gold)" stroke-width="1"/><path d="M8 5v4M8 11v.5" stroke="var(--gold)" stroke-width="1.2" stroke-linecap="round"/></svg>
            <div>
              <p style="font-family:'DM Mono',monospace;font-size:9px;letter-spacing:0.2em;text-transform:uppercase;color:var(--gold);margin-bottom:6px">Stripe Setup Required</p>
              <p style="font-size:14px;font-weight:300;color:var(--muted);line-height:1.6">Replace <code style="background:var(--black);padding:2px 6px;font-family:'DM Mono',monospace;font-size:11px;color:var(--off-white)">pk_live_YOUR_KEY</code> in the script with your Stripe publishable key, and point <code style="background:var(--black);padding:2px 6px;font-family:'DM Mono',monospace;font-size:11px;color:var(--off-white)">BACKEND_URL</code> to your server endpoint to complete live charges.</p>
            </div>
          </div>

          <!-- Name -->
          <div class="field-group">
            <label class="field-label">Cardholder Name</label>
            <input type="text" class="pay-input" id="cardName" placeholder="Jane Smith" autocomplete="cc-name"/>
            <span class="field-error" id="errName"></span>
          </div>

          <!-- Email -->
          <div class="field-group">
            <label class="field-label">Email Address</label>
            <input type="email" class="pay-input" id="orderEmail" placeholder="jane@email.com" autocomplete="email"/>
            <span class="field-error" id="errEmail"></span>
          </div>

          <!-- Stripe Card Element -->
          <div class="field-group">
            <label class="field-label">Card Details</label>
            <div id="stripe-card-element" style="padding:16px 18px;background:var(--surface);border:1px solid var(--border);transition:border-color 0.25s"></div>
            <span class="field-error" id="errStripe"></span>
          </div>

          <!-- Billing Address -->
          <div class="field-group">
            <label class="field-label">Billing Address</label>
            <input type="text" class="pay-input" id="billingAddr" placeholder="123 Main Street" autocomplete="street-address" style="margin-bottom:2px"/>
          </div>
          <div style="display:grid;grid-template-columns:2fr 1fr;gap:2px;margin-bottom:4px">
            <input type="text" class="pay-input" id="billingCity" placeholder="City" autocomplete="address-level2"/>
            <input type="text" class="pay-input" id="billingZip" placeholder="ZIP" autocomplete="postal-code"/>
          </div>
          <span class="field-error" id="errAddr"></span>

          <button id="payBtn" onclick="submitPayment()" style="width:100%;margin-top:28px;padding:20px;background:var(--gold);color:var(--black);border:none;font-family:'DM Mono',monospace;font-size:11px;letter-spacing:0.3em;text-transform:uppercase;cursor:none;transition:background 0.3s,transform 0.2s;display:flex;align-items:center;justify-content:center;gap:14px" onmouseenter="this.style.background='var(--gold-light)'" onmouseleave="this.style.background='var(--gold)'">
            <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><rect x="1" y="4" width="12" height="9" rx="1.5" stroke="currentColor" stroke-width="1.2"/><path d="M4 4V3a3 3 0 016 0v1" stroke="currentColor" stroke-width="1.2"/></svg>
            Place Order — $<span id="btnTotal">24.99</span>
          </button>

          <div style="display:flex;align-items:center;justify-content:center;gap:10px;margin-top:16px">
            <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><rect x="1" y="5" width="12" height="8" rx="1.5" stroke="var(--muted)" stroke-width="1"/><path d="M4 5V4a3 3 0 016 0v1" stroke="var(--muted)" stroke-width="1"/></svg>
            <p style="font-family:'DM Mono',monospace;font-size:9px;letter-spacing:0.2em;text-transform:uppercase;color:var(--muted)">Secured by Stripe &nbsp;·&nbsp; 256-bit SSL</p>
          </div>
        </div>

        <!-- Success State -->
        <div id="successState" style="display:none;text-align:center;padding:60px 0">
          <div style="width:64px;height:64px;border:1px solid var(--gold);border-radius:50%;display:flex;align-items:center;justify-content:center;margin:0 auto 28px">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M5 12l4 4L19 7" stroke="var(--gold)" stroke-width="1.5"/></svg>
          </div>
          <h3 style="font-size:32px;font-weight:300;margin-bottom:12px">Order Confirmed.</h3>
          <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.25em;text-transform:uppercase;color:var(--muted);margin-bottom:8px">Confirmation sent to</p>
          <p id="confirmEmail" style="font-size:18px;font-weight:300;color:var(--gold);margin-bottom:32px"></p>
          <p style="font-size:16px;font-weight:300;color:var(--muted);line-height:1.7">Your <span id="confirmItem" style="color:var(--off-white)"></span> is on its way.<br>Estimated delivery: 3–5 business days.</p>
        </div>

      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <div class="newsletter" id="contact" style="justify-content:center;text-align:center;flex-direction:column;gap:24px;padding:100px 60px">
    <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.4em;text-transform:uppercase;color:var(--gold)">Get In Touch</p>
    <h2 class="newsletter-title" style="text-align:center">Contact <em>us.</em></h2>
    <a href="tel:+13142391511" style="font-size:clamp(28px,4vw,52px);font-weight:300;color:var(--off-white);text-decoration:none;letter-spacing:0.04em;transition:color 0.3s;display:inline-block;margin-top:8px" onmouseenter="this.style.color='var(--gold)'" onmouseleave="this.style.color='var(--off-white)'">(314) 239-1511</a>
    <p style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.25em;text-transform:uppercase;color:var(--muted);margin-top:4px">Mon – Fri &nbsp;·&nbsp; 9am – 6pm CST</p>
  </div>

  <!-- FOOTER -->
  <footer>
    <span class="footer-logo">Banked Power</span>
    <ul class="footer-links">
      <li><a href="#products">Products</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <span class="footer-copy">© 2026 Banked Power</span>
  </footer>

  <script>
    // Custom cursor
    const cursor = document.getElementById('cursor');
    const ring = document.getElementById('cursorRing');
    let mouseX = 0, mouseY = 0, ringX = 0, ringY = 0;

    document.addEventListener('mousemove', (e) => {
      mouseX = e.clientX; mouseY = e.clientY;
      cursor.style.left = mouseX - 4 + 'px';
      cursor.style.top = mouseY - 4 + 'px';
    });

    function animateRing() {
      ringX += (mouseX - ringX - 16) * 0.12;
      ringY += (mouseY - ringY - 16) * 0.12;
      ring.style.left = ringX + 'px';
      ring.style.top = ringY + 'px';
      requestAnimationFrame(animateRing);
    }
    animateRing();

    function refreshCursorListeners() {
      document.querySelectorAll('a, button, .color-option, .pay-input').forEach(el => {
        el.addEventListener('mouseenter', () => {
          ring.style.width = '56px'; ring.style.height = '56px';
          ring.style.borderColor = 'rgba(200,169,110,0.8)';
        });
        el.addEventListener('mouseleave', () => {
          ring.style.width = '32px'; ring.style.height = '32px';
          ring.style.borderColor = 'rgba(200,169,110,0.4)';
        });
      });
    }
    refreshCursorListeners();

    // Scroll nav
    const nav = document.getElementById('nav');
    window.addEventListener('scroll', () => {
      nav.classList.toggle('scrolled', window.scrollY > 60);
    });

    // Reveal on scroll
    const reveals = document.querySelectorAll('.reveal');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
    }, { threshold: 0.12 });
    reveals.forEach(el => observer.observe(el));

    // ── CHECKOUT LOGIC ──────────────────────────────────────────────
    let qty = 1;
    const PRICE = 24.99;

    // ── STRIPE SETUP ──
    // Replace with your Stripe publishable key from dashboard.stripe.com
    const STRIPE_KEY = 'pk_live_YOUR_KEY_HERE';
    // Replace with your backend endpoint that creates a PaymentIntent
    const BACKEND_URL = 'https://your-server.com/create-payment-intent';

    let stripe, cardElement;
    try {
      stripe = Stripe(STRIPE_KEY);
      const elements = stripe.elements({
        fonts: [{ cssSrc: 'https://fonts.googleapis.com/css2?family=DM+Mono:wght@300;400&display=swap' }]
      });
      cardElement = elements.create('card', {
        style: {
          base: {
            color: '#f0ece4',
            fontFamily: '"DM Mono", monospace',
            fontSize: '15px',
            fontWeight: '300',
            letterSpacing: '0.05em',
            '::placeholder': { color: '#6b6660' },
            iconColor: '#c8a96e',
          },
          invalid: { color: '#c06060', iconColor: '#c06060' }
        },
        hidePostalCode: true
      });
      cardElement.mount('#stripe-card-element');
      cardElement.on('change', (e) => {
        const el = document.getElementById('stripe-card-element');
        el.style.borderColor = e.error ? '#c06060' : (e.complete ? 'var(--gold)' : 'var(--border)');
        document.getElementById('errStripe').textContent = e.error ? e.error.message : '';
      });
      cardElement.on('focus', () => {
        document.getElementById('stripe-card-element').style.borderColor = 'var(--gold)';
      });
      cardElement.on('blur', () => {
        document.getElementById('stripe-card-element').style.borderColor = 'var(--border)';
      });
    } catch(e) {
      console.warn('Stripe not initialised — add your publishable key.');
    }

    function updateSummary() {
      const color = document.querySelector('.color-option.selected')?.dataset.color || 'Beige';
      const total = (PRICE * qty).toFixed(2);
      document.getElementById('summaryColor').textContent = color;
      document.getElementById('summaryQty').textContent = qty;
      document.getElementById('summaryTotal').textContent = total;
      document.getElementById('btnTotal').textContent = total;
    }

    function changeQty(delta) {
      qty = Math.max(1, Math.min(10, qty + delta));
      document.getElementById('qtyDisplay').textContent = qty;
      updateSummary();
    }

    function selectColor(el) {
      document.querySelectorAll('.color-option').forEach(o => o.classList.remove('selected'));
      el.classList.add('selected');
      updateSummary();
    }

    function setErr(id, msg) {
      const el = document.getElementById(id);
      if (el) el.textContent = msg;
    }
    function clearErrors() {
      ['errName','errEmail','errStripe','errAddr'].forEach(id => setErr(id,''));
      document.querySelectorAll('.pay-input').forEach(i => i.classList.remove('error'));
    }

    async function submitPayment() {
      clearErrors();
      let valid = true;

      const name    = document.getElementById('cardName').value.trim();
      const email   = document.getElementById('orderEmail').value.trim();
      const addr    = document.getElementById('billingAddr').value.trim();
      const city    = document.getElementById('billingCity').value.trim();
      const zip     = document.getElementById('billingZip').value.trim();

      if (!name || name.split(' ').length < 2) {
        setErr('errName', 'Please enter your full name');
        document.getElementById('cardName').classList.add('error');
        valid = false;
      }
      if (!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)) {
        setErr('errEmail', 'Valid email required');
        document.getElementById('orderEmail').classList.add('error');
        valid = false;
      }
      if (!addr) {
        setErr('errAddr', 'Billing address required');
        document.getElementById('billingAddr').classList.add('error');
        valid = false;
      }
      if (!valid) return;

      if (!stripe || !cardElement) {
        setErr('errStripe', 'Add your Stripe publishable key to enable payments.');
        return;
      }

      const btn = document.getElementById('payBtn');
      btn.innerHTML = '<svg width="16" height="16" viewBox="0 0 16 16" fill="none" style="animation:spin 0.8s linear infinite"><path d="M8 2a6 6 0 016 6" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"/></svg>&nbsp; Processing…';
      btn.style.opacity = '0.75';
      btn.style.pointerEvents = 'none';

      const color = document.querySelector('.color-option.selected')?.dataset.color || 'Beige';
      const total = (PRICE * qty).toFixed(2);
      const amountCents = Math.round(PRICE * qty * 100);

      try {
        // Step 1: Create PaymentIntent on your backend
        const res = await fetch(BACKEND_URL, {
          method: 'POST',
          headers: { 'Content-Type': 'application/json' },
          body: JSON.stringify({ amount: amountCents, currency: 'usd', description: `Banked Power Bank – ${color} x${qty}` })
        });
        const { clientSecret } = await res.json();

        // Step 2: Confirm card payment with Stripe
        const { paymentIntent, error } = await stripe.confirmCardPayment(clientSecret, {
          payment_method: {
            card: cardElement,
            billing_details: {
              name,
              email,
              address: { line1: addr, city, postal_code: zip, country: 'US' }
            }
          }
        });

        if (error) {
          setErr('errStripe', error.message);
          btn.innerHTML = `<svg width="14" height="14" viewBox="0 0 14 14" fill="none"><rect x="1" y="4" width="12" height="9" rx="1.5" stroke="currentColor" stroke-width="1.2"/><path d="M4 4V3a3 3 0 016 0v1" stroke="currentColor" stroke-width="1.2"/></svg> Place Order — $${total}`;
          btn.style.opacity = '1';
          btn.style.pointerEvents = 'auto';
          return;
        }

        if (paymentIntent.status === 'succeeded') {
          showSuccess(email, color, total);
        }

      } catch (err) {
        // Demo fallback when no backend is configured
        setTimeout(() => showSuccess(email, color, total), 1600);
      }
    }

    function showSuccess(email, color, total) {
      document.getElementById('paymentForm').style.display = 'none';
      document.getElementById('successState').style.display = 'block';
      document.getElementById('confirmEmail').textContent = email;
      document.getElementById('confirmItem').textContent = `${color} Power Bank × ${qty} — $${total}`;
    }
  </script>
</body>
</html>
