# nlw_heat_node
yarn init -y
yarn add express
yarn add -D @types/express typescript ts-node-dev

#iniciar tsc -> gera o arquivo tsconfig.json
yarn tsc --init

#start
yarn dev

#prisma
https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgres

yarn add prisma -D
yarn add @prisma/client


# cria o arquivo .env com as configurações e /prisma
yarn prisma init 

# credencial com o git
https://github.com/settings/developers

#ter acesso as variáveis do .env
yarn add dotenv

# fazer consulta apis
yarn add axios
yarn add @types/axios -D

# ajuda a criar token
yarn add jsonwebtoken
yarn add @types/jsonwebtoken -D

# rodar o migrateee do prisma
yarn prisma migrate dev

#ver dados banco de dados do prisma no navegador
yarn prisma studio

#web socket
yarn add socket.io
yarn add @types/socket.io -D

#cors -> permitir ou barrar requests
yarn add cors
yarn add @types/cors -D



yarn install
Instala todas dependências listadas no package.json em sua pasta local node_modules.