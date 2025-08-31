<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trockenausbau Mateusz Nowak</title>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #111;
      color: #eee;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #1a1a1a, #222);
      box-shadow: 0 2px 15px rgba(0,0,0,0.5);
    }
    header img {
      max-width: 180px;
      margin-bottom: 20px;
      animation: fadeIn 1.5s ease-in-out;
    }
    header h1 {
      font-size: 32px;
      letter-spacing: 2px;
      margin-bottom: 10px;
      color: #e53935;
    }
    header p {
      font-size: 18px;
      color: #ccc;
    }

    section {
      max-width: 1000px;
      margin: 50px auto;
      padding: 30px;
      background: #1b1b1b;
      border-radius: 12px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.6);
      animation: slideUp 1s ease-in-out;
    }
    section h2 {
      font-size: 24px;
      margin-bottom: 20px;
      color: #e53935;
      border-left: 5px solid #e53935;
      padding-left: 10px;
    }
    ul {
      list-style: none;
    }
    ul li {
      margin: 12px 0;
      padding-left: 30px;
      position: relative;
      font-size: 18px;
    }
    ul li::before {
      content: "▸";
      position: absolute;
      left: 0;
      color: #e53935;
      font-size: 20px;
    }

    section p, section a {
      font-size: 18px;
      color: #ddd;
    }
    a {
      text-decoration: none;
      color: #e53935;
    }
    a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #000;
      color: #777;
      font-size: 14px;
      margin-top: 50px;
    }

    /* Animacje */
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9);}
      to { opacity: 1; transform: scale(1);}
    }
    @keyframes slideUp {
      from { opacity: 0; transform: translateY(40px);}
      to { opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Trockenausbau Nowak Logo">
    <h1>TROCKENAUSBAU MATEUSZ NOWAK</h1>
    <p>Mehr als nur Trockenbau.</p>
  </header>

  <section>
    <h2>Unsere Leistungen</h2>
    <ul>
      <li>Trockenbau</li>
      <li>Akustikdecken</li>
      <li>Trennwände</li>
      <li>Spachtelarbeiten</li>
      <li>Dämmung</li>
      <li>Innenausbau</li>
    </ul>
  </section>

  <section>
    <h2>Kontakt</h2>
    <p><strong>Adresse:</strong> Am Brink 10, 38176 Wendeburg</p>
    <p><strong>Telefon:</strong> <a href="tel:+4915152210271">+49 151 52210271</a></p>
    <p><strong>Email:</strong> <a href="mailto:trockenausbaunowak@gmail.com">trockenausbaunowak@gmail.com</a></p>
  </section>

  <footer>
    © 2025 Trockenausbau Mateusz Nowak – Alle Rechte vorbehalten
  </footer>

</body>
</html>
