<h1 align="center">
    <a href="https://github.com/jpbraz/projeto-sds3">🔗 PROJETO-SDS3
</a>
</h1>

## Descrição do Projeto
🚀 Projeto desenvolvido durante a [Semana Spring React da DevSuperior](https://github.com/devsuperior/sds3).

## 🛠 Ferramentas necessárias/utilizadas:
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

### Tecnologias utilizadas :

As seguintes ferramentas foram usadas na construção do projeto:

- [React](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Spring Data JPA - JpaRepository](https://spring.io/)


## 🏃 Andamento do Projeto
- [x] Aula 1 - 03/05/2021 :heavy_check_mark:
- [ ] Aula 2 - 05/05/2021
- [ ] Aula 3 - 07/05/2021

### Demonstração da Aplicação
[<img src="https://github.com/jpbraz/projeto-sds3/blob/main/frontend/src/assets/img/Captura%20de%20tela%20de%202021-05-05%2000-06-40.png" width=80% >
<br>jpbraz-dsvendas](https://jpbraz-dsvendas.netlify.app/)


### Badges
[![Netlify Status](https://api.netlify.com/api/v1/badges/a40749b2-82ce-4ff6-8d49-504aeba8e5e8/deploy-status)](https://app.netlify.com/sites/jpbraz-dsvendas/deploys)

## ⏲️ Etapas
### Criação do Projeto (monorepo)
   ##### 1) Frontend
   - Criar o React App no diretório do projeto:
   
   `npx create-react-app frontend --template typescript`
        
   Lembrar de remover o arquivo .git
   
   - Adicionar Bootstrap para utiliziar no projeto:
   
   `yarn add bootstrap`
   
   - Adicionar biblioteca de gráficos estáticos: Apex Charts
   
   `yarn add apexcharts react-apexcharts`

   ##### 2) Backend
   Criado projeto Spring Boot no *Spring Initializr*(https://start.spring.io/) com as seguintes dependências:
   - Web
   - JPA
   - H2
   - Postgres
   - Security
    
   #### Deploy da Aplicação com Netlify: :dash:
   Configurações para a Publicação no Netlify:
   - Site -> *New site from Git*
        
   - Basic build settings
        - Build Comand: yarn build
        - Publish Directory: build
        - *Deploy site*
        
        Deploy! (vai quebrar)
   - Site settings
        - Build & Deploy: (colocar o nome da sua subpasta do projeto frontend)
        - Domain Management: (colocar o nome que você quiser)
   - Deploys -> *Trigger deploy*
   > https://jpbraz-dsvendas.netlify.app/

## :octocat: Colaboradores:
[<img src="https://avatars.githubusercontent.com/u/49927924?s=200&v=4" width=60 > <br> <sub> João Paulo Braz </sub>](https://github.com/jpbraz) |
| :---: | 
[<img src="https://avatars.githubusercontent.com/u/66876849?s=200&v=4" width=60 > <br> <sub> DevSuperior </sub>](https://github.com/devsuperior) |
[<img src="https://avatars.githubusercontent.com/u/13897257?s=200&v=4" width=60 > <br> <sub> Nelio Alves </sub>](https://github.com/acenelio) |

