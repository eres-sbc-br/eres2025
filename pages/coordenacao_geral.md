---
layout: page-fullwidth
title: "Coordenação Geral"
subheadline: ""
permalink: "/coordenacao_geral/"
header:
  image_fullwidth: "ERES-2025_Logo.svg"
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
      width: 40%;
    }

    .card img {
			margin-top: 15px;
      height: 140px;
			width: 60%;
    }

		#img-carla {
			width: 50%;
		}
  }

  @media (max-width: 768px) {
    .card {
      width: 50%;  
    }

    .card img {
      height: 150px;
			width: 70%;
    }

		#img-carla {
			width: 55%;
		}
  }

  @media (max-width: 600px) {
    .card {
      width: 70%;
    }

    .card img {
      height: 150px;
			width: 70%;
    }

		#img-carla {
			width: auto;
		}
  }
</style>

<main>
  <section aria-labelledby="coordenacao-geral-header">
    <h2 id="coordenacao-geral-header"><strong>Coordenadores Gerais</strong></h2>
    <div class="section-container">
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/prof_anderson.jpg" alt="Prof. Mr. Anderson de Paula Fortes">
          <figcaption class="card-text">
            <strong>Prof. Me. Anderson de Paula Fortes</strong><br>
            URI Santiago<br>
            <a href="http://lattes.cnpq.br/8500919840176084" target="_blank">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/maicon.jpg" alt="Prof. Dr. Maicon Bernardino da Silveira">
          <figcaption class="card-text">
            <strong>Prof. Dr. Maicon Bernardino da Silveira</strong><br>
            Unipampa<br>
            <a href="http://lattes.cnpq.br/0523166822363498" target="_blank">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
    </div>
  </section>

  <section aria-labelledby="organizacao-local-header">
    <h2 id="organizacao-local-header"><strong>Organização Local</strong></h2>
    <div class="section-container">
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/prof_carla.jpg" id="img-carla" alt="Profa. Me. Carla Lisiane de Oiliveira Castanho">
          <figcaption class="card-text">
            <strong>Profa. Me. Carla Lisiane de Oliveira Castanho</strong><br>
            URI Santiago<br>
            <a href="http://lattes.cnpq.br/2572817294743935" target="_blank">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/prof_lu.jpg" alt="Profa. Me. Luciane Machado Fraga">
          <figcaption class="card-text">
            <strong>Profa. Me. Luciane Machado Fraga</strong><br>
            URI Santiago<br>
            <a href="http://lattes.cnpq.br/0576253490550915" target="_blank">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/prof_gustavo.jpg" alt="Prof. Gustavo Girardon dos Reis">
          <figcaption class="card-text">
            <strong>Prof. Esp. Gustavo Girardon dos Reis</strong><br>
            URI Santiago<br>
            <a href="http://lattes.cnpq.br/9724726861595610" target="_blank">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
      <article class="card">
        <figure>
          <img src="{{ site.urlimg }}/prof_leonardo.jpg" alt="Prof. Me. Leonardo Lima Carvalho">
          <figcaption class="card-text">
            <strong>Prof. Me. Leonardo Lima Carvalho</strong><br>
            URI Santiago<br>
            <a href="http://lattes.cnpq.br/4149281529137286" target="_blank">Currículo Lattes</a>
          </figcaption>
        </figure>
      </article>
    </div>
  </section>
</main>
