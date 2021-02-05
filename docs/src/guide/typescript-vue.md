# Proyects with Typescript

## Typescript with Graphql, Type-ORM, Type-graphql

Packages needed to start working with this technology

### Dev Dependencies

```
  npm i -D nodemon typescript ts-node @types/node

```

### Dependencies

```
    npm i express apollo-server-express graphql class-validator mysql type-graphql typeorm reflect-metadata

```

### Installacion

1. `npm install typeorm -g`
2. `typeorm init --name MyProject --database mysql`
3. `cd name_proyect && npm i`
4. `npm i -D nodemon`
5. `npm i express apollo-server-express graphql class-validator`
6. create script dev
7. `"dev": "nodemon --exec ts-node src/index.ts"`

::: tip
Here is the example with the repository [GITHUB]("https://github.com/Allan-Sanchez/api-rest-type-orm-graphql")
:::


## Typescript with Mongoose 

API created with typescript and mongoose using graphql-tools and apollo-server-express 
### Dev Dependencies

```
  npm i -D nodemon @types/cors @types/express @type/express-graphql @types/node ts-node typescript @types/dotenv @types/mongoose

```

### Dependencies

```
    npm i express apollo-server-express graphql graphql-import-node graphql-tools ncp mongoose dotenv

```

### Installacion

1. `npm init -Y`
2. `install dev dependencies && install dependecies`
3.  `git init && .gitignore`
4.  `touch tsconfig.json || npx tsconfig.json`
5.  `change rootDir `
6.  `change package.json dev nodemon src/main.ts --exec ts-node src/main.ts -e ts,graphql`

::: tip
Here is the example with the repository [GITHUB]("https://github.com/Allan-Sanchez/crud-typescript-graphql")
:::


## Typescript with prisma
### Installacion

1. `npm init -Y`
2. `install package`
3. `touch tsconfig.json || npx tsconfig.json {lib[esnext]}`
4.  `npx prisma init`
5.  `change .env`
6.  `create model`
7.  `npx prisma migrate dev --name init --preview-feature`
8.  `npm install @prisma/client`
* `install dev dependencies && install dependecies`
4.
*  `git init && .gitignore`
*  `touch tsconfig.json || npx tsconfig.json`
*  `change rootDir `
*  `change package.json dev nodemon src/main.ts --exec ts-node src/main.ts -e ts,graphql`

### Dev Dependencies

```
  npm i -D nodemon @types/cors @types/express @types/node ts-node typescript prisma @types/dotenv 

```

### Dependencies

```
    npm i express apollo-server-express graphql graphql-import-node graphql-tools dotenv 

```
::: tip
Here is the example with the repository [GITHUB]("https://github.com/Allan-Sanchez/")
:::
