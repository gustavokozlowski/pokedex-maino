# poke-app

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

O app deverá ser dotado das seguintes funcionalidades:

Listagem dos Pokémon com scroll infinito, contendo filtros para nome, id, tipo e espécie;
O app deve contar com suporte aos idiomas português, inglês e espanhol, disponíveis na API;
Abrir um card do Pokémon na listagem;

No card: 

Todos os sprites do Pokémon; 
Seus movimentos de ataque;
Visualizar às evoluções de cada Pokémon, se houver;
Visualizar todos os games (game_indices) que aquele Pokémon está presente.

Você poderá usar quaisquer bibliotecas que desejar para acelerar o seu desenvolvimento.

Opcionais: 

Se conseguir, escreva testes automatizados simples;
Se conseguir, implemente internacionalização;
Se conseguir, utilize VueX para gerenciamento de estado;
Se conseguir, torne a aplicação responsiva.

Quanto a infraestrutura, a sua aplicação deve estar publicada no Vercel (https://vercel.com/) e seu código deve estar acessível em sua conta do Github. 
Não iremos considerar a entrega de uma aplicação que não esteja publicada e de um código que não esteja no Github, de modo que possamos avaliar a evolução do seu código, ou seja, não aceitaremos a entrega funcionando apenas em Localhost. 

Caso não esteja habituado com o Vercel, você pode recorrer a seguinte documentação: https://vercel.com/guides/deploying-vuejs-to-vercel 

Quanto aos critério de avaliação, você será avaliado por uma banca de 3 pessoas, que poderão votar de 1 a 5 nos seguintes critérios: Boas práticas: qualidade de código, legibilidade, aplicação de patterns, dentre outros;