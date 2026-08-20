<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Anime Network India 🇮🇳</title>

  <meta name="description" content="Anime Network India - Anime news, updates and entertainment.">
  <meta name="theme-color" content="#111827">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #0b0f19;
      color: #ffffff;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Header */
    header {
      background: #111827;
      border-bottom: 1px solid #263044;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .navbar {
      max-width: 1100px;
      margin: auto;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 10px;
      font-size: 20px;
      font-weight: bold;
      white-space: nowrap;
    }

    .logo-icon {
      width: 42px;
      height: 42px;
      border-radius: 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #ff2d55, #7c3aed);
      font-size: 22px;
      box-shadow: 0 5px 20px rgba(124, 58, 237, 0.35);
    }

    nav {
      display: flex;
      gap: 20px;
    }

    nav a {
      color: #d1d5db;
      font-size: 14px;
      transition: 0.2s;
    }

    nav a:hover {
      color: #ffffff;
    }

    /* Hero */
    .hero {
      min-height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 70px 20px;
      background:
        radial-gradient(circle at top, #312e81 0%, transparent 45%),
        linear-gradient(180deg, #111827, #0b0f19);
    }

    .hero-content {
      max-width: 800px;
    }

    .hero-badge {
      display: inline-block;
      padding: 7px 14px;
      border: 1px solid #374151;
      border-radius: 30px;
      background: rgba(255,255,255,0.05);
      color: #c4b5fd;
      font-size: 13px;
      margin-bottom: 20px;
    }

    .hero h1 {
      font-size: clamp(38px, 8vw, 70px);
      line-height: 1.05;
      margin-bottom: 20px;
      font-weight: 800;
    }

    .gradient-text {
      background: linear-gradient(90deg, #ff2d55, #a855f7, #38bdf8);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .hero p {
      color: #9ca3af;
      max-width: 650px;
      margin: 0 auto 30px;
      font-size: 17px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 12px;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-block;
      padding: 12px 22px;
      border-radius: 10px;
      font-weight: bold;
      transition: 0.2s;
    }

    .btn-primary {
      background: linear-gradient(135deg, #7c3aed, #ec4899);
    }

    .btn-secondary {
      background: #1f2937;
      border: 1px solid #374151;
    }

    .btn:hover {
      transform: translateY(-2px);
      opacity: 0.9;
    }

    /* Section */
    .section {
      max-width: 1100px;
      margin: auto;
      padding: 70px 20px;
    }

    .section-title {
      text-align: center;
      margin-bottom: 40px;
    }

    .section-title h2 {
      font-size: 32px;
      margin-bottom: 8px;
    }

    .section-title p {
      color: #9ca3af;
    }

    /* Cards */
    .cards {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .card {
      background: #111827;
      border: 1px solid #263044;
      border-radius: 16px;
      padding: 25px;
      transition: 0.25s;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: #7c3aed;
    }

    .card-icon {
      width: 50px;
      height: 50px;
      border-radius: 12px;
      background: #1f2937;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 24px;
      margin-bottom: 18px;
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .card p {
      color: #9ca3af;
      font-size: 14px;
    }

    /* About */
    .about {
      background: #111827;
      border-top: 1px solid #263044;
      border-bottom: 1px solid #263044;
    }

    .about-content {
      max-width: 800px;
      margin: auto;
      text-align: center;
    }

    .about-content p {
      color: #9ca3af;
      margin-top: 15px;
    }

    /* Footer */
    footer {
      background: #070a11;
      text-align: center;
      padding: 30px 20px;
      color: #6b7280;
      font-size: 14px;
    }

    footer strong {
      color: #ffffff;
    }

    /* Mobile */
    @media (max-width: 768px) {
      .navbar {
        flex-direction: column;
      }

      nav {
        gap: 15px;
      }

      .hero {
        min-height: 450px;
        padding: 50px 20px;
      }

      .hero p {
        font-size: 15px;
      }

      .cards {
        grid-template-columns: 1fr;
      }

      .section {
        padding: 50px 20px;
      }
    }

    @media (max-width: 420px) {
      .logo {
        font-size: 17px;
      }

      .logo-icon {
        width: 38px;
        height: 38px;
      }

      nav a {
        font-size: 13px;
      }

      .hero h1 {
        font-size: 40px;
      }
    }
  </style>
</head>

<body>

  <!-- Header -->
  <header>
    <div class="navbar">

      <a href="#" class="logo">
        <span class="logo-icon">🇮🇳</span>
        <span>Anime Network India</span>
      </a>

      <nav>
        <a href="#home">Home</a>
        <a href="#updates">Updates</a>
        <a href="#about">About</a>
      </nav>

    </div>
  </header>


  <!-- Hero -->
  <main id="home">

    <section class="hero">
      <div class="hero-content">

        <span class="hero-badge">
          🇮🇳 Made for Indian Anime Fans
        </span>

        <h1>
          Anime Network
      s="gradient-text">India</span>
        </h1>

        <p>
          Your place for anime news, updates, announcements,
          releases and everything happening in the anime world.
        </p>

        <div class="buttons">


