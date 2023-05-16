## Step to install TypeScript in Node
- npm init - Iniciar o package.json
- npm i typescript -D - Instalar o TS no projeto
- npm i @types/node -D - Types para o TS do Node
- `npx` tsc - Gerar tsconfig.json e alterar o ES para 2020
- npm i tsx -D - Automatiza o processo de conversão de TS para JS

## Run Server TS
- npx tsx <file.js>
- package.json - `tsx watch src/server.ts` to keep running

## Install Fastify
- npm i fastify

## Install ESLint
- npm i eslint -D - Install ESLint as developer dependency
  - npm i @rocketseat/eslint-config -D - ESLint config from RocketSeat
 - Create eslintrc.json and extends RocketSeat config

 ## Install Prisma
 - npm i prisma -D - Install Prisma as Developer Dependency
 - npx prisma -h - Help from prisma
 - npx prisma init --datasource-provider SQlite to create SQLite DB
  - Create model in prisma/schema.prisma
  - run npx prisma migrate dev to create DB Table
  - npx prisma studio to open Prisma Studio

## Connect application with Prisma DB
- npm i @prisma/client