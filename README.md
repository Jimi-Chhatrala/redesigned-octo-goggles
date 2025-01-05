# Nodejs Sequelize PostgreSQL Project
<!-- # redesigned-octo-goggles -->
A backend project made using NodeJS, Sequelize ORM and PostgreSQL database.

commands:

npx sequelize-cli db:create

npx sequelize-cli model:generate --name user --attributes userType:ENUM,firstName:string,lastName:string,email:string,password:string

npx sequelize-cli db:migrate

npx sequelize-cli db:migrate:undo

npx sequelize-cli db:migrate:undo all
