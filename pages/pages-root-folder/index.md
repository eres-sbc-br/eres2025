---
layout: page-fullwidth
permalink: /index.html
title: "Contagem regressiva para o início da ERES 2024"
homepage: true
header:
  image_fullwidth: "ERES-2024_Logo.png"
---

<style>
  h1 {
    text-align: center;
  }

  #countdown-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    background-color: #f1f1f1;
    padding: 20px;
    border-radius: 10px;
  }

  .countdown-unit {
    margin: 10px;
    text-align: center;
    background-color: #ffffff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    padding: 20px;
    flex: 1;
    min-width: 125px;
  }

  .countdown-unit span {
    display: block;
    font-size: 2.5em;
    font-weight: bold;
  }

  .unit-label {
    font-size: 1em;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: #555;
  }

  .container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
    margin-top: -20px;
  }

  #countdown-title {
    font-size: 2em;
    margin-bottom: 20px;
    text-align: center;
  }

  h1, h3 {
    color: #333;
    margin: 20px 0;
    font-size: 1.8em;
  }

  .text {
    font-size: 1.1em;
    line-height: 1.6;
    color: #666;
  }

  .event-started {
    text-align: center;
    font-size: 2em;
    color: #FF6347;
    background-color: #FFF8F0;
    padding: 30px;
    margin-bottom: 1.25 rem;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  @media (max-width: 768px) {
    #countdown-container {
      flex-direction: column;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      width: 100%;
    }

    .countdown-unit {
      width: 75%;
      margin: 5px auto;
    }

    #title {
      text-align: left;
    }
  }
</style>

<section class="container">
  <div id="countdown-container">
    <div class="countdown-unit">
      <span id="days">00</span>
      <div class="unit-label">Dias</div>
    </div>
    <div class="countdown-unit">
      <span id="hours">00</span>
      <div class="unit-label">Horas</div>
    </div>
    <div class="countdown-unit">
      <span id="minutes">00</span>
      <div class="unit-label">Minutos</div>
    </div>
    <div class="countdown-unit">
      <span id="seconds">00</span>
      <div class="unit-label">Segundos</div>
    </div>
  </div>

  <h1 id="title">Bem-vindo à ERES 2024</h1>

  <p class="text">A <b>Escola Regional de Engenharia de Software (ERES)</b> é promovida anualmente pela Sociedade Brasileira de Computação (SBC). A oitava edição da escola, a <b>ERES 2024</b>, ocorrerá <b>presencialmente</b>, no período de 11 a 13 de novembro de 2024.</p>

  <p class="text">Esta edição está sendo realizada pelo <a href="http://www1.urisantiago.br/ciencia-da-computacao" target="_blank">Curso de Ciência da Computação</a> da <a href="http://www1.urisantiago.br/" target="_blank">Universidade Regional Integrada e das Missões (URI) - Campus Santiago</a>.</p>

  <p class="text">A ERES tem por objetivo disseminar o conhecimento e boas práticas em Engenharia de Software (ES), do ponto de vista profissional e acadêmico. A ERES 2024 é um espaço regional para que possam ser apresentados os resultados de pesquisas e extensão em nível de graduação e pós-graduação e relatos de experiência na indústria. Além disso, possibilitará um ambiente natural para a discussão de abordagens no ensino-aprendizagem na ES.</p>

  <p class="text">A realização da ERES 2024 oferecerá aos seus participantes atualizações do estado-da-arte da pesquisa científica na área de engenharia de software por meio da apresentação de palestras ministradas por pesquisadores e praticantes da indústria renomados. Dessa forma, este evento irá possibilitar a promoção de conceitos atuais na área, além de divulgar o que se está pesquisando em engenharia de software na região sul, no país e no mundo, inspirando, assim, o gosto pela pesquisa científica aos participantes.</p>
  <p class="text">A programação da ERES 2024 está sendo elaborada com palestras, minicursos e submissões de artigos para serem apresentados em um Fórum de Graduação, um Fórum de Pós-Graduação e um Fórum de Extensão.</p>

  <h3>Fórum de Graduação</h3>
  <p class="text">Espaço destinado para apresentação dos trabalhos de pesquisa ou relatos de experiência em Engenharia de Software, desenvolvidos por acadêmicos de graduação, principalmente das IES catarinenses, gaúchas e paranaenses.</p>

  <h3> Fórum de Pós-Graduação</h3>
  <p class="text">Espaço para apresentação de trabalhos de estudantes de pós-graduação, com o objetivo de incentivar a troca de experiências e divulgar pesquisas em andamento e/ou concluídas e resultados obtidos. Além da clareza do trabalho, relevância do tema, e qualidade da apresentação, o Comitê Científico da ERES 2024 avaliará também as contribuições científicas do trabalho.</p>

  <h3>Fórum de Extensão</h3>
  <p class="text">Espaço para apresentação de trabalhos de relatos das atividades extensionistas aplicados aos currículos de computação, especialmente da Engenharia de Software, relacionados à forma  como estão implantando a extensão em seus currículos, conforme previsto na Resolução CNE/CES nº 7, de 18 de dezembro de 2018. O objetivo é incentivar a troca de experiências entre docentes e estudantes que atuam em ações de extensão.</p>

  <script>
    const countDownDate = new Date("November 11, 2024 13:00:00").getTime();
    const countdownTimer = setInterval(() => {
      const now = new Date().getTime();
      const distance = countDownDate - now;
      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);
      document.getElementById("days").innerHTML = String(days).padStart(2, '0');
      document.getElementById("hours").innerHTML = String(hours).padStart(2, '0');
      document.getElementById("minutes").innerHTML = String(minutes).padStart(2, '0');
      document.getElementById("seconds").innerHTML = String(seconds).padStart(2, '0');
      if (distance < 0) {
        clearInterval(countdownTimer);
        document.getElementById("countdown-container").style.display = "none";
        document.getElementById("title").style.display = "none";
        const eventStarted = document.createElement("div");
        eventStarted.classList.add("event-started");
        eventStarted.innerHTML = "O evento começou!";
        document.querySelector(".container").prepend(eventStarted);
      }
    }, 1000);
  </script>
</section>
