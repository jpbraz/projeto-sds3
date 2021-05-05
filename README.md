<h1 align="center">
    <a href="https://github.com/jpbraz/projeto-sds3">🔗 PROJETO-SDS3
</a>
</h1>

### Descrição do Projeto
🚀 Projeto desenvolvido durante a [Semana Spring React da DevSuperior](https://github.com/devsuperior/sds3).

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
- [jpbraz-dsvendas](https://jpbraz-dsvendas.netlify.app/)

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

### 🛠 Tecnologias utilizadas:

As seguintes ferramentas foram usadas na construção do projeto:

- [React](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Spring Data JPA - JpaRepository](https://spring.io/)

### Etapas
1) Criação do Projeto
   * Frontend
  ```shell npx create-react-app frontend --template typescript```
      
  * Backend
    Criado projeto Spring Boot no Spring Initializr com as seguintes dependências:
    * Web
    * JPA
    * H2
    * Postgres
    * Security
