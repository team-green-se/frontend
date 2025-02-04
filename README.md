# Como Rodar o Projeto Front-end

Este repositório contém o projeto front-end do nosso projeto, desenvolvido com **React** e **Vite**. Se você quer saber como começar, siga os passos abaixo para rodar o projeto na sua máquina.

## Pré-requisitos

Antes de começar, você precisa ter o seguinte instalado:

- **Node.js**: Você pode baixar a versão mais recente do Node [aqui](https://nodejs.org/).
- **npm** (gerenciador de pacotes): Ele vem instalado junto com o Node.js.

Para verificar se já tem o Node.js e o npm instalados, execute os seguintes comandos no terminal:

```bash
node -v
npm -v
```

Se as versões aparecerem, isso significa que o Node.js e o npm estão instalados corretamente.

## Passos para rodar o projeto

1. **Clone o repositório**

   Primeiramente, você precisa clonar o repositório para a sua máquina local. Para fazer isso, abra o terminal e execute o seguinte comando:

   ```bash
   git clone https://github.com/team-green-se/frontend.git
   ```

   Navegue até a pasta do projeto:

   ```bash
   cd frontend
   ```

2. **Instale as dependências**

   Agora que você tem o código na sua máquina, é hora de instalar as dependências do projeto. Execute o seguinte comando no terminal:

   ```bash
   npm install
   ```

   Esse comando vai baixar todos os pacotes necessários para o projeto.

3. **Inicie o servidor de desenvolvimento**

   Após a instalação das dependências, você pode rodar o projeto localmente. Execute o seguinte comando:

   ```bash
   npm run dev
   ```

   Esse comando vai iniciar o servidor de desenvolvimento e você poderá acessar o aplicativo no navegador. O terminal vai mostrar o endereço, geralmente algo como `http://localhost:3000`.

4. **Abra o projeto no navegador**

   Abra o navegador e digite o endereço fornecido pelo terminal (geralmente `http://localhost:3000`). Agora você deve ver a aplicação rodando localmente!

## Estrutura do Projeto

Aqui estão os principais diretórios e arquivos do projeto:

- **public/**: Contém arquivos estáticos, como o `index.html`.
- **src/**: Contém o código-fonte do projeto, onde você vai trabalhar no desenvolvimento.
- **vite.config.js**: Arquivo de configuração do Vite.

## Dicas adicionais

- Se você tiver problemas ao rodar o projeto, tente deletar a pasta `node_modules` e o arquivo `package-lock.json`, e depois execute `npm install` novamente.
- Para parar o servidor de desenvolvimento, basta pressionar `Ctrl + C` no terminal.
