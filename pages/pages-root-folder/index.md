---
layout: page-fullwidth
permalink: /index.html
homepage: true
header:
  image_fullwidth: ERES-2024_Logo.png
---

<style>
  #countdown-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }

  .countdown-unit {
    margin: 10px;
    text-align: center;
    background-color: #f9f9f9;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
    padding: 10px;
    flex: 1;
    min-width: 120px;
  }

  .countdown-unit span {
    display: block;
    font-size: 2em;
    font-weight: bold;
  }

  .unit-label {
    font-size: 0.8em;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: #555;
  }

  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-top: -30px;

  }

  #countdown-title {
    font-size: 1.5em;
    margin-bottom: 20px;
  }

  @media (max-width: 768px) { 
    .countdown-unit {
      flex: 1 1 25%;
    }
  }
</style>

<section class="container">
  <h1 id="countdown-title">Contagem regressiva para o início da ERES 2024</h1>
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

  <div>
    <h1>Início</h1>

    <p>A <b>Escola Regional de Engenharia de Software (ERES)</b> é promovida anualmente pela Sociedade Brasileira de Computação (SBC). A oitava edição da escola, a <b>ERES 2024</b>, ocorrerá <b>presencialmente</b>, no período de 11 a 13 de novembro de 2024.</p>

    Esta edição está sendo realizada pelo <a href="http://www1.urisantiago.br/ciencia-da-computacao" target="_blank">Curso de Ciência da Computação</a> da <a href="http://www1.urisantiago.br/" target="_blank">Universidade Regional Integrada e das Missões (URI) - Campus Santiago</a>.

    <p>A ERES tem por objetivo disseminar o conhecimento e boas práticas em Engenharia de Software (ES), do ponto de vista profissional e acadêmico. A ERES 2024 é um espaço regional para que possam ser apresentados os resultados de pesquisas e extensão em nível de graduação e pós-graduação e relatos de experiência na indústria. Além disso, possibilitará um ambiente natural para a discussão de abordagens no ensino-aprendizagem na ES.</p>

    <p>A realização da ERES 2024 oferecerá aos seus participantes atualizações do estado-da-arte da pesquisa científica na área de engenharia de software por meio da apresentação de palestras ministradas por pesquisadores e praticantes da indústria renomados. Dessa forma, este evento irá possibilitar a promoção de conceitos atuais na área, além de divulgar o que se está pesquisando em engenharia de software na região sul, no país e no mundo, inspirando, assim, o gosto pela pesquisa científica aos participantes.</p>

    <p>A programação da ERES 2024 está sendo elaborada com palestras, minicursos e submissões de artigos para serem apresentados em um Fórum de Graduação, um Fórum de Pós-Graduação e um Fórum de Extensão.</p>

    <h3>Fórum de Graduação</h3>
    <p>Espaço destinado para apresentação dos trabalhos de pesquisa ou relatos de experiência em Engenharia de Software, desenvolvidos por acadêmicos de graduação, principalmente das IES catarinenses, gaúchas e paranaenses.</p>

    <h3> Fórum de Pós-Graduação</h3>
    <p>Espaço para apresentação de trabalhos de estudantes de pós-graduação, com o objetivo de incentivar a troca de experiências e divulgar pesquisas em andamento e/ou concluídas e resultados obtidos. Além da clareza do trabalho, relevância do tema, e qualidade da apresentação, o Comitê Científico da ERES 2024 avaliará também as contribuições científicas do trabalho.</p>

    <h3> Fórum de Extensão </h3>
    <p>Espaço para apresentação de trabalhos de relatos das atividades extensionistas aplicados aos currículos de computação, especialmente da Engenharia de Software, e de que forma estão implantando a inserção da extensão em seus currículos conforme previsto na Resolução CNE/CES nº 7, de 18 de dezembro de 2018. O objetivo é incentivar a troca de experiências entre docentes coordenadores de programas e projetos de extensão.
    </p>

  </div>
</section>

<script>
  const countDownDate = new Date("November 11, 2024 00:00:00").getTime();

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
      document.getElementById("countdown-container").innerHTML = "<h1>O evento começou!</h1>";
    }
  }, 1000);
</script>
