# Ignite-Lab-4-Node.js
Ignite Lab 04 - Node.js

Install [Nest.js](https://docs.nestjs.com) CLI
```sh
npm i -g @nestjs/cli
nest new notifications-service
```

Start the project
```sh
npm run start
```

Prisma
```sh
npm i prisma -D
npm i @prisma/client
npx prisma init --datasource-provider SQLite
```

Create the database, tables and updates
```sh
npx prisma migrate dev
```

Open Prisma Studio to Visualize and update the Database
```sh
npx prisma studio
```

## VS Code Extensions
- [Prisma](https://marketplace.visualstudio.com/items?itemName=Prisma.prisma)