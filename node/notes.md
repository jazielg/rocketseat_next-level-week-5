# Aula 01 - Liftoff

`https://www.youtube.com/watch?v=KYmvnN9X3UY`

Material Complementar: `https://www.notion.so/Trilha-Node-js-0b238db0256c4ce889df0e9ce92f4a68`

```bash
# Iniciar projeto node
yarn init -y

# Instalar microframework express - https://expressjs.com/pt-br/
yarn add express
yarn add @types/express -D
```

```bash
# Instalar e configurar o typescript
yarn add typescript -D

yarn tsc --init

yarn add ts-node-dev -D

# EM package.json
# "scripts": {
#   "dev": "ts-node-dev src/server.ts"
# },

yarn dev
```

# Aula 02 - Maximum Speed

`https://www.youtube.com/watch?v=2aIhICvFWO4`

```bash
# Instalar TypeORM - https://typeorm.io/#/
yarn add typeorm reflect-metadata sqlite3
```

- Criar arquivo `ormconfig.json` na raiz e criar pasta `database` dentro do `src`.

```bash
# Criar migrações
yarn typeorm migration:create -n CreateSettings

# Executar migrações
yarn typeorm migration:run

# Criar uuid
yarn add uuid
yarn add @types/uuid -D
```

- https://www.beekeeperstudio.io

# Aula 03 - In Orbit

`https://www.youtube.com/watch?v=L_pnDYasaog`

```bash
# Criação de tabelas e relacionamento
yarn typeorm migration:create -n CreateUsers
yarn typeorm migration:create -n CreateMessages
yarn typeorm migration:create -n CreateConnections

yarn typeorm migration:run
```

# Aula 04 - Landing

`https://www.youtube.com/watch?v=rjQJHrcqku8`

```bash
# WebSocket - https://socket.io/
yarn add socket.io
yarn add @types/socket.io -D
```

```bash
# Preparando página client
yarn add ejs
yarn add socket.io-client
```

# Aula 05 - Surface Exploration

`https://www.youtube.com/watch?v=zRGXhZmDHG8`

```bash
Template no HTML - https://github.com/janl/mustache.js


yarn dev

http://localhost:3333/pages/client
http://localhost:3333/pages/admin
```
