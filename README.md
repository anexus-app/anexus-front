# Projeto Full Stack com Angular, Ionic, Tailwind, Node.js, NestJS e MySQL

Este projeto é uma aplicação full stack utilizando as tecnologias mais modernas para o desenvolvimento de back-end e front-end, com foco em desempenho, escalabilidade e eficiência.

## Tecnologias Utilizadas

### Back-end:
- **[Node.js](https://nodejs.org/)**: Plataforma para execução de código JavaScript no lado do servidor.
- **[NestJS](https://nestjs.com/)**: Framework Node.js para a construção de APIs escaláveis e eficientes utilizando TypeScript.
- **[Swagger](https://swagger.io/)**: Ferramenta para documentação e teste de APIs RESTful.

### Banco de Dados:
- **[MySQL](https://www.mysql.com/)**: Sistema de gerenciamento de banco de dados relacional.

### Front-end:
- **[Angular 17/18 (Standalone)](https://angular.io/)**: Framework front-end para a construção de aplicações web dinâmicas e responsivas.
- **[Ionic 8](https://ionicframework.com/)**: Framework para a criação de aplicações móveis híbridas usando tecnologias web.
- **[TailwindCSS](https://tailwindcss.com/)**: Framework CSS utilitário para estilização rápida e eficiente.

## Estrutura do Projeto

- **Back-end**: Implementado utilizando Node.js com NestJS, fornecendo uma API REST documentada pelo Swagger.
- **Banco de Dados**: O projeto utiliza o MySQL como banco de dados, gerenciando as operações CRUD.
- **Front-end**: A interface do usuário é construída com Angular (versão standalone) e Ionic para garantir uma experiência mobile-first, com TailwindCSS responsável pelo estilo da aplicação.

## Instalação e Execução

### Pré-requisitos
Certifique-se de que você tenha instalado:
- **Node.js** (versão 20): [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
- **MySQL**: [https://dev.mysql.com/downloads/](https://dev.mysql.com/downloads/)

## Git FLow

Os Branches principais

develop -> O origin/develop será o branch principal, onde modificações realizadas na fase de desenvolvimento serão enviadas para o próximo release.

main -> origin/master será o branch principal onde seu HEAD sempre vai refletir o estado do código do projeto em produção.

Branches de apoio
Ao contrário dos branches principais esses possuem um tempo de vida limitado, uma vez que serão removidos posteriormente.

Os brances de apoio podem ser: Feature branches, Release branches e Hotfix branches.

#feature branches

Pode se ramificar a partir : develop
Pode ser mergeado para: develop

Convenção de nomes: feature/[nomedaatividade]

Qualquer coisa exceto master, develop, release-* ou hotfix-*

#Release branches

Pode ramificar a partir de: develop
Pode ser mergeado para: develop e master
Conversão de nomenclatura: release-*

#Hotfix branches

Pode ramificar a partir de: develop
Pode ser mergeado para: develop e master
Conversão de nomenclatura: hotfix-*
