<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KRUSHURT - Originalmente teu</title>
  
  <!-- Google Fonts: Montserrat -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />

  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      background: #fff;
      color: #222;
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-bottom: 30px;
      border-bottom: 1px solid #ddd;
    }

    header h1 {
      font-weight: 900;
      font-size: 2.5rem;
      letter-spacing: 5px;
      color: #111;
      text-transform: uppercase;
    }

    header p {
      font-style: italic;
      font-weight: 600;
      color: #b22222;
      letter-spacing: 2px;
      font-size: 1.2rem;
      font-family: 'Montserrat', sans-serif;
    }

    nav {
      margin-top: 25px;
      margin-bottom: 45px;
      text-align: center;
    }

    nav a {
      text-decoration: none;
      color: #222;
      font-weight: 600;
      margin: 0 25px;
      font-size: 1.15rem;
      transition: color 0.3s ease;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    nav a:hover {
      color: #b22222;
    }

    section {
      padding-bottom: 60px;
      border-bottom: 1px solid #eee;
    }

    section:last-child {
      border-bottom: none;
    }

    h2 {
      font-weight: 800;
      font-size: 2rem;
      margin-bottom: 25px;
      letter-spacing: 3px;
      color: #111;
      text-align: center;
      text-transform: uppercase;
    }

    p {
      max-width: 700px;
      font-weight: 400;
      font-size: 1.05rem;
      color: #444;
      margin: auto;
      text-align: center;
      margin-bottom: 25px;
    }

    .collection-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(260px,1fr));
      gap: 30px;
      margin-top: 35px;
    }

    .item {
      background: #fafafa;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .item:hover {
      transform: translateY(-7px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }

    .item img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      margin-bottom: 18px;
      filter: grayscale(20%);
      transition: filter 0.3s ease;
    }

    .item:hover img {
      filter: grayscale(0%);
    }

    .lyric {
      font-style: italic;
      color: #b22222;
      font-weight: 600;
      margin-bottom: 15px;
      font-size: 1rem;
      min-height: 48px;
    }

    footer {
      text-align: center;
      padding: 35px 0;
      font-size: 0.9rem;
      color: #888;
      letter-spacing: 1px;
      text-transform: uppercase;
    }

  </style>
</head>
<body>

  <header>
    <div>
      <h1>KRUSHURT</h1>
      <p>Originalmente teu</p>
    </div>
  </header>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#colecao">Coleção</a>
    <a href="#sobre">Sobre</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="inicio">
    <h2>Bem-vindo à KRUSHURT</h2>
    <p>Camisas personalizadas com atitude, unindo letras icônicas de bandas e imagens impactantes de esqueletos e crânios para expressar sua originalidade.</p>
  </section>

  <section id="colecao">
    <h2>Coleção</h2>
    <div class="collection-grid">
      <div class="item">
        <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=400&q=80" alt="T-shirt Crânio 1" />
        <div class="lyric">"No fear, no pain, just rock and roll."</div>
        <div>T-shirt Skull Rock</div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1527434001472-f1f687d2e60a?auto=format&fit=crop&w=400&q=80" alt="T-shirt Crânio 2" />
        <div class="lyric">"Lost in the shadows of the night."</div>
        <div>T-shirt Dark Skull</div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1530629013299-6cb85f98e317?auto=format&fit=crop&w=400&q=80" alt="T-shirt Crânio 3" />
        <div class="lyric">"Scream the words that set you free."</div>
        <div>T-shirt Rebel Skull</div>
      </div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre a KRUSHURT</h2>
    <p>KRUSHURT nasceu da paixão pela música, arte e autenticidade. Criamos camisetas que falam a sua língua, com design impactante e alma rebelde. Cada peça é feita para quem não tem medo de ser original.</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Quer saber mais? Fale conosco no email:</p>
    <p><a href="mailto:geral@krushurt.pt" style="color:#b22222; font-weight:600;">geral@krushurt.pt</a></p>
  </section>

  <footer>
    <p>© 2025 KRUSHURT. Originalmente teu.</p>
  </footer>

</body>
</html>
  <footer>
    <p>© 2025 KRUSHURT.</p>
  </footer>

</body>
</html>
