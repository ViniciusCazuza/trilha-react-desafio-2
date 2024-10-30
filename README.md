
# Projeto de Busca de Repositórios do GitHub

Este projeto é uma aplicação em React que permite buscar repositórios no GitHub pelo nome do repositório completo, exibir as informações básicas de cada repositório encontrado e removê-los da lista. Utiliza a API pública do GitHub para buscar e exibir os dados.

## Funcionalidades

- **Busca de repositórios**: Pesquisa repositórios no GitHub pelo nome completo do repositório.
- **Listagem de repositórios**: Exibe o nome, nome completo e um link para o repositório.
- **Remoção de repositório**: Permite remover um repositório da lista exibida.

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção da interface.
- **Styled-components**: Biblioteca para estilização de componentes.
- **Axios**: Cliente HTTP para requisições à API do GitHub.
- **API GitHub**: Utilizada para buscar dados dos repositórios.

## Estrutura do Projeto

- `src/index.js`: Ponto de entrada da aplicação, onde o componente principal `App` é renderizado.
- `src/styles.js`: Configuração global de estilos utilizando `styled-components`.
- `src/pages/App.js`: Componente principal da aplicação, que controla o estado dos repositórios e as funções de busca e remoção.
- `src/services/api.js`: Configuração do cliente `axios` para a API do GitHub.
- `src/components/`: Contém os componentes reutilizáveis da aplicação:
  - **Button**: Botão de busca de repositório.
  - **Input**: Campo de entrada de texto para buscar o repositório.
  - **ItemRepo**: Exibe as informações do repositório e possui a opção de remoção.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone <URL-do-repositório>
   ```

2. **Instale as dependências**:
   ```bash
   npm install
   ```

3. **Inicie o projeto**:
   ```bash
   npm start
   ```

   A aplicação estará disponível em [http://localhost:3000](http://localhost:3000).

## Estrutura de Código

### `src/pages/App.js`
Este é o componente principal da aplicação que:
- Controla o estado dos repositórios através de `useState`.
- Contém a lógica para buscar e adicionar repositórios através da função `handleSearchRepo`.
- Permite remover repositórios com `handleRemoveRepo`.

### `src/services/api.js`
Configura o cliente `axios` com a URL base da API do GitHub.

### `src/components/ItemRepo`
Exibe informações do repositório e contém o botão de remoção.

## Exemplo de Uso

1. Digite o nome completo do repositório no campo de busca (por exemplo, `facebook/react`).
2. Clique em **Buscar** para ver o repositório na lista.
3. Clique em **Remover** para excluir o repositório da lista.

## Estilização

A estilização é feita com `styled-components`, permitindo um escopo de estilos isolado por componente.

## Créditos

Este projeto foi construído para fins de aprendizado para o Bootcamp da DIO e XP Inc. e utiliza a [API pública do GitHub](https://api.github.com).

---

**Observação**: Certifique-se de não exceder os limites de requisição da API do GitHub para evitar bloqueios temporários.


##

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
