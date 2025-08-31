<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trockenausbau Mateusz Nowak</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Segoe UI', sans-serif; background: #0f0f0f; color: #eee; }
    a { color: #e53935; text-decoration: none; }
    a:hover { text-decoration: underline; }

    /* HERO */
    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #111, #222);
      text-align: center;
    }
    header img { max-width: 200px; margin-bottom: 20px; animation: fadeIn 2s ease; }
    header h1 { font-size: 40px; letter-spacing: 2px; color: #e53935; }
    header p { font-size: 20px; color: #aaa; margin-top: 10px; }

    /* SEKCJE */
    section { max-width: 1100px; margin: 60px auto; padding: 30px; }
    section h2 {
      font-size: 28px; color: #e53935;
      border-left: 6px solid #e53935; padding-left: 15px; margin-bottom: 25px;
    }
    section p { font-size: 18px; line-height: 1.6; color: #ddd; }

    /* PORTFOLIO GRID */
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
    .grid img {
      width: 100%; border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.6);
      transition: transform 0.3s;
    }
    .grid img:hover { transform: scale(1.05); }

    /* LISTA USŁUG */
    ul { list-style: none; }
    ul li { margin: 12px 0; font-size: 18px; padding-left: 30px; position: relative; }
    ul li::before { content: "✔"; position: absolute; left: 0; color: #e53935; }

    /* KONTAKT */
    .contact p { font-size: 18px; margin: 10px 0; }

    /* FOOTER */
    footer { text-align: center; padding: 25px; background: #000; color: #777; margin-top: 50px; }

    /* ANIMACJE */
    @keyframes fadeIn { from {opacity:0; transform: scale(0.9);} to {opacity:1; transform: scale(1);} }
  </style>
</head>
<body>

  <!-- HERO -->
  <header>
    <img src="logo.png" alt="Logo Trockenausbau Nowak">
    <h1>TROCKENAUSBAU MATEUSZ NOWAK</h1>
    <p>Mehr als nur Trockenbau.</p>
  </header>

  <!-- O NAS -->
  <section>
    <h2>Über uns</h2>
    <p>
      Wir sind ein erfahrenes Bauunternehmen aus Wendeburg, spezialisiert auf Trockenbau 
      und Innenausbau. Qualität, Präzision und Zuverlässigkeit stehen bei uns an erster Stelle. 
      Unsere Mission: Räume schaffen, die sowohl funktional als auch ästhetisch überzeugen.
    </p>
  </section>

  <!-- PORTFOLIO -->
  <section>
    <h2>Portfolio</h2>
    <div class="grid">
      <img src="projekt1.jpg" alt="Projekt 1">
      <img src="projekt2.jpg" alt="Projekt 2">
      <img src="projekt3.jpg" alt="Projekt 3">
      <img src="projekt4.jpg" alt="Projekt 4">
    </div>
  </section>

  <!-- USŁUGI -->
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

  <!-- KONTAKT -->
  <section class="contact">
    <h2>Kontakt</h2>
    <p><strong>Adresse:</strong> Am Brink 10, 38176 Wendeburg</p>
    <p><strong>Telefon:</strong> <a href="tel:+4915152210271">+49 151 52210271</a></p>
    <p><strong>Email:</strong> <a href="mailto:trockenausbaunowak@gmail.com">trockenausbaunowak@gmail.com</a></p>
  </section>

  <!-- FOOTER -->
  <footer>
    © 2025 Trockenausbau Mateusz Nowak – Alle Rechte vorbehalten
  </footer>

</body>
</html>
