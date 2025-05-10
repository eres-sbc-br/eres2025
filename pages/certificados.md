---
layout: page-fullwidth
permalink: /certificados/
title: "Certificado de Participação - ERES 2025"
header:
  image_fullwidth: "ERES-2025_Logo.svg"
---

<style>
  h1 {
    color: #333;
    text-align: center;
    font-size: 2em;
    margin-top: 20px;
  }

  .text {
    font-size: 1.1em;
    line-height: 1.6;
    color: #666;
    max-width: 700px;
    margin: 20px auto;
    text-align: center;
  }

  #search-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    max-width: 500px;
    margin: 30px auto;
    padding: 20px;
  }

  #nameInput {
    width: 100%;
    padding: 12px;
    font-size: 16px;
    margin-bottom: 30px;
    border: 1px solid #ddd;
    border-radius: 6px;
  }

  #searchButton {
    padding: 12px 25px;
    font-size: 16px;
    cursor: pointer;
    color: white;
    border: none;
    border-radius: 6px;
    transition: background-color 0.3s ease;
  }

  #results {
    width: 100%;
    max-width: 500px;
    margin: 20px auto;
    text-align: center;
  }

  .result-item {
    background-color: #ffffff;
    padding: 12px;
    margin: 8px 0;
    border: 1px solid #ddd;
    border-radius: 6px;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s, background-color 0.2s;
  }

  .result-item:hover {
    transform: scale(1.02);
    background-color: #f1f1f1;
  }

  .result-item a {
    color: #0066cc;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1em;
  }

  .result-item a:hover {
    text-decoration: underline;
  }
</style>

<p class="text">Insira seu nome completo no campo abaixo para pesquisar e acessar seu certificado de participação na ERES 2025. Clique no link do certificado para baixá-lo.</p>

<p class="text">Estão disponíveis os certificados de participação, apresentação de artigo e participação em mini cursos, até o momento.</p>

<div id="search-container">
    <input type="text" id="nameInput" placeholder="Digite seu nome" />
    <button id="searchButton">Buscar</button>
</div>

<div id="results"></div>

<script>
    let participants = [];

    async function loadParticipants() {
        try {
            const response = await fetch('{{ site.baseurl }}/certificados/participantes.txt');
            const data = await response.text();
            participants = data.split('\n').map(name => name.trim()).filter(name => name);
        } catch (error) {
            console.error('Erro ao carregar a lista de participantes:', error);
        }
    }

    function performSearch() {
        const nameInput = document.getElementById('nameInput').value.trim().toLowerCase();
        const resultsContainer = document.getElementById('results');
        resultsContainer.innerHTML = '';

        const results = participants.filter(participant => participant.toLowerCase().includes(nameInput));

        if (results.length === 0) {
            resultsContainer.innerHTML = '<p>Nenhum certificado encontrado para este nome.</p>';
        } else {
            results.forEach(participant => {
                const formattedName = participant.replace(/ /g, '_');
                const pdfFile = `${formattedName}.pdf`;
                const resultItem = document.createElement('div');
                resultItem.className = 'result-item';
                resultItem.innerHTML = `<a href="{{ site.baseurl }}/certificados/pdfs/${pdfFile}" target="_blank">${participant}</a>`;
                resultsContainer.appendChild(resultItem);
            });
        }
    }

    document.getElementById('searchButton').addEventListener('click', performSearch);

    document.getElementById('nameInput').addEventListener('keydown', (event) => {
        if (event.key === 'Enter') {
            performSearch();
        }
    });

    loadParticipants();
</script>
