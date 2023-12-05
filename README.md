# back_end_express_begin
Corpo de uma aplicação express, com comandos para iniciar uma aplicação do 0



# Passo a Passo para uma aplicação express do 0 (typescript, typeorm)

- rodar comando npm init -y

- rodar comando npm i -D ts-node-dev typescript

- rodar comando npm i -S express e npm i -D @types/express

- rodar comando npx tsc --init

- configurar o tsconfig.json

- no package.json adicionar no scripts =>  "dev": "tsnd --cls --rs --ignore-watch node_modules src/app.ts"

- npm i -S typeorm pg reflect-metadata (configurar o tsconfig >> procurar decorators e descomentar as 2 linhas, strict property inicialization descomentar e colocar false)

- adicionar o .gitignore

- adicionar .env e .evn.example

# Instalar Bibliotecas necessárias :

- npm i -S pg
- npm i -D @types/pg
- npm i pg-format
- npm i -D @types/pg-format
- npm i -S dotenv
- npm i -S express-async-errors (primeiro import do app)
- npm i -S zod 
- npm i -S jsonwebtoken
- npm i -D @types/jsonwebtoken
- npm i bcryptjs
- npm install --save-dev @types/bcryptjs

# Criar a estrutura do projeto.

- configurar app.ts, server.ts, data-source.ts

- instalar cors => npm i cors , npm i --save-dev @types/cors
