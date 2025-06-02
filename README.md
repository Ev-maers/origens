# 🛍️ Origens – Marketplace de Artesanato Nordestino

**Origens** é um projeto desenvolvido durante a residência Rise Up 2025.1 com o objetivo de valorizar o artesanato brasileiro, começando pelo Nordeste, conectando artesãos locais a consumidores através de uma plataforma digital intuitiva e acessível.

## 🚀 Tecnologias utilizadas

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [ESLint](https://eslint.org/)

## 📦 Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:

- [Node.js (v18+ recomendado)](https://nodejs.org/)
- [Git](https://git-scm.com/)

## ⚙️ Como executar o projeto localmente

Siga os passos abaixo para clonar e rodar o projeto na sua máquina:


### 1. Clone o repositório

git clone https://github.com/DeyvisonConrado/origens.git


### 2. Acesse a pasta do projeto

cd origens

### 3. Instale as dependências

npm install

### 4. Execute o projeto em ambiente de desenvolvimento

npm run dev

Após isso, o Vite iniciará o servidor local. Normalmente, você verá uma mensagem como:
Local: http://localhost:5173/

Acesse esse link no seu navegador para ver a aplicação rodando!


### Estrutura do Projeto

src/
├── assets/        → Imagens e recursos visuais
├── components/    → Componentes reutilizáveis (Header, Footer, CardProduto)
├── pages/         → Páginas principais (Home, Produtos)
├── App.jsx        → Estrutura geral da aplicação
├── main.jsx       → Ponto de entrada do React
├── index.css      → Estilos globais

### Versão MVP

O MVP entrega as seguintes funcionalidades:

* Página inicial com destaque cultural
* Listagem de produtos artesanais
* Layout responsivo básico
* Componentização das seções da interface




=============================================================================


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
