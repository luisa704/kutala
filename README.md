[index.html](https://github.com/user-attachments/files/22037130/index.html)

<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <title>Feliz Aniversário, Carmen Donge!</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      scroll-behavior: smooth;
      background-color: #fff8f0;
      overflow-x: hidden;
    }

    header {
      background-color: #ff6f61;
      color: white;
      padding: 40px;
      text-align: center;
    }

    section {
      padding: 60px 20px;
      text-align: center;
      position: relative;
    }

    img {
      max-width: 300px;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }

    .mensagem {
      font-size: 1.2em;
      line-height: 1.8;
      max-width: 700px;
      margin: 40px auto;
      color: #333;
    }

    footer {
      background-color: #ff6f61;
      color: white;
      text-align: center;
      padding: 20px;
    }

    /* 🎈 Balões animados */
    .balao {
      position: absolute;
      bottom: -100px;
      width: 40px;
      height: 60px;
      background-color: red;
      border-radius: 50% 50% 45% 45%;
      animation: subir 10s linear infinite;
      opacity: 0.7;
    }

    @keyframes subir {
      0% { bottom: -100px; transform: translateX(0); }
      100% { bottom: 100vh; transform: translateX(100px); }
    }

    /* 🎊 Confetes */
    .confete {
      position: absolute;
      width: 10px;
      height: 10px;
      background-color: gold;
      animation: cair 5s linear infinite;
      opacity: 0.8;
    }

    @keyframes cair {
      0% { top: -10px; transform: rotate(0deg); }
      100% { top: 100vh; transform: rotate(360deg); }
    }
  </style>
</head>
<body>

  <header>
    <h1>🎉 Feliz Aniversário, Carmen! 🎂</h1>
    <p>Celebrando a vida de Carmen Filomena Kutala Donge</p>
  </header>
<audio controls autoplay loop src="musica_da_carmen2.mp3" type="audio/x-mp3">
</audio>
  <section>
    <img src="carmen_imagem.jpeg" alt=" foto da carmen">
    <div class="mensagem">
      Hoje o dia tem um brilho diferente,porque é o dia em que Deus nos presenteou  vida de uma mulher incrível: Carmen Filomena Kutala Donge.<br>
      Um dia que nunca passa despercebido,pois ele carrega a alegria de saber que tu existes, que és parte da nossa família e do meu coração<br><br>
      Sei que este aniversário é diferente, talvez até um pouco difícil,porque é o primeiro que passas longe de casa,longe das pessoas que sempre estiveram ao teu lado para cantar,rir,brincar e encherte-te de abraços apertados.<br>
      Mas quero que saibas que a distância nunca será capaz de diminuir o amor que sinto por ti. Pelo contrário,ela só me faz perceber ainda mais o quanto és importante e insubstituível na minha vida<br>Tenho tantas lembranças tuas,desde as nossas conversas,as risadas sem fim, até os pequenos momentos de conflito. Tudo isso mora em mim e me faz sorrir sempre que penso em ti. És mais que uma irmã, és minha amiga, uma companheira de vida e um pedaço essencial da minha história.<br>
      Hoje, mesmo não podendo estar aí contigo,quero que sintas o meu abraço através destas palavras. Fecha os olhos por um instante e imagina-me ao teu lado, a segurar a tua mão e adizer o qunto te admiro, pela força, pela coragem e pela incrível mulher que estás a se tornar<br> Tens uma luz única, que ulimina os lugares por onde passas e aquece os corações das pessoas que têm a sorte de te conhecer.
      Que este novo ciclo seja cheio de realizações, saúde e sonhos realizados. que nunca te falte a fé a esperença e, principalmente, o amor
      - porque o amor é o que tu espalhas e é também o que recebes de todos nós que te amamos.
      Irmã, nunca te esqueças: a distância é só geográfica. aqui dentro do meu coraçaõ, tu estás sempre perto.
      Feliz aniversário!Que teu sorriso continue sendo a razão de tantas alegrias, e que a vida te retribua com tudo de mais lindo.💖
    </div>
  </section>

  <footer>
    Com carinho, do teu irmão  Jeovane Donge 
  </footer>

  <!-- 🎈 Balões e 🎊 Confetes gerados dinamicamente -->
  <script>
    // Balões
    for (let i = 0; i < 10; i++) {
      let balao = document.createElement('div');
      balao.className = 'balao';
      balao.style.left = `${Math.random() * window.innerWidth}px`;
      balao.style.backgroundColor = ['red', 'blue', 'green', 'purple', 'orange'][i % 5];
      document.body.appendChild(balao);
    }

    // Confetes
    for (let i = 0; i < 30; i++) {
      let confete = document.createElement('div');
      confete.className = 'confete';
      confete.style.left = `${Math.random() * window.innerWidth}px`;
      confete.style.backgroundColor = ['gold', 'pink', 'cyan', 'lime', 'silver'][i % 5];
      confete.style.animationDuration = `${3 + Math.random() * 3}s`;
      document.body.appendChild(confete);
    }
  </script>

</body>
</html>
