<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adriana Salgados & Festa</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background-color: #fff0f5;
      color: #000;
    }
    header {
      background-color: #000;
      color: #ffc0cb;
      padding: 1rem 2rem;
      text-align: center;
    }
    nav {
      margin-top: 0.5rem;
    }
    nav a {
      color: #ffc0cb;
      margin: 0 1rem;
      text-decoration: none;
    }
    section {
      padding: 2rem;
    }
    .hero {
      background-color: #ffc0cb;
      color: #000;
      text-align: center;
      padding: 4rem 2rem;
    }
    .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .card {
      background-color: #fff;
      border: 2px solid #ffc0cb;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%; height: 200px; object-fit: cover;
    }
    .card-body {
      padding: 1rem;
    }
    .button {
      background-color: #000;
      color: #ffc0cb;
      padding: 0.5rem 1rem;
      border: none;
      text-decoration: none;
      display: inline-block;
      margin-top: 1rem;
    }
    footer {
      background-color: #000;
      color: #ffc0cb;
      text-align: center;
      padding: 1rem;
    }
    form {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
    }
    form input, form textarea {
      margin-bottom: 1rem;
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      background-color: #000;
      color: #ffc0cb;
      padding: 0.75rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Adriana Salgados & Festa</h1>
    <nav>
      <a href="#portfolio">Portfólio</a>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Delícias que encantam sua festa!</h2>
    <p>Encomende seus salgados preferidos para qualquer ocasião.</p>
    <a class="button" href="https://wa.me/5511947314504" target="_blank">Fazer Pedido via WhatsApp</a>
  </section>

  <section id="portfolio">
    <h2>Portfólio de Salgados</h2>
    <div class="portfolio">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1627308595181-340e33b3a22d?auto=format&fit=crop&w=800&q=80" alt="Coxinha">
        <div class="card-body">
          <h3>Coxinha</h3>
          <p>Tradicional, crocante e recheada com frango temperado.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1611861061920-6d01dc1f0bbf?auto=format&fit=crop&w=800&q=80" alt="Esfirra">
        <div class="card-body">
          <h3>Esfirra</h3>
          <p>De carne ou queijo, com massa leve e muito sabor.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1613145998130-9e7d2825ddf9?auto=format&fit=crop&w=800&q=80" alt="Risole">
        <div class="card-body">
          <h3>Risole</h3>
          <p>Recheios variados com casquinha dourada e macia.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1627497307480-f5d0f3007f21?auto=format&fit=crop&w=800&q=80" alt="Quibe">
        <div class="card-body">
          <h3>Quibe</h3>
          <p>Clássico da culinária árabe com muito sabor.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>Com amor pela culinária e dedicação em cada detalhe, a Adriana Salgados & Festa leva sabor e alegria para sua comemoração. Trabalhamos com ingredientes frescos e receitas tradicionais para garantir a melhor experiência.</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <form>
      <input type="text" placeholder="Seu nome" required>
      <input type="email" placeholder="Seu e-mail" required>
      <textarea placeholder="Sua mensagem" rows="5" required></textarea>
      <button type="submit">Enviar</button>
    </form>
    <p style="text-align:center; margin-top: 1rem;">Ou fale direto pelo <a href="https://wa.me/5511947314504" target="_blank">WhatsApp</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Adriana Salgados & Festa. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
