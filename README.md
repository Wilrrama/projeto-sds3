# projeto-sds3
# DS Vendas
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Wilrrama/projeto-sds3/blob/master/LICENSE) 

# Sobre o projeto

https://wilson-sds3.netlify.app/

DSVendas é uma aplicação full stack web e mobile construída durante a 3ª edição da **Semana DevSuperior** (#sds3), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um resultado das vendas dos vendedores de uma empresa, onde os dados são listados paginados no app web, que também apresenta dois dashboards (donut, bar) com gráficos baseados nestes dados.

## Modelo conceitual
![Modelo Conceitual](https://raw.githubusercontent.com/devsuperior/bds-assets/main/sds/sds3-mc.png)

## Modelo de camadas
![Modelo Camadas](https://raw.githubusercontent.com/devsuperior/bds-assets/main/sds/camadas.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Apex Charts
- Expo
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/Wilrrama/projeto-sds3

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/Wilrrama/projeto-sds3

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Wilson Alves Franchi dos Santos

https://www.linkedin.com/in/wilson-alves-franchi-dos-santos-b3ba3332/
