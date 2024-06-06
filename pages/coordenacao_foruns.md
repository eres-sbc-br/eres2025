---
layout: page-fullwidth
title: "Coordenação dos Fóruns"
subheadline: ""
permalink: "/coordenacao_foruns/"
header:
  image_fullwidth: "ERES-2024_Logo.svg"
---

<style>
  header {
    margin-bottom: 30px;
  }

  h1, h2 {
    color: #333;
    text-align: center;
    margin: 20px 0;
  }

  h2 {
    font-size: 24px;
    padding-bottom: 10px;
    border-bottom: 1px solid #cbcbcb;
  }

  .section-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }

  .card {
    border-radius: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    width: calc(100% / 4 - 40px);
    margin: 10px;
    overflow: hidden;
    display: flex;
    padding: 10px;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .card img {
    width: 90%;
    height: 175px;
    object-fit: cover;
    border-radius: 50%;
    margin-top: 15px;
    box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
  }

  .card-text {
    margin: 15px 0 -20px 0;
    padding: 10px;
    width: 100%;
    box-sizing: border-box;
  }

  @media (max-width: 1024px) {
    .card {
      width: 30%;
    }

    .card img {
      height: 140px;
      width: 80%;
    }

    #img-andrea {
      width: auto;
    }

    #img-natasha {
      width: auto;
    }
  }

  @media (max-width: 768px) {
    .card {
      width: 50%;
    }

    .card img {
      height: 150px;
      width: 90%;
    }
  }

  @media (max-width: 600px) {
    .card {
      width: 100%;
    }

    .card img {
      height: 150px;
      width: 100%;
    }
  }
</style>

<main>
  <section aria-labelledby="coordenacao-graduacao-header">
    <h2 id="coordenacao-graduacao-header"><strong>Coordenação do Fórum de Graduação</strong></h2>
    <div class="section-container">
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/silvio.jpg" alt="Prof. Dr. Silvio Quincozes">
          <figcaption class="card-text">
            <strong>Prof. Dr. Silvio Quincozes</strong><br>
            Unipampa<br>
            <a href="http://lattes.cnpq.br/9401130360785458">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
    </div>
  </section>

  <section aria-labelledby="coordenacao-pos-graduacao-header">
    <h2 id="coordenacao-pos-graduacao-header"><strong>Coordenação do Fórum de Pós-Graduação</strong></h2>
    <div class="section-container">
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/natasha.jpg" id="img-natasha" alt="Prof. Dra. Natasha Malveira Costa Valentim">
          <figcaption class="card-text">
            <strong>Prof. Dra. Natasha Malveira Costa Valentim</strong><br>
            <a href="http://lattes.cnpq.br/1374747002879287">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
    </div>
  </section>

  <section aria-labelledby="coordenacao-extensao-header">
    <h2 id="coordenacao-extensao-header"><strong>Coordenação do Fórum de Extensão</strong></h2>
    <div class="section-container">
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/andrea.jpg" id="img-andrea" alt="Prof. Dra. Andréa Sabedra Bordin">
          <figcaption class="card-text">
            <strong>Prof. Dra. Andréa Sabedra Bordin</strong><br>
            UFSC<br>
            <a href="http://lattes.cnpq.br/3462254816005439">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
    </div>
  </section>
</main>
