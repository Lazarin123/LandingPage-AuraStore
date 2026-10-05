# E-commerce Headless & Interactive Catalog App

Um aplicativo de e-commerce moderno, responsivo e interativo, construído com foco em arquitetura headless, catálogo interativo e excelente experiência do usuário.

## 🚀 Funcionalidades

- **Catálogo Interativo de Produtos:** Visualização e filtragem dinâmica de produtos por categorias.
- **Carrinho de Compras em Tempo Real:** Adição, remoção e atualização da quantidade de itens de forma fluida.
- **Interface Responsiva:** Adaptada para dispositivos móveis, tablets e desktops.
- **Design Moderno:** Utilização de componentes Tailwind CSS para uma estilização limpa e ágil.
- **Arquitetura Headless:** Deslocamento da camada de apresentação para fácil integração com diversas APIs de backend e headless CMSs (por exemplo, Shopify Storefront API, Strapi, Contentful).

## 🛠️ Tecnologias Utilizadas

- **Frontend:** React (JSX/TSX), HTML5, CSS3
- **Estilização:** Tailwind CSS, Lucide Icons
- **Gerenciamento de Estado:** React Hooks (`useState`, `useEffect`, `useContext`)

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas em seu ambiente:

- [Node.js](https://nodejs.org/) (Versão 16.x ou superior recomendada)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## 🔧 Instalação e Execução

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   # ou
   yarn install
   ```

3. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

4. **Acesse a aplicação:**
   Abra o seu navegador e acesse `http://localhost:3000` (ou a porta indicada no terminal).

## 📂 Estrutura do Projeto

```text
.
├── src/
│   ├── components/     # Componentes reutilizáveis da interface
│   ├── data/           # Dados de simulação (Mock data)
│   ├── hooks/          # Custom Hooks do React
│   ├── App.jsx         # Aplicação principal
│   └── index.css       # Estilos globais e Tailwind CSS
├── public/             # Arquivos estáticos
├── package.json        # Dependências e scripts do projeto
└── README.md           # Documentação do projeto
```

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um **Fork** deste repositório.
2. Crie uma branch para sua funcionalidade (`git checkout -b feature/MinhaFuncionalidade`).
3. Faça o **Commit** das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`).
4. Envie as alterações para a sua branch (`git push origin feature/MinhaFuncionalidade`).
5. Abra um **Pull Request**.

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).