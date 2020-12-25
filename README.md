# restaurantDIOsearch 🍖

Projeto de criação de um site para encontrar restaurantes usando Google Maps que consulta API do Google pra aula final de Reach da [DIO](https://web.digitalinnovation.one/home), ministrada pelo [Patrick Narciso](https://github.com/patrick-narciso/restaurants-search).

O projeto já está [online](https://restaurantesdiosearch.netlify.app/), com a ajuda do netlify, foi criado com [Yarn](https://yarnpkg.com/), então `yarn start` pra iniciar o ambiente de desenvolvimento.

---

Eu não consegui validar minha chave, o google exigia um cartão de crédito, mas até onde eu pude testar, só o que falta no projeto é uma APIKey válida do [Places](https://developers.google.com/maps/gmp-get-started).

Essa chave deve ficar em um arquivo com o nome de `.env` na raiz do projeto, com a seguinte estrutura: `REACT_APP_GOOGLE_API_KEY=chave_valida`.