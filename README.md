<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JS XPLAY - Sua TV Online Premium</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #141414;
      color: #fff;
    }

    header {
      background-color: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      color: #e50914;
      font-size: 2rem;
    }

    nav a {
      margin-left: 2rem;
      text-decoration: none;
      color: #fff;
      font-weight: 500;
    }

    .hero {
      background-image: url('https://images.unsplash.com/photo-1603481546579-81b5ecb7cb9b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80');
      background-size: cover;
      background-position: center;
      padding: 10rem 2rem;
      text-align: center;
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }

    .btn {
      background-color: #e50914;
      padding: 1rem 2rem;
      color: white;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      transition: 0.3s;
    }

    .btn:hover {
      background-color: #b20710;
    }

    .section {
      padding: 4rem 2rem;
      text-align: center;
    }

    .plans {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }

    .plan {
      background-color: #222;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.6);
    }

    .plan h3 {
      font-size: 1.5rem;
      color: #e50914;
    }

    .plan ul {
      list-style: none;
      margin: 1rem 0;
      padding: 0;
      text-align: left;
    }

    .plan ul li {
      margin-bottom: 0.5rem;
    }

    .plan a {
      margin-top: 1rem;
      display: inline-block;
    }

    .footer {
      background-color: #000;
      color: #999;
      text-align: center;
      padding: 2rem;
    }

    .floating-whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      padding: 1rem;
      border-radius: 50%;
      font-size: 2rem;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
      z-index: 999;
    }
  </style>
</head>

<body>
  <header>
    <h1>JS XPLAY</h1>
    <nav>
      <a href="#planos">Planos</a>
      <a href="#instalacao">Guia de Instalação</a>
      <a href="https://wa.me/5577999771690" target="_blank">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h2>TV Online Premium em Alta Definição</h2>
    <p>Mais de 2.800 canais, 20 mil filmes e 8.400 séries ao seu alcance</p>
    <a href="https://wa.me/5577999771690?text=Quero%20testar%20grátis%20a%20lista%20IPTV" class="btn">Teste Grátis</a>
  </section>

  <section class="section" id="planos">
    <h2>Escolha seu Plano</h2>
    <div class="plans">
      <div class="plan">
        <h3>1 Mês - R$25</h3>
        <ul>
          <li>+2.800 canais (abertos, fechados, esportes)</li>
          <li>+20.000 filmes atualizados</li>
          <li>+8.400 séries completas</li>
          <li>Suporte rápido via WhatsApp</li>
          <li>Qualidade HD e Full HD</li>
        </ul>
        <a class="btn" href="https://wa.me/5577999771690?text=Quero%20assinar%20o%20plano%20de%201%20mês">Assinar Agora</a>
      </div>
      <div class="plan">
        <h3>2 Meses - R$45</h3>
        <ul>
          <li>Todos os benefícios do plano mensal</li>
          <li>Desconto exclusivo</li>
        </ul>
        <a class="btn" href="https://wa.me/5577999771690?text=Quero%20assinar%20o%20plano%20de%202%20meses">Assinar Agora</a>
      </div>
      <div class="plan">
        <h3>3 Meses - R$65</h3>
        <ul>
          <li>Todos os benefícios + bônus exclusivos</li>
        </ul>
        <a class="btn" href="https://wa.me/5577999771690?text=Quero%20assinar%20o%20plano%20de%203%20meses">Assinar Agora</a>
      </div>
      <div class="plan">
        <h3>6 Meses - R$120</h3>
        <ul>
          <li>Acesso prolongado com super desconto</li>
        </ul>
        <a class="btn" href="https://wa.me/5577999771690?text=Quero%20assinar%20o%20plano%20de%206%20meses">Assinar Agora</a>
      </div>
      <div class="plan">
        <h3>1 Ano - R$229,90</h3>
        <ul>
          <li>Plano mais completo com economia máxima</li>
        </ul>
        <a class="btn" href="https://wa.me/5577999771690?text=Quero%20assinar%20o%20plano%20anual">Assinar Agora</a>
      </div>
    </div>
  </section>

  <section class="section" id="instalacao">
    <h2>Guia de Instalação</h2>
    <p>Escolha seu dispositivo para ver o passo a passo</p>
    <div class="plans">
      <div class="plan">
        <h3>TV Samsung</h3>
        <a class="btn" href="https://www.youtube.com/watch?v=EXEMPLO1">Ver Instalação</a>
      </div>
      <div class="plan">
        <h3>TV LG</h3>
        <a class="btn" href="https://www.youtube.com/watch?v=EXEMPLO2">Ver Instalação</a>
      </div>
      <div class="plan">
        <h3>TV Box</h3>
        <a class="btn" href="https://www.youtube.com/watch?v=EXEMPLO3">Ver Instalação</a>
      </div>
      <div class="plan">
        <h3>Celular Android</h3>
        <a class="btn" href="https://www.youtube.com/watch?v=EXEMPLO4">Ver Instalação</a>
      </div>
      <div class="plan">
        <h3>PC / Windows</h3>
        <a class="btn" href="https://www.youtube.com/watch?v=EXEMPLO5">Ver Instalação</a>
      </div>
    </div>
  </section>

  <footer class="footer">
    <p>&copy; 2025 JS XPLAY - Todos os direitos reservados.</p>
  </footer>

  <a href="https://wa.me/5577999771690" target="_blank" class="floating-whatsapp">
    <i class="fab fa-whatsapp"></i>
  </a>
</body>

</html>
