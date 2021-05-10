<h1 align="center">
    <a href="https://github.com/jpbraz/projeto-sds3">🔗 PROJETO-SDS3
</a>
</h1>


## Descrição do Projeto
🚀 Projeto desenvolvido durante a [Semana Spring React da DevSuperior](https://github.com/devsuperior/sds3).

&nbsp;&nbsp;&nbsp;

## 🛠 Ferramentas necessárias/utilizadas:
- [x] Curl
- [x] Git
- [x] Java JDK 11
- [x] Maven
- [x] STS
- [x] Postman
- [x] Postgresql e pgAdmin (ou DBeaver)
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


&nbsp;&nbsp;&nbsp;

## 🏃 Andamento do Projeto
- [x] Aula 1 - 03/05/2021 :heavy_check_mark:
- [x] Aula 2 - 05/05/2021 :heavy_check_mark:
- [x] Aula 3 - 07/05/2021 :heavy_check_mark:

### Demonstração da Aplicação
[<img src="https://github.com/jpbraz/projeto-sds3/blob/main/frontend/src/assets/img/Captura%20de%20tela%20de%202021-05-05%2000-06-40.png" width=80% >
<br>jpbraz-dsvendas](https://jpbraz-dsvendas.netlify.app/)


### Badges
[![Netlify Status](https://api.netlify.com/api/v1/badges/a40749b2-82ce-4ff6-8d49-504aeba8e5e8/deploy-status)](https://app.netlify.com/sites/jpbraz-dsvendas/deploys)
![Heroku](https://pyheroku-badge.herokuapp.com/?app=sds3-jp&style=plastic)

&nbsp;&nbsp;&nbsp;

## ⏲️ Etapas
### Criação do Projeto (monorepo)
   #### 1) Frontend
   - Criar o React App no diretório do projeto:
   
   `npx create-react-app frontend --template typescript`
        
   Lembrar de remover o arquivo .git
   
   - Adicionar Bootstrap para utiliziar no projeto:
   
   `yarn add bootstrap`
   
   - Adicionar biblioteca de gráficos estáticos: Apex Charts
   
   `yarn add apexcharts react-apexcharts`

   #### 2) Backend
   Criado projeto Spring Boot no *[Spring Initializr](https://start.spring.io/)* com as seguintes dependências:
   - Web
   - JPA
   - H2
   - Postgres
   - Security
    
   ##### Deploy da Aplicação com Netlify: :dash:
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

   #### 3) Implementação do Backend
   Padrão de camadas utilizado (repositories, DTO's, service e controller), com busca paginada e agrupada:
   [<img src="https://github.com/devsuperior/bds-assets/raw/main/sds/camadas.png" width=50% >](https://spring.io/guides)
   
   - Criado três arquivos de properties com perfis de: test, dev, prod
   - Gerado script SQL no perfil dev para criação das tabelas do Banco de Dados ([create.sql](https://github.com/jpbraz/projeto-sds3/blob/main/backend/create.sql))
   
   #### 4) Implementação e Deploy no Heroku:
   - Criado novo app no [Heroku](heroku.com)
   - Provisionado banco Postgres, definindo variável APP_PROFILE=prod
   - Criado servidor de acesso local via DBeaver (poderia ser feito via PgAdmin) utiliando dados de credenciais do Database.
   - Deploy do backend no Heroku via terminal (no diretório do projeto):
 
    heroku login
    heroku git:remote -a <nome-do-app>
    git subtree push --prefix backend heroku maingit subtree push --prefix backend heroku main

   #### 4) Integração do backend (Heroku) com o frontend (Netlify):
   - Criação de Rotes e Links com o react-router-dom, para as pages Home e Dashboard.
   - Criação de request com o [axios](https://github.com/axios/axios): ```yarn add axios``` 
   - Definição do BASE_URL do BACKEND em "request.ts" e Heroku -> Build & Deploy -> Environment;
   - Integração com Hooks (useState e useEffect) em BarChart, DonutChart e DataTable para rederenzição dos dados
   - Criação do componente Pagination
   - Adicionado rederização condicional com o useState isLoading

&nbsp;&nbsp;&nbsp;

## :octocat: Colaboradores:
[<img src="https://avatars.githubusercontent.com/u/49927924?s=200&v=4" width=60 > <br> <sub> João Paulo Braz </sub>](https://github.com/jpbraz) |
| :---: | 
[<img src="https://avatars.githubusercontent.com/u/66876849?s=200&v=4" width=60 > <br> <sub> DevSuperior </sub>](https://github.com/devsuperior) |
[<img src="https://avatars.githubusercontent.com/u/13897257?s=200&v=4" width=60 > <br> <sub> Nelio Alves </sub>](https://github.com/acenelio) |

