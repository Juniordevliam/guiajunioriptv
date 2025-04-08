<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JS XPLAY - Sua Plataforma IPTV</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background-color: #000;
      color: #fff;
      line-height: 1.6;
    }

    header {
      background: url('https://images.unsplash.com/photo-1607672401803-0d7ec3fcd6dc?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 2rem;
    }

    header img.logo {
      max-width: 180px;
      margin-bottom: 1.5rem;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    header p {
      font-size: 1.1rem;
      margin-bottom: 2rem;
    }

    .btn {
      background-color: #e50914;
      padding: 0.8rem 1.5rem;
      color: white;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      transition: background 0.3s;
    }

    .btn:hover {
      background-color: #b00710;
    }

    section img.responsive-img {
      width: 100%;
      height: auto;
      display: block;
      margin: 0 auto;
    }

    section.benefits, section.plans, section.guide {
      padding: 3rem 1rem;
      text-align: center;
      background-color: #111;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
    }

    .benefits .card-container,
    .plans .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: #1a1a1a;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.05);
    }

    .card h3 {
      font-size: 1.4rem;
      margin-bottom: 0.8rem;
    }

    .card p {
      font-size: 1rem;
    }

    .guide .buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }

    .guide a {
      background-color: #e50914;
      color: white;
      padding: 0.7rem 1.3rem;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }

    .whatsapp-chat {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.8rem;
      text-decoration: none;
      z-index: 1000;
      box-shadow: 0 0 10px #000;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 1.8rem;
      }
      header p {
        font-size: 1rem;
      }
    }
  </style>
</head>

<body>
  <header>
    <img src="https://via.placeholder.com/180x80?text=JS+XPLAY" alt="JS XPLAY Logo" class="logo">
    <h1>Filmes, Séries e Canais ao Vivo em uma só plataforma</h1>
    <p>Mais de 2.800 canais, 20 mil filmes e 8.400 séries disponíveis 24h</p>
    <a href="https://wa.me/5577999771690?text=Quero+testar+o+IPTV+gratis!" class="btn">TESTAR GRÁTIS</a>
  </header>

  <section>
    <img src="https://images.unsplash.com/photo-1608534509186-d396abba0e2c?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80" alt="Banner de entretenimento" class="responsive-img">
  </section>

  <section class="benefits">
    <h2>Vantagens Exclusivas</h2>
    <div class="card-container">
      <div class="card">
        <h3>+2.800 Canais</h3>
        <p>Incluindo esportes, filmes, infantis, documentários, notícias e muito mais.</p>
      </div>
      <div class="card">
        <h3>+20.000 Filmes</h3>
        <p>Lançamentos e clássicos em alta definição com áudio e legenda.</p>
      </div>
      <div class="card">
        <h3>+8.400 Séries</h3>
        <p>Temporadas completas das principais plataformas de streaming.</p>
      </div>
    </div>
  </section>

  <section class="plans">
    <h2>Planos com Desconto</h2>
    <div class="card-container">
      <div class="card">
        <h3>1 Mês - R$ 25,00</h3>
        <p>Acesso completo, suporte 24h, conteúdo full HD. (0% desconto)</p>
        <a href="https://wa.me/5577999771690?text=Quero+o+plano+mensal+de+R$25,00" class="btn">Escolher plano</a>
      </div>
      <div class="card">
        <h3>2 Meses - R$ 45,00</h3>
        <p>Economize 10% com suporte e canais premium.</p>
        <a href="https://wa.me/5577999771690?text=Quero+o+plano+de+2+meses+por+R$45,00" class="btn">Escolher plano</a>
      </div>
      <div class="card">
        <h3>3 Meses - R$ 65,00</h3>
        <p>Desconto de 13%. Conteúdo completo e atualizações diárias.</p>
        <a href="https://wa.me/5577999771690?text=Quero+o+plano+trimestral+de+R$65,00" class="btn">Escolher plano</a>
      </div>
      <div class="card">
        <h3>6 Meses - R$ 120,00</h3>
        <p>Desconto de 20%. Atendimento prioritário e acesso vitalício por período.</p>
        <a href="https://wa.me/5577999771690?text=Quero+o+plano+semestral+de+R$120,00" class="btn">Escolher plano</a>
      </div>
      <div class="card">
        <h3>12 Meses - R$ 229,90</h3>
        <p>Desconto de 24%. Plano completo com renovação facilitada.</p>
        <a href="https://wa.me/5577999771690?text=Quero+o+plano+anual+de+R$229,90" class="btn">Escolher plano</a>
      </div>
    </div>
  </section>

  <section class="guide">
    <h2>Guia de Instalação</h2>
    <div class="buttons">
      <a href="https://youtu.be/XO82hctuvl0" target="_blank">TV SAMSUNG</a>
      <a href="https://youtu.be/XO82hctuvl0" target="_blank">TV LG</a>
      <a href="https://youtu.be/XO82hctuvl0" target="_blank">TV ROKU</a>
      <a href="https://youtu.be/XO82hctuvl0" target="_blank">TV BOX</a>
      <a href="https://youtu.be/XO82hctuvl0" target="_blank">PHILCO / AOC ANTIGA</a>
      <a href="https://youtu.be/XO82hctuvl0" target="_blank">PC</a>
      <a href="https://youtu.be/XO82hctuvl0" target="_blank">CELULAR</a>
    </div>
  </section>

  <a class="whatsapp-chat" href="https://wa.me/5577999771690" target="_blank">
    <i class="fab fa-whatsapp"></i>
  </a>
</body>

</html>
