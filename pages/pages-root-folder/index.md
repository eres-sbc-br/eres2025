---
layout: page-fullwidth
permalink: /index.html
homepage: true
header:
  image_fullwidth: ERES-2024_Logo.png
---

<div id="countdown-container" style="text-align: center;">
  <h1 style="color: #333; font-size: 24px; font-weight: bold;">Contagem Regressiva para o Evento:</h1>
  <div id="countdown" style="color: #000000; font-size: 48px; font-weight: normal;">Carregando...</div>
</div>

<script>
  const countDownDate = new Date("November 11, 2024 00:00:00").getTime();

  const countdownTimer = setInterval(() => {
      const now = new Date().getTime();
      const distance = countDownDate - now;

      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      document.getElementById("countdown").innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;

      if (distance < 0) {
          clearInterval(countdownTimer);
          document.getElementById("countdown").innerHTML = "O evento começou!";
      }
  }, 1000);
</script>

<h1>Início</h1>

<p>A <b>Escola Regional de Engenharia de Software (ERES)</b> é promovida anualmente pela Sociedade Brasileira de Computação (SBC). A sétima edição da escola, a <b>ERES 2024</b>, ocorrerá <b>presencialmente</b>, no período de 06 a 08 de dezembro de 2024.</p>

Esta edição está sendo realizada pelo <a href="http://www.din.uem.br" target="_blank">Departamento de Informática (DIN)</a> da <a href="http://www.uem.br" target="_blank">Universidade Estadual de Maringá (UEM)</a>.

<p>A ERES tem por objetivo disseminar o conhecimento e boas práticas em Engenharia de Software (ES), do ponto de vista profissional e acadêmico. A ERES 2024 é um espaço regional para que possam ser apresentados os resultados de pesquisas e extensão em nível de graduação e pós-graduação e relatos de experiência na indústria. Além disso, possibilitará um ambiente natural para a discussão de abordagens no ensino-aprendizagem na ES.</p>

<p>A realização da ERES 2024 oferecerá aos seus participantes atualizações do estado-da-arte da pesquisa científica na área de engenharia de software por meio da apresentação de palestras ministradas por pesquisadores e praticantes da indústria renomados. Dessa forma, este evento irá possibilitar a promoção de conceitos atuais na área, além de divulgar o que se está pesquisando em engenharia de software na região sul, no país e no mundo, inspirando, assim, o gosto pela pesquisa científica aos participantes.</p>

<p>A programação da ERES 2024 está sendo elaborada com palestras, minicursos e submissões de artigos para serem apresentados em um Fórum de Graduação, um Fórum de Pós-Graduação e um Fórum de Extensão.</p>

<h3>Fórum de Graduação</h3>
<p>Espaço destinado para apresentação dos trabalhos de pesquisa ou relatos de experiência em Engenharia de Software, desenvolvidos por acadêmicos de graduação, principalmente das IES catarinenses, gaúchas e paranaenses. </p>

<h3> Fórum de Pós-Graduação</h3>
<p>Espaço para apresentação de trabalhos de estudantes de pós-graduação, com o objetivo de incentivar a troca de experiências e divulgar pesquisas em andamento e/ou concluídas e resultados obtidos. Além da clareza do trabalho, relevância do tema, e qualidade da apresentação, o Comitê Científico da ERES 2024 avaliará também as contribuições científicas do trabalho.</p>

<h3> Fórum de Extensão </h3>
<p>Espaço para apresentação de trabalhos de relatos das atividades extensionistas aplicados aos currículos de computação, especialmente da Engenharia de Software, e de que forma estão implantando a inserção da extensão em seus currículos conforme previsto na Resolução CNE/CES nº 7, de 18 de dezembro de 2018. O objetivo é incentivar a troca de experiências entre docentes coordenadores de programas e projetos de extensão.
 </p>
