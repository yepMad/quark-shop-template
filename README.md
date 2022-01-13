## Sobre o desafio

Esse desafio tem como objetivo enteder suas habilidades básicas com React Native e Typescript! Você utilizará ferramentas como rotas API e Context API.

### Template da aplicação
Para agilizar o início do projeto, você poderá utilizar esse git como template para iniciar sua aplicação.

#### O que é Git Template?
Git Template é uma forma de você dar um "fork", ou apenas copiar, um projeto do GitHub como base para implementar e fazer seus PRs por cima, sem haver necessidade de ficar vinculado ao projeto original. [Saibe o que é um Git Template](https://youtu.be/aYYNXK9tt8Y)

PS: Lembre-se de executar `yarn` ou `npm install` no seu terminal para instalar todos os node_modules.

### Utilizando uma fake API

Esse repositório não utiliza uma API real para listar os produtos e salvar os favoritos. Para isso, nós utilizamos o módulo "json-server". Você deve notar que existe um arquivo chamado `server.json` que já possui produtos e categorias listadas. Executando o comando `yarn start:server` você inicia a API na URL `localhost:3000`, e isso torna possível fazer métodos de GET, POST, PUT e DELETE para qualquer uma das rotas existentes, como se fosse uma aplicação real.

Rotas existentes:

- "/products"
- "/categories"
- "/favorites"

É altamente recomendável que você veja como funciona o [json-server](https://github.com/typicode/json-server) e como pode fazer requisições mais complexas.

### Layout da aplicação

Você deve seguir nosso layout do [Figma](https://www.figma.com/file/9bbq084YJeAYIAv56BtwYf/QuarkShop?node-id=0%3A1), feedbacks que não estiverem explícitos na plataforma você pode criar/elaborar por si mesmo.

### Funcionalidades da aplicação

- **`Listar os produtos`**: Sua `Página Principal` deve ser capaz de exibir uma listagem de todos os produtos. Deve ser possível filtrar por uma ou mais de uma categoria. Assim como deve ser possível filtrar por nenhuma.

- **`Adicionar itens ao carrinho`**: A aplicação deve permitir que o usuário adicione itens ao carrinho ao clicar no símbolo de "+" na listagem de produtos.

- **`Exibir itens do carrinho`**: Em `Carrinho` você deve exibir todos os itens do carrinho, junto com a quantidade, valor único, valor subtotal dos itens e total de todos os items.

- **`Aumentar quantidade de itens do carrinho`**: Em `Carrinho` você deve permitir que o usuário aumente a quantidade de itens do mesmo produto.

- **`Diminuir quantidade de um item do carrinho`**: Em `Carrinho` você deve permitir que o usuário decremente a quantidade de itens do mesmo produto.

- **`Exibir valor total dos itens no carrinho`**: Em `Carrinho` você deve exibir o valor e a quantidade total de todos os itens que estão no seu carrinho. Na barra de navegação inferior você deve exibir a quantidade total de itens no carrinho - caso passe de 9, você pode colocar "+9".

- **`Exibir e armazenar favoritos`**: Em `Favoritos` você deve exibir todos os itens que foram favoritados.
