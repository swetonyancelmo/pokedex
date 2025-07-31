# Pokedex 

A **Pokedex** é uma aplicação web que exibe detalhes dos Pokémon usando a [PokeAPI](https://pokeapi.co/). O projeto foi desenvolvido com uma abordagem *mobile-first* e utiliza tecnologias modernas do desenvolvimento web. Projeto realizado para estudos.

## Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página.
- **CSS3:** Estilização e layout responsivo, utilizando técnicas *mobile-first*, com media queries definidas em [assets/css/pokedex.css](assets/css/pokedex.css) e [assets/css/global.css](assets/css/global.css).
- **JavaScript (ES6+):**
  - Uso de **Classes**, como em [`Pokemon`](assets/js/pokemon-model.js), para modelar os dados dos Pokémon.
  - Utilização da **Fetch API** e **Promises** para realizar requisições assíncronas à API, conforme implementado em [`pokeApi.getPokemons`](assets/js/poke-api.js).
  - Funções *arrow* para uma sintaxe concisa e manipulação dinâmica do DOM, evidenciada em [assets/js/main.js](assets/js/main.js).

## Conceitos de JavaScript Aplicados

- **Promises:** Para gerenciar operações assíncronas de forma não bloqueante.
- **Fetch API:** Para recuperar dados da [PokeAPI](https://pokeapi.co/), permitindo a atualização dinâmica do conteúdo.
- **Arrow Functions:** Para escrita de funções de maneira mais simples e legível.
- **Manipulação do DOM:** Atualização do conteúdo da página (por exemplo, renderização dinâmica dos Pokémon e gerenciamento do botão de "Load More").
- **Mobile First:** O desenvolvimento teve início pela abordagem *mobile-first*, garantindo uma ótima experiência em dispositivos móveis. Posteriormente, foram adicionados breakpoints para ajustar o layout em dispositivos maiores (como tablets e desktops), conforme especificado nos media queries em [assets/css/pokedex.css](assets/css/pokedex.css).

## Como Executar

1. Clone o repositório.
2. Abra o arquivo `index.html` em seu navegador.
3. Utilize o botão "Load More" para carregar mais Pokémon.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir *issues* e enviar *pull requests* com melhorias ou correções.

## Licença

Este projeto é open-source e pode ser utilizado livremente.
