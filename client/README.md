# Capputeeno - Catálogo de Loja

Bem-vindo ao projeto Capputeeno! Este repositório contém o código do lado do cliente para o Capputeeno, um catálogo de loja online. Este documento o guiará pelo processo de configuração e execução do projeto em sua máquina local.

## Pré-requisitos

Antes de começar, certifique-se de ter os seguintes softwares instalados em seu sistema:

- [Node.js](https://nodejs.org/) (versão recomendada: 16.x ou superior)
- [npm](https://www.npmjs.com/) (vem com o Node.js) ou [Yarn](https://yarnpkg.com/) (recomendado)

## Instalação

1. Clone este repositório em sua máquina local:

   ```bash
   git clone https://github.com/Kianelc/capputeeno.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd capputeeno
   ```

3. Instale as dependências do projeto usando o npm:

   ```bash
   npm install
   ```

   Ou se preferir usar o Yarn:

   ```bash
   yarn
   ```

## Scripts Disponíveis

No diretório do projeto, você pode executar os seguintes scripts:

- `dev`: Inicie o servidor de desenvolvimento.

   ```bash
   npm run dev
   ```

   Ou com o Yarn:

   ```bash
   yarn dev
   ```

   Isso iniciará o servidor de desenvolvimento em [http://localhost:3000](http://localhost:3000).

- `build`: Construa o aplicativo pronto para produção.

   ```bash
   npm run build
   ```

   Ou com o Yarn:

   ```bash
   yarn build
   ```

   Isso criará uma construção otimizada do aplicativo na pasta `.next`.

- `start`: Inicie o servidor de produção após a construção do aplicativo.

   ```bash
   npm run start
   ```

   Ou com o Yarn:

   ```bash
   yarn start
   ```

   Isso iniciará o servidor de produção em [http://localhost:3000](http://localhost:3000).

- `lint`: Faça a verificação de código usando o ESLint.

   ```bash
   npm run lint
   ```

   Ou com o Yarn:

   ```bash
   yarn lint
   ```

   Isso verificará seu código quanto a problemas de linting de acordo com as regras configuradas.

## Notas Importantes

- Este projeto utiliza o Next.js, que oferece renderização do lado do servidor e outras otimizações de desempenho prontas para uso.
- O ESLint está configurado com a configuração recomendada do Next.js para qualidade do código.
- Certifique-se de manter suas dependências atualizadas por motivos de segurança e desempenho.

Se você encontrar problemas ou tiver dúvidas, não hesite em pedir ajuda. 🌟