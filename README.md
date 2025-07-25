<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KRUSHURT - Originalmente teu</title>

  <!-- Fontes do Google -->
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet" />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background: #fff;
      color: #111;
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-bottom: 30px;
      border-bottom: 1px solid #ccc;
    }

    header h1 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 3rem;
      letter-spacing: 4px;
      color: #111;
    }

    header p {
      font-style: italic;
      font-weight: 600;
      color: #b22222;
      letter-spacing: 1px;
    }

    nav {
      margin: 30px 0;
      text-align: center;
    }

    nav a {
      font-family: 'Bebas Neue', sans-serif;
      text-decoration: none;
      color: #111;
      margin: 0 20px;
      font-size: 1.3rem;
      letter-spacing: 2px;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #b22222;
    }

    section {
      padding: 60px 0;
      border-bottom: 1px solid #eee;
    }

    section:last-child {
      border-bottom: none;
    }

    h2 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 2.2rem;
      letter-spacing: 3px;
      text-align: center;
      color: #111;
      margin-bottom: 30px;
      text-transform: uppercase;
    }

    p {
      font-size: 1.05rem;
      max-width: 700px;
      margin: auto;
      text-align: center;
      color: #333;
      margin-bottom: 25px;
    }

    .collection-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(260px,1fr));
      gap: 30px;
      margin-top: 35px;
    }

    .item {
      background: #f8f8f8;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      transition: transform 0.3s ease;
    }

    .item:hover {
      transform: translateY(-6px);
    }

    .item img {
      width: 100%;
      height: auto;
      border-radius: 6px;
      margin-bottom: 15px;
      filter: grayscale(20%);
      transition: filter 0.3s ease;
    }

    .item:hover img {
      filter: grayscale(0%);
    }

    .lyric {
      font-style: italic;
      font-weight: 600;
      color: #b22222;
      margin-bottom: 10px;
    }

    .item-title {
      font-weight: bold;
      color: #000;
    }

    footer {
      text-align: center;
      padding: 35px 0;
      font-size: 0.85rem;
      color: #888;
      text-transform: uppercase;
      letter-spacing: 1px;
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
    <p>Camisas personalizadas com atitude — letras marcantes de bandas e ilustrações de esqueletos e crânios que expressam quem você é.</p>
  </section>

  <section id="colecao">
    <h2>Coleção</h2>
    <div class="collection-grid">
      <div class="item">
        <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=400&q=80" alt="T-shirt Skull 1" />
        <div class="lyric">"No fear, no pain, just rock and roll."</div>
        <div class="item-title">T-shirt Skull Rock</div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1527434001472-f1f687d2e60a?auto=format&fit=crop&w=400&q=80" alt="T-shirt Skull 2" />
        <div class="lyric">"Lost in the shadows of the night."</div>
        <div class="item-title">T-shirt Dark Skull</div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1530629013299-6cb85f98e317?auto=format&fit=crop&w=400&q=80" alt="T-shirt Skull 3" />
        <div class="lyric">"Scream the words that set you free."</div>
        <div class="item-title">T-shirt Rebel Skull</div>
      </div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre a marca</h2>
    <p>KRUSHURT nasceu da paixão pela música, arte e autenticidade. Criamos t-shirts com alma — estampas que gritam atitude e representam quem vive fora da caixa.</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Tem alguma dúvida ou quer fazer parte? Escreve para:</p>
    <p><a href="mailto:geral@krushurt.pt" style="color:#b22222; font-weight:600;">geral@krushurt.pt</a></p>
  </section>

  <footer>
    <p>© 2025 KRUSHURT. Originalmente teu.</p>
  </footer>

</body>
</html>
