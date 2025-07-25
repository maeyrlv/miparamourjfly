<head>
  <meta charset="UTF-8">
  <title>Mi Paramour</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Quicksand&display=swap');

    body {
      margin: 0;
      font-family: 'Quicksand', sans-serif;
      background: #fff0f6;
      color: #4a2c2a;
      text-align: center;
      padding: 50px 20px;
      position: relative;
      overflow-x: hidden;
    }

    body::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background-image: url('https://www.transparenttextures.com/patterns/hearts.png');
      opacity: 0.08;
      z-index: 0;
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3.5em;
      color: #c9184a;
      margin-bottom: 10px;
      letter-spacing: 1px;
      position: relative;
      z-index: 1;
    }
    p {
      font-size: 1.2em;
      max-width: 700px;
      margin: 20px auto;
      line-height: 1.8;
      background: #ffffffcc;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      position: relative;
      z-index: 1;
    }

    .heart {
      font-size: 4em;
      color: #ff4d6d;
      margin: 30px 0;
      animation: pulse 1.5s infinite;
      position: relative;
      z-index: 1;
    }

    footer {
      margin-top: 60px;
      font-size: 0.95em;
      color: #a36a6a;
      position: relative;
      z-index: 1;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }

    /* Floating animated hearts */
    .floating-heart {
      position: absolute;
      font-size: 2em;
      color: #ffccd5;
      animation: float 10s linear infinite;
      opacity: 0.5;
    }

    .floating-heart:nth-child(1) { top: 100%; left: 10%; animation-delay: 0s; }
    .floating-heart:nth-child(2) { top: 100%; left: 40%; animation-delay: 2s; }
    .floating-heart:nth-child(3) { top: 100%; left: 70%; animation-delay: 4s; }

    @keyframes float {
      0% { transform: translateY(0) scale(1); opacity: 0.4; }
      50% { transform: translateY(-50vh) scale(1.2); opacity: 0.6; }
      100% { transform: translateY(-100vh) scale(0.8); opacity: 0; }
    }
  </style>
</head>
<body>
  <!-- Floating hearts animation -->
  <div class="floating-heart">💗</div>
  <div class="floating-heart">💞</div>
  <div class="floating-heart">💖</div>

  <div class="heart">❤️</div>
  <h1>Mi Paramour</h1>

  <p>
    You are the calm in my chaos, the light in my low days, and the joy in my everyday.  
    With every beat of my heart, I am reminded of how lucky I am to walk this life with you.
  </p>

  <p>
    I appreciate the way you listen, the way you laugh, the little gestures you think go unnoticed — they mean everything.  
    You're not just someone I love. You're someone I admire, respect, and feel proud of every single day.
  </p>

  <p>
    No webpage could ever hold all the love and gratitude I feel for you,  
    but let this be one more reminder that you're everything to me.
  </p>

  <div class="heart">💖</div>

  <footer>
    Truly yours,<br>
    Mae ❤️
  </footer>
</body>
