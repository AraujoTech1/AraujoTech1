<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fernanda Araújo</title>
  <style>
    body {
      font-family: sans-serif;
      line-height: 1.5;
      margin: 20px;
      background-color: #f4f4f4;
    }
    
    .content {
      max-width: 800px;
      margin: 0 auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .highlight {
      color: lightblue;
      font-weight: bold;
    }

    h1, h2 {
      text-align: center;
    }

    .emoji {
      font-size: 1.2em;
      margin: 0 0.2em;
    }

    .contact {
      margin: 20px 0;
      text-align: center;
    }

    #myChart {
      max-width: 600px;
      margin: 20px auto;
    }

    img {
      display: block;
      max-width: 100%;
      height: auto;
      margin: 20px auto;
    }
  </style>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>
  <div class="content">
    <h1>Fernanda Araújo</h1>
    <p>Olá! Sou apaixonada por <span class="highlight">tecnologia</span> e projetos em <span class="highlight">Cloud</span>. ☁️💡</p>

    <p>Minha jornada profissional começou no atendimento ao cliente, onde desenvolvi habilidades em organização, resiliência e trabalho em equipe.</p>

    <p>Mas meu verdadeiro sonho sempre foi trabalhar com <span class="highlight">tecnologia</span>. Desde sempre, me fascino pelo mundo digital e, na busca por conhecimento, encontrei minha paixão pela área de <span class="highlight">Cloud</span>.</p>

    <p>Atualmente, estou aprimorando minhas habilidades em <span class="highlight">Cloud Computing</span> e buscando oportunidades para colaborar em projetos.</p>

    <div class="contact">
      <a href="mailto:xfernandaaraujo@gmail.com">✉️ Entre em contato comigo</a>
    </div>

    <p>⚡ Curiosidade: Sou autodidata e dinâmica, sempre buscando novos desafios e aprendizados!</p>

    <h2>Habilidades e Áreas de Interesse</h2>
    <img src="https://via.placeholder.com/800x400" alt="Exemplo de imagem representando tecnologia" />

    <h2>Progresso de Aprendizado</h2>
    <canvas id="myChart"></canvas>
  </div>

  <script>
    // Configuração do gráfico
    var ctx = document.getElementById('myChart').
