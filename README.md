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
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #121212;
      color: #eee;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem 1rem;
    }

    header {
      text-align: center;
      margin-bottom: 2rem;
    }

    header h1 {
      font-size: 3rem;
      letter-spacing: 0.15em;
      font-weight: 900;
      color: #f04e30;
      margin-bottom: 0.2rem;
    }

    header p {
      font-size: 1.2rem;
      font-style: italic;
      color: #bbb;
    }

    main {
      max-width: 900px;
      width: 100%;
      text-align: center;
    }

    .hero-img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-bottom: 2rem;
      filter: drop-shadow(0 0 6px #f04e30);
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-bottom: 3rem;
      flex-wrap: wrap;
    }

    .btn {
      background-color: #f04e30;
      border: none;
      color: white;
      padding: 0.85rem 2.2rem;
      font-size: 1.1rem;
      font-weight: 700;
      border-radius: 35px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(240, 78, 48, 0.7);
      transition: background-color 0.3s ease, transform 0.2s ease;
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      user-select: none;
    }

    .btn:hover {
      background-color: #d93e1d;
      transform: scale(1.05);
      box-shadow: 0 6px 15px rgba(217, 62, 29, 0.9);
    }

    .btn:active {
      transform: scale(0.97);
    }

    section.gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.5rem;
      margin-bottom: 3rem;
    }

    section.gallery img {
      width: 100%;
      height: 260px;
      object-fit: cover;
      border-radius: 15px;
      filter: drop-shadow(0 0 8px #f04e30);
      transition: transform 0.3s ease;
      cursor: pointer;
    }

    section.gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      font-size: 0.9rem;
      color: #666;
      text-align: center;
      margin-top: auto;
      padding-top: 1rem;
      user-select: none;
    }

    /* Responsivo */
    @media (max-width: 480px) {
      header h1 {
        font-size: 2.2rem;
      }
      .btn {
        font-size: 1rem;
        padding: 0.75rem 1.5rem;
      }
      section.gallery img {
        height: 200px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>KRUSHURT</h1>
    <p>Originalmente teu</p>
  </header>

  <main>
    <img 
      class="hero-img" 
      src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80" 
      alt="Imagem estilizada de crânio com arte gráfica" 
    />

    <div class="buttons">
      <a href="#" class="btn" title="Comprar no site">Comprar no site</a>
      <a href="#" class="btn" title="Instagram KRUSHURT">Instagram</a>
      <a href="mailto:geral@krushurt.pt" class="btn" title="Contactar por email">Contactar</a>
    </div>

    <section class="gallery" aria-label="Galeria de imagens KRUSHURT">
      <img src="https://images.unsplash.com/photo-1549924231-f129b911e442?auto=format&fit=crop&w=400&q=80" alt="Esqueleto estilizado 1" />
      <img src="https://images.unsplash.com/photo-1532888052211-57d869f86db3?auto=format&fit=crop&w=400&q=80" alt="Crânio estilizado 2" />
      <img src="https://images.unsplash.com/photo-1523983304280-0561ecb4d02e?auto=format&fit=crop&w=400&q=80" alt="Esqueleto estilizado 3" />
    </section>
  </main>

  <footer>
    © 2025 KRUSHURT. Todos os direitos reservados.
  </footer>
</body>
</html>
