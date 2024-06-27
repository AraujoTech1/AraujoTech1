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
    }
    
    .highlight {
      color: lightblue;
      font-weight: bold;
    }
    
    .emoji {
      font-size: 1.2em;
      margin: 0 0.2em;
    }
    
    .content {
      max-width: 800px;
      margin: 0 auto;
    }
    
    #myChart {
      max-width: 600px;
      margin: 20px auto;
    }
    
    .contact {
      margin: 20px 0;
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

    <p class="contact"><a href="mailto:xfernandaaraujo@gmail.com">✉️ Entre em contato comigo</a></p>

    <p>⚡ Curiosidade: Sou autodidata e dinâmica, sempre buscando novos desafios e aprendizados!</p>
    
    <h2>Habilidades e Áreas de Interesse</h2>
    <img src="https://via.placeholder.com/800x400" alt="Exemplo de imagem representando tecnologia" />

    <h2>Progresso de Aprendizado</h2>
    <canvas id="myChart"></canvas>
  </div>

  <script>
    // Configuração do gráfico
    var ctx = document.getElementById('myChart').getContext('2d');
    var myChart = new Chart(ctx, {
        type: 'bar',
        data: {
            labels: ['HTML', 'CSS', 'JavaScript', 'Python', 'Cloud'],
            datasets: [{
                label: 'Nível de Proficiência',
                data: [80, 70, 85, 75, 90],
                backgroundColor: 'lightblue',
                borderColor: 'blue',
                borderWidth: 1
            }]
        },
        options: {
            scales: {
                y: {
                    beginAtZero: true
                }
            }
        }
    });
  </script>
</body>
</html>

