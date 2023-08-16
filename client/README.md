## Frontend (Client)

Bem-vindo à documentação do frontend (client) do projeto Capputeeno! Aqui, você encontrará informações detalhadas sobre como iniciar e executar o frontend do projeto em sua máquina local.

### Pré-requisitos

Antes de começar, certifique-se de ter os seguintes softwares instalados em seu sistema:

- [Node.js](https://nodejs.org/) (versão recomendada: 16.x ou superior)
- [npm](https://www.npmjs.com/) (vem com o Node.js) ou [Yarn](https://yarnpkg.com/) (recomendado)

### Instalação das Dependências

1. Navegue até o diretório do cliente:

   ```bash
   cd client
   ```

2. Instale as dependências do cliente usando o npm:

   ```bash
   npm install
   ```

   Ou usando o Yarn:

   ```bash
   yarn
   ```

### Scripts Disponíveis

No diretório do cliente, você pode executar os seguintes scripts para gerenciar o desenvolvimento e a construção do projeto:

- `dev`: Inicia o servidor de desenvolvimento.

   ```bash
   npm run dev
   ```

   Ou com o Yarn:

   ```bash
   yarn dev
   ```

   Isso inicia o servidor de desenvolvimento em [http://localhost:3000](http://localhost:3000).

- `build`: Constrói o aplicativo pronto para produção.

   ```bash
   npm run build
   ```

   Ou com o Yarn:

   ```bash
   yarn build
   ```

   Isso cria uma construção otimizada do aplicativo na pasta `.next`.

- `start`: Inicia o servidor de produção após a construção do aplicativo.

   ```bash
   npm run start
   ```

   Ou com o Yarn:

   ```bash
   yarn start
   ```

   Isso inicia o servidor de produção em [http://localhost:3000](http://localhost:3000).

- `lint`: Verifica o código usando o ESLint.

   ```bash
   npm run lint
   ```

   Ou com o Yarn:

   ```bash
   yarn lint
   ```

   Isso verifica seu código quanto a problemas de linting de acordo com as regras configuradas.

Se tiver alguma dúvida ou encontrar problemas, não hesite em pedir ajuda. 🌟