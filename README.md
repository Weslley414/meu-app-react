Este projeto acadêmico tem como objetivo estruturar uma aplicação React utilizando o conceito de Pages e navegação entre páginas (SPA) com React Router DOM, aplicando boas práticas de organização, modularidade e escalabilidade no desenvolvimento front-end.

A aplicação foi desenvolvida seguindo uma arquitetura clara, com separação de responsabilidades e foco em manutenibilidade, servindo como base para projetos React de pequeno e médio porte.

🎯 Objetivos do Projeto

Estruturar a aplicação no conceito de Pages, organizadas em src/pages

Criar as páginas principais:

Home – conteúdo principal da aplicação

Watch – página de visualização de conteúdo

Implementar navegação SPA (Single Page Application) utilizando react-router-dom

Refatorar componentes para utilizar o componente <Link> no lugar de tags HTML <a>

Centralizar o gerenciamento de rotas no arquivo src/routes.js, facilitando a manutenção e escalabilidade do projeto

🛠️ Tecnologias Utilizadas

React.js – biblioteca principal para construção da interface

React Router DOM – gerenciamento de rotas e navegação entre páginas

JavaScript (ES6+)

CSS Modules – estilização modular e escopada

Figma – design de interface e prototipagem

VS Code – ambiente de desenvolvimento

🎨 Processo de Desenvolvimento
🔹 Design no Figma

Antes da implementação em código, o projeto foi planejado no Figma, seguindo um fluxo de design estruturado:

Criação do guia de estilo, com definição de:

Paleta de cores

Tipografia

Assets visuais

Desenvolvimento do wireframe para estruturação da interface

Montagem da interface visual final, garantindo consistência antes da codificação

🔹 Implementação no Código

Com o design definido, foi iniciada a etapa de desenvolvimento:

Organização da estrutura de diretórios e componentes

Criação das páginas Home e Watch

Configuração das rotas utilizando:

BrowserRouter

Routes

Route

Aplicação dos estilos com CSS Modules, garantindo escopo e organização do CSS

📁 Estrutura do Projeto (Resumo)
src/
├── components/
├── pages/
│   ├── Home/
│   └── Watch/
├── routes.js
├── App.js
└── index.js

🚀 Considerações Finais

Este projeto representa uma base sólida para aplicações React com navegação entre páginas, unindo planejamento visual (UI/UX) e boas práticas de desenvolvimento front-end.
Ele pode ser facilmente expandido com novas páginas, funcionalidades e integrações.
