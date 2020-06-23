# SERVERLESS FOR VERCEL

CONFIGURE FIRST THE config.json on config folder

1. npm install
2. npm i -g sequelize-cli <-- SEQUELIZE-CLI
3. npm i -g @zeit/ncc <-- BUILDER
4. npm i -g now <-- VERCEL CLI FOR DEPLOYMENT
5. sequelize db:create
6. sequelize db:migrate
7. sequelize db:seed:all
8. npm run build <-- BUILD
9. now --prod

---------------------------------
Create Models
---------------------------------
RUN: sequelize model:generate --name User --attributes firstName:string,lastName:string

Available Data Types
- string
- text
- integer
- float