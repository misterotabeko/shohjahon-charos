<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Shohjahon & Charos To‘y Taklifnomasi</title>
  <link rel="icon" type="image/png" href="love.png">
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Tangerine:wght@400;700&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Tangerine:wght@400;700&family=Unna:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">
  <style>
    /* Reset */
    * {
      margin: 0; 
      padding: 0; 
      box-sizing: border-box;
    }
    html, body {
      height: 100%;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background: url('red-white-flower-petals-floating-milk.jpg') center/cover no-repeat;
      color: #333;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }

    /* Asosiy taklif konteyneri */
    .invite {
      max-width: 900px;
      width: 100%;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.1);
      overflow: hidden;
    }

    /* Hero qismi */
    .hero {
      position: relative;
      padding: 60px 20px;
      background: url('beautiful-background-roses-valentine-s-day.jpg') center/cover no-repeat;
      color: #fff;
    }
    .hero::after {
      content: '';
      position: absolute;
      inset: 0;
      background: rgba(60, 1, 1, 0.528);
    }
    .hero .inner {
      position: relative;
      z-index: 1;
      font-family: 'Great Vibes', cursive;
    }
    .hero h1 {
      font-size: 3rem;
      line-height: 1.2;
    }
    .hero p.date {
      margin-top: 8px;
      font-size: 1.1rem;
      font-weight: 300;
      letter-spacing: 1px;
    }

    /* Main content */
    .content {
      position: relative;
      margin: 40px auto;
      padding: 40px 30px;
      background: #fefefe; /* Yengil fon */
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.06);
      max-width: 700px;
      text-align: center;
    }

    /* Joy nomini sarlavha ko‘rinishida berish */
    .location {
      font-family: 'Roboto', sans-serif;
      font-size: 1.4rem;
      color: #2c3e50;
      font-weight: 700;
      text-transform: unset;
      margin-top: 16px;
      letter-spacing: 1px;
    }
    .location img {
    width: 1.4rem;
    height: 1.4rem;
    object-fit: contain;}

    /* Asosiy taklif matni */
    .invitation-text {
      font-family: 'Unna';
      font-size: 1.05rem;
      line-height: 1.7;
      color: #2c3e50;
      text-align: center; 
      margin-top: 16px;
      margin-bottom: 0;
    }
    .invitation-text-xurmatli {
      font-family: 'Tangerine';
      font-size: 2.2rem;
      color: #2c3e50;
      font-weight: 700;
      text-transform: unset;
      margin-top: 16px;
      letter-spacing: 1px;
    }
    .invitation-text strong {
      color: #c0392b; 
      font-weight: 700;
    }
    .custom-link {
    color: #1e88e5; /* Zamonaviy ko‘k */
    text-decoration: none; /* Chiziqni yo‘q qiladi */
    font-weight: 500;
    font-size: 18px;
    transition: all 0.3s ease;
    padding: 6px 12px;
    border-radius: 6px;
    background-color: #f0f8ff; /* Yengil fon */
    display: inline-block;
  }

  .custom-link:hover {
    background-color: #0b1925;
    color: white;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);}

    /* Countdown */
    #countdown {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
      gap: 16px;
      margin-top: 32px;
    }
    #countdown .box {
      background: #b90d10;
      padding: 16px;
      border-radius: 8px;
    }
    #countdown .number {
      font-size: 2.2rem;
      font-weight: bold;
      color: #ffffff;
    }
    #countdown .label {
      margin-top: 4px;
      font-size: 0.9rem;
      text-transform: uppercase;
      color: #ffffff;
    }

    /* Responsive text sizes */
    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2.4rem;
      }
      .hero p.date {
        font-size: 1rem;
      }
      .invitation-text {
        font-size: 0.95rem;
      }
    }

  </style>
</head>
<body>

  <div class="invite">
    <!-- Hero section -->
    <div class="hero">
      <div class="inner">
        <h1>Shohjahon &amp; Charos</h1>
        <p class="date">25-MAY, 2025 | Navro‘z To'yxonasi</p>
      </div>
    </div>

    <!-- Main content -->
    <div class="content">  
      <!-- Invitation text -->
      <p class="invitation-text-xurmatli">
        Hurmatli yaqinlarimiz va aziz do‘stlar!</p>
        <p class="invitation-text"> Hayotimizdagi eng quvonchli va unutilmas kunlardan </br> birini sizlar bilan baham ko‘rishni istaymiz.
          Yurakdan chiqqan ezgu niyatlar va samimiy tilaklaringiz biz uchun bebaho. </br>
          Quvonchimizga sherik bo‘lishingiz, ushbu baxtiyor kunda yonimizda bo‘lishingizdan mamnun bo‘lamiz!
      </p>
      <h2 class="location">
        <img src="placeholder.png" alt="Manzil belgisi"> Manzil:
       <a href="https://maps.app.goo.gl/LhegSi78NBqwmXrQ8" target="_blank" class="custom-link">Zomin, Jizzax, O‘zbekiston</a></h2>

      <!-- Countdown -->
      <div id="countdown">
        <div class="box">
          <div id="days" class="number">0</div>
          <div class="label">Kun</div>
        </div>
        <div class="box">
          <div id="hours" class="number">0</div>
          <div class="label">Soat</div>
        </div>
        <div class="box">
          <div id="minutes" class="number">0</div>
          <div class="label">Daqiqa</div>
        </div>
        <div class="box">
          <div id="seconds" class="number">0</div>
          <div class="label">Soniya</div>
        </div>
      </div>
    </div>
  </div>

  <script>
    // To'y vaqti
    const eventTime = new Date("2025-05-25T00:00:00").getTime();

    function updateCountdown() {
      const now = Date.now();
      const diff = eventTime - now;

      if (diff <= 0) {
        clearInterval(timer);
        document.getElementById('countdown').innerHTML = 
          '<p style="font-size:1.2rem; color:#c0392b;">Marosim boshlandi!</p>';
        return;
      }

      const sec = 1000,
            min = sec * 60,
            hr  = min * 60,
            day = hr  * 24;

      const days    = Math.floor(diff / day),
            hours   = Math.floor((diff % day) / hr),
            minutes = Math.floor((diff % hr) / min),
            seconds = Math.floor((diff % min) / sec);

      document.getElementById('days').textContent    = days;
      document.getElementById('hours').textContent   = hours;
      document.getElementById('minutes').textContent = minutes;
      document.getElementById('seconds').textContent = seconds;
    }

    const timer = setInterval(updateCountdown, 1000);
    updateCountdown();
  </script>

</body>
</html>
