---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: page-fullwidth
permalink: /index.html
homepage: true
header:
  image_fullwidth: Banner_principalERES2023.jpg
---

<center><div style="color:#000000; font-size: 85px; font-weight: normal" id="dday">teste</div></center>

<script> 

 
var countDownDate = new Date("December 6, 2023 08:00:00").getTime();

var x = setInterval(function() { // Get todays date and time 
	 var now = new Date().getTime();
	 var distance = countDownDate - now;
	 var days = Math.floor(distance / (1000 * 60 * 60 * 24)); 
	 var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
	 var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
	 var seconds = Math.floor((distance % (1000 * 60)) / 1000);

	 document.getElementById("dday").innerHTML = days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

	 if (distance < 0) {
		clearInterval(x); document.getElementById("dday").innerHTML = "SITE NA TEIA"; 
	 } 
	 
}, 1000);

</script>



<h1>Início</h1>

<p>A <b>Escola Regional de Engenharia de Software (ERES)</b> é promovida anualmente pela Sociedade Brasileira de Computação (SBC). A sétima edição da escola, a <b>ERES 2023</b>, ocorrerá <b>presencialmente</b>, no período de 06 a 08 de dezembro de 2023.</p>

Esta edição está sendo realizada pelo <a href="http://www.din.uem.br" target="_blank">Departamento de Informática (DIN)</a> da <a href="http://www.uem.br" target="_blank">Universidade Estadual de Maringá (UEM)</a>.

<p>A ERES tem por objetivo disseminar o conhecimento e boas práticas em Engenharia de Software (ES), do ponto de vista profissional e acadêmico. A ERES 2023 é um espaço regional para que possam ser apresentados os resultados de pesquisas e extensão em nível de graduação e pós-graduação e relatos de experiência na indústria. Além disso, possibilitará um ambiente natural para a discussão de abordagens no ensino-aprendizagem na ES.</p>

<p>A realização da ERES 2023 oferecerá aos seus participantes atualizações do estado-da-arte da pesquisa científica na área de engenharia de software por meio da apresentação de palestras ministradas por pesquisadores e praticantes da indústria renomados. Dessa forma, este evento irá possibilitar a promoção de conceitos atuais na área, além de divulgar o que se está pesquisando em engenharia de software na região sul, no país e no mundo, inspirando, assim, o gosto pela pesquisa científica aos participantes.</p>

<p>A programação da ERES 2023 está sendo elaborada com palestras, minicursos e submissões de artigos para serem apresentados em um Fórum de Graduação, um Fórum de Pós-Graduação e um Fórum de Extensão.</p>

<h3>Fórum de Graduação</h3>
<p>Espaço destinado para apresentação dos trabalhos de pesquisa ou relatos de experiência em Engenharia de Software, desenvolvidos por acadêmicos de graduação, principalmente das IES catarinenses, gaúchas e paranaenses. </p>

<h3> Fórum de Pós-Graduação</h3>
<p>Espaço para apresentação de trabalhos de estudantes de pós-graduação, com o objetivo de incentivar a troca de experiências e divulgar pesquisas em andamento e/ou concluídas e resultados obtidos. Além da clareza do trabalho, relevância do tema, e qualidade da apresentação, o Comitê Científico da ERES 2023 avaliará também as contribuições científicas do trabalho.</p>

<h3> Fórum de Extensão </h3>
<p>Espaço para apresentação de trabalhos de relatos das atividades extensionistas aplicados aos currículos de computação, especialmente da Engenharia de Software, e de que forma estão implantando a inserção da extensão em seus currículos conforme previsto na Resolução CNE/CES nº 7, de 18 de dezembro de 2018. O objetivo é incentivar a troca de experiências entre docentes coordenadores de programas e projetos de extensão.
 </p>



<!--
widget1:
  title: "Blog & Portfolio"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'Every good portfolio website has a blog with fresh news, thoughts and develop&shy;ments of your activities. <em>Feeling Responsive</em> offers you a fully functional blog with an archive page to give readers a quick overview of all your posts.'

widget2:
  title: "Why use this theme?"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: '<em>Feeling Responsive</em> is heavily customizable.<br/>1. Language-Support :)<br/>2. Optimized for speed and it&#39;s responsive.<br/>3. Built on <a href="http://foundation.zurb.com/">Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,...'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'




#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
-->
