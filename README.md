<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KRUSHURT - Originalmente teu</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background: #fafafa;
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
      font-size: 2rem;
      letter-spacing: 4px;
      color: #111;
    }

    header p {
      font-style: italic;
      font-weight: 600;
      color: #aa0000;
      letter-spacing: 2px;
      font-size: 1.1rem;
    }

    nav {
      margin-top: 20px;
      margin-bottom: 40px;
      text-align: center;
    }

    nav a {
      text-decoration: none;
      color: #222;
      font-weight: 600;
      margin: 0 20px;
      font-size: 1.1rem;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #aa0000;
    }

    section {
      padding-bottom: 60px;
      border-bottom: 1px solid #eee;
    }

    section:last-child {
      border-bottom: none;
    }

    h2 {
      font-weight: 900;
      font-size: 1.8rem;
      margin-bottom: 20px;
      letter-spacing: 2px;
      color: #111;
      text-align: center;
    }

    p {
      max-width: 700px;
      font-weight: 400;
      font-size: 1rem;
      color: #444;
      margin: auto;
      text-align: center;
      margin-bottom: 20px;
    }

    .collection-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .item {
      background: #fff;
      padding: 15px;
      border: 1px solid #ddd;
      border-radius: 8px;
      text-align: center;
      box-shadow: 2px 2px 6px rgba(0,0,0,0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .item:hover {
      transform: translateY(-5px);
      box-shadow: 4px 6px 12px rgba(0,0,0,0.1);
    }

    .item img {
      max-width: 100%;
      height: auto;
      border-radius: 6px;
      margin-bottom: 15px;
    }

    .lyric {
      font-style: italic;
      color: #aa0000;
      font-weight: 600;
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      padding: 30px 0;
      font-size: 0.9rem;
      color: #888;
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
    <p>Peças personalizadas com atitude, unindo as tuas letras favoritas a imagens impactantes para dar asas à tua originalidade.</p>
  </section>

  <section id="colecao">
    <h2>Coleção</h2>
    <div class="collection-grid">
      <div class="item">
        <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?auto=format&fit=crop&w=400&q=80" alt="T-shirt Crânio 1" />
        <div class="lyric">"No fear, no pain, just rock and roll."</div>
        <div>T-shirt Skull Rock</div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" alt="T-shirt Crânio 2" />
        <div class="lyric">"Lost in the shadows of the night."</div>
        <div>T-shirt Dark Skull</div>
      </div>
      <div class="item">
        <img src="https://images.unsplash.com/photo-1520975691830-94d4b8e376f1?auto=format&fit=crop&w=400&q=80" alt="T-shirt Crânio 3" />
        <div class="lyric">"Scream the words that set you free."</div>
        <div>T-shirt Rebel Skull</div>
      </div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre a KRUSHURT</h2>
    <p>KRUSHURT nasceu da paixão pela música, arte e autenticidade. Criamos peças que falam a tua língua, com design impactante e alma rebelde. Cada peça é feita para quem não tem medo de ser original.</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Quer saber mais? Fala conosco no email:</p>
    <p><a href="mailto:geral@krushurt.pt" style="color:#aa0000; font-weight:600;">geral@krushurt.pt</a></p>
  </section>

  <footer>
    <p>© 2025 KRUSHURT.</p>
  </footer>

</body>
</html>
  <footer>
    <p>© 2025 KRUSHURT.</p>
  </footer>

</body>
</html>
