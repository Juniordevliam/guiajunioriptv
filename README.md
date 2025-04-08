<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JS XPLAY - Sua IPTV Completa</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    .countdown {
      font-size: 1.5rem;
      font-weight: bold;
    }
    .whatsapp-float {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 40px;
      right: 40px;
      background-color: #e50914;
      color: #fff;
      border-radius: 50px;
      text-align: center;
      font-size: 30px;
      z-index: 100;
    }
    .whatsapp-float i {
      margin-top: 16px;
    }
    .netflix-banner {
      background: url('https://cdn.pixabay.com/photo/2020/05/06/06/56/home-cinema-5136777_1280.jpg') center center / cover no-repeat;
      height: 100vh;
    }
    @media (max-width: 768px) {
      .netflix-banner {
        background-position: top center;
        height: 70vh;
      }
    }
  </style>
</head>

<body class="bg-black text-white">
  <!-- Banner estilo Netflix -->
  <header class="netflix-banner flex items-center justify-center px-4">
    <div class="text-center bg-black bg-opacity-60 p-6 rounded-xl">
      <h1 class="text-4xl md:text-6xl font-bold mb-4">JS XPLAY</h1>
      <p class="text-lg md:text-xl mb-6">+2.800 canais | +20.000 filmes | +8.400 séries em uma só assinatura!</p>
      <a href="#planos" class="bg-red-600 hover:bg-red-700 text-white py-3 px-6 rounded-full text-lg font-semibold">Conheça os Planos</a>
    </div>
  </header>

  <!-- Planos -->
  <section id="planos" class="py-16 px-6 text-center">
    <h2 class="text-4xl font-bold mb-10">Planos e Preços</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <div class="border border-red-500 p-6 rounded-xl bg-gray-900">
        <h3 class="text-2xl font-bold">1 Mês</h3>
        <p class="text-xl text-red-400 mt-2">R$ 25,00</p>
        <ul class="mt-4 text-sm text-left">
          <li>✔ Acesso Full HD</li>
          <li>✔ +2.800 Canais</li>
          <li>✔ +20.000 Filmes</li>
          <li>✔ +8.400 Séries</li>
          <li>✔ Sem travamentos</li>
          <li>✔ Suporte dedicado</li>
        </ul>
        <a href="https://wa.me/5577999771690?text=Quero%20o%20plano%20de%201%20mês" class="mt-4 inline-block bg-red-600 hover:bg-red-700 py-2 px-4 rounded-full">Assinar Agora</a>
      </div>
      <div class="border border-red-500 p-6 rounded-xl bg-gray-900">
        <h3 class="text-2xl font-bold">3 Meses <span class="text-sm text-green-400">(13% OFF)</span></h3>
        <p class="text-xl text-red-400 mt-2">R$ 65,00</p>
        <ul class="mt-4 text-sm text-left">
          <li>✔ Todos os benefícios do plano mensal</li>
        </ul>
        <a href="https://wa.me/5577999771690?text=Quero%20o%20plano%20de%203%20meses" class="mt-4 inline-block bg-red-600 hover:bg-red-700 py-2 px-4 rounded-full">Assinar Agora</a>
      </div>
      <div class="border border-red-500 p-6 rounded-xl bg-gray-900">
        <h3 class="text-2xl font-bold">1 Ano <span class="text-sm text-green-400">(24% OFF)</span></h3>
        <p class="text-xl text-red-400 mt-2">R$ 229,90</p>
        <ul class="mt-4 text-sm text-left">
          <li>✔ Todos os benefícios + estabilidade garantida</li>
        </ul>
        <a href="https://wa.me/5577999771690?text=Quero%20o%20plano%20anual" class="mt-4 inline-block bg-red-600 hover:bg-red-700 py-2 px-4 rounded-full">Assinar Agora</a>
      </div>
    </div>
  </section>

  <!-- Benefícios -->
  <section class="py-16 px-6 bg-gray-800 text-center">
    <h2 class="text-3xl font-bold mb-8">Benefícios Exclusivos</h2>
    <p class="mb-4 text-gray-300">Economize comparado com plataformas como:</p>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-left">
      <div>
        <h3 class="text-xl font-semibold">Netflix</h3>
        <p>R$ 55,90/mês</p>
      </div>
      <div>
        <h3 class="text-xl font-semibold">Amazon Prime</h3>
        <p>R$ 14,90/mês</p>
      </div>
      <div>
        <h3 class="text-xl font-semibold">Disney+, HBO, Telecine...</h3>
        <p>+R$ 100,00/mês</p>
      </div>
    </div>
    <p class="mt-6 text-green-400 font-semibold">Com JS XPLAY, você tem tudo isso incluso por uma fração do preço!</p>
  </section>

  <!-- Guia de Instalação -->
  <section id="guia" class="py-16 px-6 text-center">
    <h2 class="text-3xl font-bold mb-6">Guia de Instalação</h2>
    <p class="mb-4">Escolha seu dispositivo e siga o passo a passo:</p>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
      <a href="https://www.youtube.com/watch?v=EXEMPLO1" class="bg-red-700 p-4 rounded-lg">TV LG - MAX PLAYER</a>
      <a href="https://www.youtube.com/watch?v=EXEMPLO2" class="bg-red-700 p-4 rounded-lg">TV Samsung - SMARTONE</a>
      <a href="https://www.youtube.com/watch?v=EXEMPLO3" class="bg-red-700 p-4 rounded-lg">TV Box - IBOR PRO</a>
      <a href="https://www.youtube.com/watch?v=EXEMPLO4" class="bg-red-700 p-4 rounded-lg">PC - MAX PLAYER</a>
    </div>
  </section>

  <!-- Contagem Regressiva -->
  <section class="py-10 text-center bg-black">
    <h2 class="text-2xl font-bold mb-2">Oferta Especial se encerra em:</h2>
    <div id="countdown" class="countdown text-red-500"></div>
  </section>

  <!-- Chat WhatsApp -->
  <a href="https://wa.me/5577999771690" class="whatsapp-float" target="_blank">
    <i class="fab fa-whatsapp"></i>
  </a>

  <script>
    const countdownDate = new Date().getTime() + 24 * 60 * 60 * 1000;
    const timer = setInterval(function () {
      const now = new Date().getTime();
      const distance = countdownDate - now;
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);
      document.getElementById("countdown").innerHTML = `${hours}h ${minutes}m ${seconds}s`;
      if (distance < 0) {
        clearInterval(timer);
        document.getElementById("countdown").innerHTML = "Promoção encerrada";
      }
    }, 1000);
  </script>

</body>

</html>
