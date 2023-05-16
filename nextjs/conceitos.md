## NextJS

- Uma framework que utiliza React que traz dentre suas principais funcionalidades o SSR(Server Side Rendering) e o SSG(Static Side Generating)
- Problema principal das SPA`s Indexação no google.

### Conceitos

- `SSR(Server Side Rendering)`, uma terceira camada entre o frontend e o backend. Essa camada é basicamente um midleware responsavel por fazer chamadas para o backend e montar o html da página e devolver para o backend.

Nossa aplicação não vai mais carregar o código javascript para depois fazer requisições, ela aguarda os dados do servidor para então mostrar em tela.
E se você desligar o javascript, ainda sim terá o html.

- `SSG(Static Side Generating)`, Genração de páginas estaticas.
  É possivel deixar uma página estatica em cache por determinado tempo, dentro desse tempo todos que acessarem terão esse HTML estatico, ou seja não vai precisar carregar a página do zero. Geralmente a primeira vez que abre a página demora mais que as seguintes. Isso ajuda a evitar chamar o nosso servidor de forma desnecessária
