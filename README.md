<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KRUSHURT - Originalmente teu</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet" />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background: #111;
      color: #eee;
      max-width: 1200px;
      margin: auto;
      padding: 40px 20px;
    }

    header {
      text-align: center;
      margin-bottom: 50px;
    }

    header h1 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 4rem;
      letter-spacing: 6px;
      color: #fff;
    }

    header p {
      font-style: italic;
      font-weight: 600;
      color: #b22222;
      letter-spacing: 1px;
    }

    nav {
      text-align: center;
      margin-bottom: 40px;
    }

    nav a {
      font-family: 'Bebas Neue', sans-serif;
      text-decoration: none;
      color: #eee;
      margin: 0 15px;
      font-size: 1.2rem;
      letter-spacing: 2px;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #b22222;
    }

    section {
      padding: 40px 0;
      border-top: 1px solid #333;
    }

    h2 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 2.5rem;
      text-align: center;
      letter-spacing: 3px;
      color: #fff;
      margin-bottom: 25px;
    }

    p {
      font-size: 1rem;
      text-align: center;
      color: #ccc;
      margin-bottom: 25px;
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }

    .collection-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
      gap: 30px;
      margin-top: 30px;
    }

    .item {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 4px 20px rgba(0,0,0,0.3);
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
      filter: grayscale(10%);
    }

    .lyric {
      font-style: italic;
      color: #b22222;
      margin-bottom: 10px;
    }

    .item-title {
      font-weight: bold;
      font-size: 1.2rem;
      margin-bottom: 15px;
      color: #fff;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 10px;
      flex-wrap: wrap;
    }

    .buttons a {
      background: #b22222;
      color: #fff;
      text-decoration: none;
      padding: 8px 14px;
      border-radius: 5px;
      font-size: 0.9rem;
      transition: background 0.3s ease;
    }

    .buttons a:hover {
      background: #fff;
      color: #111;
    }

    footer {
      border-top: 1px solid #333;
      padding: 30px 0;
      text-align: center;
      font-size: 0.9rem;
      color: #666;
    }

    .social-icons {
      margin-top: 15px;
    }

    .social-icons i {
      font-size: 1.5rem;
      color: #888;
      margin: 0 10px;
      transition: color 0.3s ease;
    }

    .social-icons i:hover {
      color: #b22222;
    }

    a.email-link {
      color: #b22222;
      font-weight: 600;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 3rem;
      }

      h2 {
        font-size: 2rem;
      }
    }
  </style>

  <!-- Ícones Font Awesome (para redes sociais futuramente) -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>

<body>

  <header>
    <h1>KRUSHURT</h1>
    <p>Originalmente teu</p>
  </header>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#colecao">Coleção</a>
    <a href="#sobre">Sobre</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="inicio">
    <h2>Bem-vindo à KRUSHURT</h2>
    <p>T-shirts com letras de música e arte sombria — crânios, esqueletos, rebeldia e alma. Uma marca para quem vive fora da caixa.</p>
  </section>

  <section id="colecao">
    <h2>Coleção</h2>
    <div class="collection-grid">
      <div class="item">
        <img src="https://images.unsplash.com/photo-1609820733094-04c9e29113cf?auto=format&fit=crop&w=600&q=80" alt="T-shirt 1">
        <div class="lyric">"In the silence, I hear the scream."</div>
        <div class="item-title">T-shirt Skull Flame</div>
        <div class="buttons">
          <a href="#">Ver Produto</a>
          <a href="#">Comprar</a>
          <a href="#">Detalhes</a>
        </div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1614276660967-c586ef2e2330?auto=format&fit=crop&w=600&q=80" alt="T-shirt 2">
        <div class="lyric">"This is where legends rot and rise."</div>
        <div class="item-title">T-shirt Grave Anthem</div>
        <div class="buttons">
          <a href="#">Ver Produto</a>
          <a href="#">Comprar</a>
          <a href="#">Detalhes</a>
        </div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1597933882749-8c74cf0d6529?auto=format&fit=crop&w=600&q=80" alt="T-shirt 3">
        <div class="lyric">"Screaming ink on your second skin."</div>
        <div class="item-title">T-shirt Inked Bones</div>
        <div class="buttons">
          <a href="#">Ver Produto</a>
          <a href="#">Comprar</a>
          <a href="#">Detalhes</a>
        </div>
      </div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre a marca</h2>
    <p>KRUSHURT nasceu da música, da arte e da alma underground. Cada peça é uma extensão de ti: letras que marcam, visuais que impactam, rebeldia que respira.</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Queres saber mais ou fazer parte da revolução?</p>
    <p><a class="email-link" href="mailto:geral@krushurt.pt">geral@krushurt.pt</a></p>
  </section>

  <footer>
    <p>© 2025 KRUSHURT — Originalmente teu.</p>
    <div class="social-icons">
      <!-- Futuro: adicionar links reais -->
      <i class="fab fa-instagram"></i>
      <i class="fab fa-tiktok"></i>
      <i class="fab fa-facebook"></i>
    </div>
  </footer>

</body>
</html>
