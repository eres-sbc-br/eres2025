# VIII Escola Regional de Engenharia de Software (ERES 2024)

Este repositório contém o código-fonte do site oficial da **VIII Escola Regional de Engenharia de Software (ERES 2024)**, desenvolvido com **Jekyll**, um gerador de sites estáticos. A ERES 2024 é promovida pela Sociedade Brasileira de Computação (SBC) e tem como objetivo disseminar boas práticas e conhecimento em Engenharia de Software, reunindo profissionais, acadêmicos e estudantes.

## Tecnologias Utilizadas

- **Jekyll**: Gerador de sites estáticos que transforma markdown e arquivos de template em sites HTML.
- **HTML/CSS**: Marcação e estilo das páginas.
- **JavaScript**: Scripts básicos, incluindo a contagem regressiva do evento.
- **Markdown**: Formatação e estruturação de conteúdo.

## Pré-requisitos

Para rodar este projeto localmente, você precisará de:

1. **Ruby**: Jekyll é uma gem do Ruby, então é necessário ter o Ruby instalado.
2. **Jekyll**: Instale o Jekyll e o Bundler com o comando:

    ```bash
    gem install jekyll bundler
    ```

## Instalação e Configuração

1. Clone o repositório:

    ```bash
    git clone https://github.com/eres-sbc-br/eres-2024.git
    cd eres-2024
    ```

2. Instale as dependências:

    ```bash
    bundle install
    ```

3. Rode o servidor localmente:

    ```bash
    bundle exec jekyll serve --config _config_dev.yml
    ```

4. Abra seu navegador e acesse `http://localhost:4000` para visualizar o site.

## Estrutura do Projeto

- **_config.yml**: Arquivo de configuração principal do Jekyll, onde estão definidas as configurações do site, como título, descrições e plugins.
- **_includes/**: Contém trechos de código reutilizáveis em várias páginas, como cabeçalhos e rodapés.
- **_layouts/**: Layouts de páginas, onde é definido o HTML comum a várias páginas.
- **_pages/**: Páginas principais do site, como Programação Geral, Minicursos, Fórum de Graduação, etc.

## Desenvolvimento

Para desenvolver novas funcionalidades ou fazer ajustes no design:

1. Siga os passos de instalação e configuração acima.
2. Realize as alterações desejadas nos arquivos de layout, includes, estilos ou scripts.
3. Utilize o comando `bundle exec jekyll serve` para verificar as alterações em tempo real.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests. 

1. Crie uma nova branch para sua funcionalidade:

    ```bash
    git checkout -b minha-nova-funcionalidade
    ```

2. Faça as alterações e os commits.
3. Abra um pull request para a branch principal.

## Licença

Este projeto é distribuído sob a licença MIT. 

---

Desenvolvido para a ERES 2024 pela comunidade acadêmica.
