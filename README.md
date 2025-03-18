# Template React com Vite

Este projeto é um template básico para iniciar um aplicativo React utilizando o Vite.

## Pré-requisitos

Esse template foi criado com as seguintes ferramentas e versões:
- [Node.js](https://nodejs.org/) (versão 18.19.1)
- [npm](https://www.npmjs.com/) (versão 10.2.4)

## Instalação

Siga os passos abaixo para configurar o projeto:

**Clone o repositório:**
  ```bash
  git clone https://github.com/gabrieloliveirapimentel/template-react.git
  cd template-react
  ```

**Instale as dependências:**
  Usando npm:
  ```bash
  npm install
  ```
  Ou usando yarn:
  ```bash
  yarn
  ```

**Inicie o servidor de desenvolvimento:**
  Usando npm:
  ```bash
  npm run dev
  ```
  Ou usando yarn:
  ```bash
  yarn dev
  ```

**Acesse a aplicação:**
  Abra o navegador e acesse [http://localhost:3001](http://localhost:3001).

## Estrutura do Projeto

```bash
- src/: Contém os arquivos principais do projeto.
  -- assets/: Pasta para ser inserido as mídias do projeto
  -- pages/: Pasta com as páginas do projeto
  --- Home/: Página inicial do projeto
  ---- index.tsx: Arquivo da tela inicial
  ---- styles.ts: Arquivo para estilização da tela inicial 
  main.tsx: Ponto de entrada da aplicação.
  App.tsx: Componente principal.
- public/: Arquivos estáticos.
```

## Criando um Novo Projeto com Vite
Se você deseja criar um novo projeto do zero, siga estas etapas:

**Crie o projeto:**
  ```bash
  npm create vite@latest
  ```

Nessa etapa é solicitado o nome do projeto, framework (React) e a variação (Typescript).

**Dê um nome para seu projeto o diretório do projeto:**
  ```bash
  cd nome-do-projeto
  ```

**Instale as dependências e inicie o servidor:**
  ```bash
  npm install
  npm run dev
  ```

## Referências
- [Documentação do React](https://reactjs.org/)
- [Documentação do Vite](https://vitejs.dev/)