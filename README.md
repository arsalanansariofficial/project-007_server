## 🚀 Project 007

Project based on **Strapi** & **Node JS** provides server API's for Project 007.

### Pre Requisites

- **Node.js** version **21** or greater.

### Dependencies used by the project

01. **react**
02. **cross-env**
03. **react-dom**
04. **@strapi/strapi**
05. **better-sqlite3**
06. **react-router-dom**
07. **styled-components**
08. **@strapi/plugin-i18n**
09. **@strapi/plugin-cloud**
10. **@strapi/plugin-users-permissions**

### Available scripts

1. `npm run strapi` for internal strapi usages.

2. `npm run deploy` for deploying the application to the cloud.

3. `npm run develop` for running the application in local environment.

4. `npm run start` for running the application in production environment.

5. `npm run build` for building the application for production environment.

### Required environment variables

#### Server Variables

01. `PORT` port number where server is actually running.

02. `HOST` name of the host where server is actually running.

03. `TRANSFER_TOKEN_SALT` any hashed `22 bit` string followed by `==` for token transfer.

04. `JWT_SECRET` any hashed `22 bit` string followed by `==` for generating `JWT Tokens`.

05. `API_TOKEN_SALT` any hashed `22 bit` string followed by `==` for generating `API Token`.

06. `ADMIN_JWT_SECRET` any hashed `22 bit` string followed by `==` for generating `ADMIN Token`.

07. `APP_KEYS` any hashed `22 bit` string followed by `==` multiple keys can be specified using a `comma` seprator.

#### Database Variables

01. `DATABASE_FILENAME` location of the `.db` file.

02. `DATABASE_CLIENT` for connecting to specific `database`.

#### Postman collection for api can be found in `./public/api` folder.
