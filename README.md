# projeto-sds3

## Descrição do Projeto
Projeto desenvolvido durante a [Semana Spring React da DevSuperior](https://github.com/devsuperior/sds3).

### Ferramentas necessárias/utilizadas :
- [x] Curl
- [x] Git
- [x] Java JDK 11
- [x] Maven
- [x] STS
- [x] Postman
- [x] Postgresql e pgAdmin
- [x] Heroku CLI
- [x] Node & NPM
- [x] YARN (Caso queira usar ao invés do NPM)
- [x] VS Code

### Andamento do Projeto
- [x] Aula 1 - 03/05/2021
- [ ] Aula 2 - 05/05/2021
- [ ] Aula 3 - 07/05/2021

### Demonstração da Aplicação


#### Passos para implantação no Netlify
- Publicação no Netlify
    * Comando: yarn build
    * Diretório: build
      Deploy! (vai quebrar)
    * -> Site settings -> Build & Deploy: (colocar o nome da sua subpasta do projeto frontend)
    * -> Site settings -> Domain Management: (colocar o nome que você quiser)
    * -> Deploys -> Trigger deploy

### Badges
[![Netlify Status](https://api.netlify.com/api/v1/badges/a40749b2-82ce-4ff6-8d49-504aeba8e5e8/deploy-status)](https://app.netlify.com/sites/jpbraz-dsvendas/deploys)

### Tecnologias utilizadas:
- [x] SQL
- [x] JpaRepository
- [x] Spring
- [x] ReactJS com TypeScript

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [React](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [SQL]()

### Etapas
1) Criação do Projeto
  * Frontend
      npx create-react-app frontend --template typescript
  * Backend
    Criar projeto Spring Boot no Spring Initializr com as seguintes dependências:

Web
JPA
H2
Postgres
Security
