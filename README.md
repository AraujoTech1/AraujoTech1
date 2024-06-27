<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fernanda Araujo</title>
  <style>
    /* Estilo personalizado */
    body {
      font-family: sans-serif;
      line-height: 1.5;
    }
    
    .emoji {
      font-size: 1.2em;
      margin: 0 0.2em;
    }

    .highlight {
      color: blue;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Fernanda Araujo</h1>
  <p>Olá! Sou apaixonada por tecnologia, e projetos em Cloud. ☁️💡</p>

  <p>Minha jornada profissional começou no atendimento ao cliente, onde desenvolvi habilidades em organização, resiliência e trabalho em equipe. </p>

  <p>Mas meu verdadeiro sonho sempre foi trabalhar com tecnologia. Desde sempre, me fascino pelo mundo digital e, na busca por conhecimento, encontrei minha paixão pela área de Cloud. </p>

  <p>Atualmente, estou aprimorando minhas habilidades em Cloud Computing e buscando oportunidades para colaborar em projetos. </p>

  <p>[✉️ Entre em contato comigo](mailto:xfernandaaraujo@gmail.com)</p>

  <p>⚡ Curiosidade: Sou autodidata e dinâmica, sempre buscando novos desafios e aprendizados!</p>

  <script>
    document.addEventListener("DOMContentLoaded", function() {
        const keyword = "tecnologia";
        const elements = document.querySelectorAll("p");

        elements.forEach(element => {
            element.innerHTML = element.innerHTML.replace(new RegExp(keyword, 'g'), `<span class="highlight">${keyword}</span>`);
        });
    });
  </script>
</body>
</html>
