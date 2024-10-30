---
layout: page-fullwidth
title: "Minicursos"
subheadline: ""
permalink: "/programacao/minicursos/"
header:
  image_fullwidth: ERES-2024_Logo.svg
---

<style>
  .minicurso {
    margin-bottom: 40px;
  }

  .minicurso-content {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
  }

  .minicurso img {
    max-width: 200px;
    height: auto;
    margin-right: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  .minicurso h2 {
    margin-top: 0;
  }

  .minicurso p {
    text-align: justify;
    color: #666;
    line-height: 1.6;
  }

  .instrutor {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
  }

  .instrutor img {
    max-width: 150px;
    height: auto;
    margin-right: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  .instrutor-content {
    flex: 1;
  }

  .instrutor h3 {
    margin-top: 0;
  }

  .instrutor p {
    text-align: justify;
    color: #666;
    line-height: 1.6;
  }

  .instrutor-h3 {
    margin-bottom: 0.5rem;
  }

  hr.divisor {
    border: none;
    border-top: 1px solid #d3d3d3;
    margin: 40px 0;
  }

  @media (max-width: 768px) {
    .minicurso-content,
    .instrutor {
      flex-direction: column;
      align-items: center;
    }

    .minicurso img,
    .instrutor img {
      margin-right: 0;
      margin-bottom: 20px;
      max-width: 100%;
    }
  }
</style>

<div id="minicurso1" class="minicurso">
  <div class="minicurso-content">
    <div>
      <h2 class="minicurso-title">Introdução à Detecção de Intrusões com Machine Learning: Protegendo Redes com Inteligência Artificial Explicável</h2>
      <p class="minicurso-resumo">
        <strong>Resumo:</strong> Este minicurso aborda como a utilização de Machine Learning (ML) pode revolucionar a detecção de intrusões, tornando os sistemas de segurança cibernética mais robustos e eficientes na identificação de ataques sofisticados. 
        Demonstraremos como algoritmos de ML, como o XGBoost, podem ser usados para classificar comportamentos como benignos ou intrusões em uma rede. 
        Além disso, será explorado como a Inteligência Artificial Explicável (XAI), com ênfase no uso de ferramentas como SHAP, pode aumentar a transparência e confiança nos modelos de detecção. 
        Com atividades práticas, os participantes aprenderão a implementar pipelines de segurança cibernética utilizando ML, desde a preparação dos dados até a análise explicativa de ataques.
      </p>
    </div>
  </div>

  <h3 class="instrutor-h3">Instrutores:</h3>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/01/Felipe Scherer.jpg" alt="Felipe H. Scherer">
    <div class="instrutor-content">
      <h3>Felipe H. Scherer</h3>
      <a href="http://lattes.cnpq.br/0515811498958707" target="_blank">Currículo Lattes</a><br><br>
      <p>
        Felipe é estudante de Engenharia de Software na Universidade Federal do Pampa, onde é membro do Laboratório de Estudos Avançados em Computação (LEA) e atua como bolsista no projeto "XAIID - Estratégias Inteligentes e Explicáveis para Detecção de Intrusões em Sistemas Ciber-Físicos". Neste projeto, dedica-se ao estudo de soluções de segurança cibernética baseadas em aprendizado de máquina e inteligência artificial explicável (XAI) com foco na detecção de intrusões em sistemas ciber-físicos. Sua experiência inclui pesquisas sobre a aplicação de XAI em redes intraveiculares, destacando-se em eventos acadêmicos e profissionais. Felipe também foi reconhecido com o prêmio de "Ferramenta Destaque" no maior evento de segurança do país, demonstrando sua relevância na área. Integra o projeto "Codefolio - Construindo Portfólios de Código & Compartilhando Conhecimento de Boas Práticas de Engenharia de Software", onde colabora no desenvolvimento de minicursos e materiais educativos voltados para a computação.
      </p>
    </div>
  </div>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/01/Felipe Dresh.jpg" alt="Felipe N. Dresch">
    <div class="instrutor-content">
      <h3>Felipe N. Dresch</h3>
      <a href="http://lattes.cnpq.br/7173376071216478" target="_blank">Currículo Lattes</a><br><br>
      <p>
        Felipe é Técnico em Informática pelo Instituto Federal do Rio Grande do Sul e integrante do Laboratório de Estudos Avançados em Computação (LEA) na Universidade Federal do Pampa, onde cursa Engenharia de Software. Ele também faz parte do projeto XAIID - Estratégias Inteligentes e Explicáveis para Detecção de Intrusões em Sistemas Ciber-Físicos, que desenvolve soluções de Inteligência Artificial Explicável (XAI) para a detecção de intrusões em sistemas digitais. Felipe participa ativamente de projetos de pesquisa e extensão, tendo artigos publicados que foram reconhecidos por suas contribuições inovadoras à aplicação de IA em cibersegurança. Trabalhando de maneira prática com Python e machine learning, Felipe alia seu conhecimento acadêmico à experiência prática no desenvolvimento de sistemas de detecção de intrusão com o foco em criar soluções robustas para desafios de segurança digital.
      </p>
    </div>
  </div>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/01/Matheus.jpg" alt="Matheus M. Ciocca">
    <div class="instrutor-content">
      <h3>Matheus M. Ciocca</h3>
      <a href="http://lattes.cnpq.br/1560440227615511" target="_blank">Currículo Lattes</a><br><br>
      <p>
        Técnico em Informática pelo Instituto Federal Farroupilha e integrante do Laboratório de Estudos Avançados em Computação (LEA) na Universidade Federal do Pampa, onde cursa Engenharia de Software. Matheus também é bolsista no projeto “Codefolio - Construindo Portfólios de Código & Compartilhando Conhecimento de Boas Práticas de Engenharia de Software”, onde atua no desenvolvimento da Plataforma Web Codefólio, à gravação de vídeos que disseminam o conhecimento em boas práticas da Engenharia de Software, bem como em organização de minicursos nesta área.
      </p>
    </div>
  </div>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/01/Estefano.jpg" alt="Estefano Ströher Soares">
    <div class="instrutor-content">
      <h3>Estefano Ströher Soares</h3>
      <p>
        Estefano é estudante de Ciência da Computação na Universidade Federal do Pampa e integrante do LESSE – Laboratório de Estudos Empíricos em Engenharia de Software. Participa do projeto de extensão “Codefolio - Construindo Portfólios de Código & Compartilhando Conhecimento de Boas Práticas de Engenharia de Software” como voluntário e é bolsista no “Projeto e Avaliação de Tecnologias para Apoiar o Desenvolvimento de Aplicações Interativas sob a Perspectiva da Qualidade de Uso”.
      </p>
    </div>
  </div>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/01/Camilla.jpg" alt="Camilla Borchhardt">
    <div class="instrutor-content">
      <h3>Camilla Borchhardt</h3>
      <a href="http://lattes.cnpq.br/5363434164195356" target="_blank">Currículo Lattes</a><br><br>
      <p>
        Camilla é estudante de Engenharia de Software e integrante do Laboratório de Estudos Avançados em Computação (LEA) na sua universidade. Ela é bolsista de ensino no projeto Egress@s pela FAPERGS, além de trabalhar em iniciativas de extensão e pesquisa como o Codefólio e o Gurias na Computação. Camilla participa ativamente desses projetos, combinando sua formação acadêmica com a prática em desenvolvimento de software, buscando contribuir para a inclusão e avanço de mulheres na tecnologia, bem como no desenvolvimento de soluções inovadoras na área da engenharia de software.
      </p>
    </div>
  </div>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/01/Silvio.jpg" alt="Silvio E. Quincozes">
    <div class="instrutor-content">
      <h3>Silvio E. Quincozes</h3>
      <a href="http://lattes.cnpq.br/9401130360785458" target="_blank">Currículo Lattes</a><br><br>
      <p>
        Professor Silvio Quincozes é Doutor em Computação pela UFF (sanduíche na University of Pittsburgh - EUA), mestre em Ciência da Computação pela UFSM e bacharel em Engenharia de Software pela UNIPAMPA. Atuou como docente no IFRS, UFU e atualmente na UNIPAMPA. É docente nos programas de pós-graduação PPGES/UNIPAMPA e PPGCO/UFU. Coordena os projetos XAIID (com ênfase em aplicações de Inteligência Artificial Explicável em Detecção de Intrusões) e Codefólio (com ênfase em atividades como produção de minicursos, portfólios de código e material audiovisual sobre computação), entre outros projetos.
      </p>
    </div>
  </div>

</div>

<hr class="divisor">

<div id="minicurso2" class="minicurso">
  <div class="minicurso-content">
    <div>
      <h2 class="minicurso-title">Risco em Jogo – Aprendendo Gerenciamento de Riscos de Forma Divertida</h2>
      <p class="minicurso-resumo">
        <strong>Resumo:</strong> No minicurso "Risco em Jogo – Aprendendo Gerenciamento de Riscos de Forma Divertida", os participantes irão explorar os principais conceitos de gerenciamento de riscos de forma interativa e prática. A primeira parte do curso abordará os fundamentos teóricos, como identificação, análise e gerenciamento de riscos em projetos de software. Na sequência, os alunos aplicarão esse conhecimento por meio de um jogo de tabuleiro desenvolvido para simular situações reais de gerenciamento de riscos. Ao final, os participantes estarão mais preparados para lidar com riscos de maneira estratégica e eficaz, de forma lúdica e envolvente.
      </p>
    </div>
  </div>

  <h3 class="instrutor-h3">Instrutora:</h3>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/palestras/Dr. Lisandra Manzoni Fontoura.jpg" alt="Dra. Lisandra Manzoni Fontoura">
    <div class="instrutor-content">
      <h3>Dra. Lisandra Manzoni Fontoura</h3>
      <a href="http://lattes.cnpq.br/8979575031016933" target="_blank">Currículo Lattes</a><br>
      <p>
        Doutora em Ciência da Computação e mestre em Computação, ambos pela Universidade Federal do Rio Grande do Sul; graduação em Informática pela Universidade Federal de Santa Maria (1997). Atua como professora e pesquisadora na Universidade Federal de Santa Maria e como professor permanente do Programa de Pós-Graduação em Ciência da Computação. Trabalhou como analista de sistemas e como membro do Grupo de Qualidade de Software no Serviço Federal de Processamento de Dados. Tem experiência na área de Ciência da Computação, com ênfase em Engenharia de Software, principalmente nos seguintes temas: Processos de Software, Gerência de Projetos, Segurança da Informação e Qualidade de Software. Atuou como coordenadora geral do projeto Sistema Integrado de Simulação ASTROS (SIS-ASTROS) e atua como coordenadora técnica do projeto Sistema Integrado de Simulação ASTROS – Grupo de Mísseis e Foguetes (SIS-ASTROS GMF), ambos desenvolvidos em parceria da UFSM com o Exército Brasileiro.
      </p>
    </div>
  </div>
</div>

<hr class="divisor">

<div id="minicurso3" class="minicurso">
  <div class="minicurso-content">
    <div>
      <h2 class="minicurso-title">Filament PHP: Acelerando o Desenvolvimento com Laravel</h2>
      <p class="minicurso-resumo">
        <strong>Resumo:</strong> Neste minicurso, criaremos uma aplicação do zero, totalmente funcional, desde a criação do banco de dados, back-end e front-end. A aplicação conterá painel administrativo com controle de acesso, formulários, gráficos e relatórios. Tudo isso de forma escalável, seguindo boas práticas de programação e utilizando componentes dinâmicos e customizáveis. Serão usadas as seguintes tecnologias: Laravel framework, Livewire, Filament, MariaDB.
      </p>
    </div>
  </div>

  <h3 class="instrutor-h3">Instrutor:</h3>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/06/Guilherme Legramante Martins.jpg" alt="Guilherme Legramante Martins">
    <div class="instrutor-content">
      <h3>Guilherme Legramante Martins</h3>
      <a href="http://lattes.cnpq.br/2573243978920771" target="_blank">Currículo Lattes</a><br>
      <p>
        Possui graduação e mestrado em Engenharia de Software pela UNIPAMPA. Atua desde 2019 como Desenvolvedor Full Stack, criando soluções para a área de gestão pública. CTO do Marca & Sinal, ferramenta pioneira para combate ao abigeato com inteligência artificial.
      </p>
    </div>
  </div>
</div>

<hr class="divisor">

<div id="minicurso4" class="minicurso">
  <div class="minicurso-content">
    <div>
      <h2 class="minicurso-title">Desenvolvimento de dApps com Ethereum e Smart Contracts</h2>
      <p class="minicurso-resumo">
        <strong>Resumo:</strong> Aplicações descentralizadas, ou dApps, são aplicativos que operam em redes blockchain, como a Ethereum, em vez de servidores centralizados. Este curso é para você, profissional e entusiasta de tecnologia que tem conhecimento básico de programação (preferencialmente JavaScript) e deseja aprofundar seus conhecimentos em blockchain e aprender a desenvolver aplicações descentralizadas (dApps). Nele, abordaremos blockchain e Ethereum, smart contracts e as principais ferramentas e frameworks para desenvolvimento e teste de dApps.
      </p>
    </div>
  </div>

  <h3 class="instrutor-h3">Instrutor:</h3>

  <div class="instrutor">
    <img src="{{ site.urlimg }}/palestras/Dr. Elvys Soares.jpg" alt="Elvys Soares">
    <div class="instrutor-content">
      <h3>Elvys Soares</h3>
      <a href="http://lattes.cnpq.br/6415531537733982" target="_blank">Currículo Lattes</a><br><br>
      <p>
        Professor Elvys Soares é docente no Instituto Federal de Alagoas (IFAL) e possui vasta experiência em desenvolvimento de software e segurança da informação. Com uma forte base em testes de software e pesquisa em "test smells," Elvys amplia seus conhecimentos na área de blockchain e aplicações descentralizadas, explorando soluções inovadoras para o futuro da tecnologia digital.
      </p>
    </div>
  </div>
</div>
