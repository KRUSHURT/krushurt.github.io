<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KRUSHURT - T-shirts Personalizadas</title>
  
  <!-- Fonte característica, marcante -->
  <link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet" />
  
  <style>
    body {
      background-color: #fafafa;
      color: #222;
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.5;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header {
      background-color: #fff;
      padding: 2rem 1rem;
      border-bottom: 3px solid #ff4a4a;
      text-align: center;
      font-family: 'Anton', sans-serif;
      font-size: 3rem;
      letter-spacing: 0.15em;
      color: #ff4a4a;
      user-select: none;
    }

    main {
      flex: 1;
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    .slogan {
      font-family: 'Anton', sans-serif;
      text-align: center;
      font-size: 1.5rem;
      color: #ff4a4a;
      margin-bottom: 3rem;
      user-select: none;
      text-transform: uppercase;
      letter-spacing: 0.1em;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }

    .card {
      background-color: #fff;
      border: 2px solid #ff4a4a;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgb(255 74 74 / 0.2);
      transition: box-shadow 0.3s ease;
      cursor: pointer;
    }

    .card:hover {
      box-shadow: 0 8px 16px rgb(255 74 74 / 0.4);
    }

    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      display: block;
    }

    .card-content {
      padding: 1rem;
      text-align: center;
    }

    .card-content h3 {
      font-family: 'Anton', sans-serif;
      color: #ff4a4a;
      font-size: 1.4rem;
      margin-bottom: 0.75rem;
      user-select: none;
      text-transform: uppercase;
      letter-spacing: 0.05em;
    }

    .buy-btn {
      display: inline-block;
      padding: 0.6rem 1.5rem;
      font-weight: 700;
      color: #fff;
      background-color: #ff4a4a;
      border: none;
      border-radius: 30px;
      text-decoration: none;
      transition: background-color 0.3s ease;
      cursor: pointer;
      user-select: none;
    }

    .buy-btn:hover {
      background-color: #cc3a3a;
    }

    footer {
      background-color: #fff;
      border-top: 3px solid #ff4a4a;
      padding: 1rem 1rem;
      text-align: center;
      font-size: 0.9rem;
      color: #666;
      user-select: none;
    }

    .social-links a {
      color: #ff4a4a;
      text-decoration: none;
      font-weight: 700;
      margin: 0 0.75rem;
      transition: color 0.3s ease;
    }

    .social-links a:hover {
      color: #cc3a3a;
    }

    @media (max-width: 600px) {
      header {
        font-size: 2.5rem;
      }
      .card img {
        height: 180px;
      }
    }
  </style>
</head>
<body>
  <header>KRUSHURT</header>

  <main>
    <p class="slogan">EXPRESS YOUR STYLE</p>

    <section class="gallery">
      <article class="card">
        <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?auto=format&fit=crop&w=400&q=80" alt="T-shirt Skull Design 1" />
        <div class="card-content">
          <h3>Crânio Flamejante</h3>
          <a href="#" class="buy-btn">Comprar</a>
        </div>
      </article>

      <article class="card">
        <img src="https://images.unsplash.com/photo-1520975917086-3ab00af81f0d?auto=format&fit=crop&w=400&q=80" alt="T-shirt Skull Design 2" />
        <div class="card-content">
          <h3>Esqueleto Rebelde</h3>
          <a href="#" class="buy-btn">Comprar</a>
        </div>
      </article>

      <article class="card">
        <img src="https://images.unsplash.com/photo-1491553895911-0055eca6402d?auto=format&fit=crop&w=400&q=80" alt="T-shirt Skull Design 3" />
        <div class="card-content">
          <h3>Letra Mortal</h3>
          <a href="#" class="buy-btn">Comprar</a>
        </div>
      </article>
    </section>
  </main>

  <footer>
    <div class="social-links">
      <a href="https://instagram.com/krushurt" target="_blank" rel="noopener noreferrer">Instagram</a> |
      <a href="https://facebook.com/krushurt" target="_blank" rel="noopener noreferrer">Facebook</a> |
      <a href="https://twitter.com/krushurt" target="_blank" rel="noopener noreferrer">Twitter</a>
    </div>
    <p>© 2025 KRUSHURT. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
