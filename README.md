👑⚛️ Aplicação React com Pages e React Router DOM
Projeto Acadêmico – Arquitetura Front-end e Navegação SPA

Este projeto acadêmico foi desenvolvido com o objetivo de aplicar uma arquitetura front-end escalável em React, utilizando o conceito de Pages, componentização e navegação SPA (Single Page Application) com React Router DOM 🧭.

A aplicação foi construída seguindo boas práticas de organização de código, separação de responsabilidades e integração entre UI/UX Design e desenvolvimento front-end 🎨💻.

🎯 Objetivos Técnicos

🧩 Estruturar a aplicação utilizando o conceito de Pages

🗂️ Organizar as páginas em src/pages, promovendo escalabilidade

🧭 Implementar navegação SPA com react-router-dom

🔗 Substituir navegação tradicional (<a>) por <Link>, evitando reloads

🧠 Centralizar o gerenciamento de rotas em src/routes.js

🎨 Garantir consistência visual com CSS Modules

🧼 Manter um código limpo, legível e de fácil manutenção

🛠️ Stack Tecnológica
Tecnologia	Descrição
⚛️ React.js	Biblioteca principal para construção da interface
🧭 React Router DOM	Gerenciamento de rotas e navegação entre páginas
📜 JavaScript (ES6+)	Lógica, eventos e manipulação de estado
🎨 CSS Modules	Estilização modular, evitando conflitos globais
🖌️ Figma	Design system, wireframes e prototipagem
💻 VS Code	Ambiente de desenvolvimento
🎨 Processo de Design (UI/UX)

Antes da implementação em código, o projeto passou por uma etapa completa de planejamento visual no Figma, seguindo princípios de UI/UX Design:

🎯 Guia de Estilo

Paleta de cores

Tipografia

Assets visuais

🧱 Wireframe

Estruturação da hierarquia visual

Organização dos componentes de interface

🖥️ Interface Final

Layout final pronto para implementação

Consistência visual entre páginas

Essa abordagem reduziu retrabalho e garantiu maior fidelidade entre design e código.

⚙️ Arquitetura da Aplicação

A aplicação foi organizada com foco em escalabilidade e separação de responsabilidades:

src/
├── components/        # Componentes reutilizáveis
├── pages/             # Páginas da aplicação
│   ├── Home/
│   │   ├── index.jsx
│   │   └── Home.module.css
│   └── Watch/
│       ├── index.jsx
│       └── Watch.module.css
├── routes.js          # Centralização das rotas
├── App.js             # Componente raiz
└── index.js           # Ponto de entrada


📌 Destaques arquiteturais:

Rotas desacopladas do App.js

Estilos escopados por página

Componentes reutilizáveis e organizados

Estrutura preparada para crescimento do projeto

🔎 Funcionalidades Implementadas

🧭 Navegação entre páginas sem recarregamento

🎬 Página Watch dedicada à visualização de conteúdo

🔎 Barra de busca interativa:

Aceita valores de 1 a 6

Filtra e exibe integrantes conforme o valor digitado

🧹 Botão de limpar busca, melhorando a experiência do usuário

🚀 Como Executar o Projeto
# Instalar as dependências
npm install

# Executar o projeto
npm start


A aplicação será executada em http://localhost:3000.

📚 Aprendizados e Conceitos Aplicados

Arquitetura SPA com React

Organização de projetos front-end

React Router DOM na prática

Componentização e reutilização

Integração entre design e desenvolvimento

Boas práticas de UI/UX

🏁 Considerações Finais

Este projeto representa uma base sólida para aplicações React modernas, combinando planejamento visual, arquitetura front-end e boas práticas de desenvolvimento ⚛️✨.

Ele pode ser facilmente expandido com:

Novas páginas

Integração com APIs

Gerenciamento de estado global

Autenticação e controle de rotas
