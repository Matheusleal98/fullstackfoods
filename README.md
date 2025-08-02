# Full Stack FSW Foods

FSW Foods é um projeto completo de e-commerce para restaurantes no estilo iFood, desenvolvido durante a Full Stack Week 4.0. Esta aplicação oferece um ecossistema completo para serviços de delivery, com integração entre frontend e backend, gerenciamento de estado e persistência de dados.

## Tecnologias
### Stack Principal

- Frontend: Next.js 14 com App Router
- Estilização: Tailwind CSS + Shadcn/ui
- Linguagem: TypeScript
- Backend: Server Actions integrado ao Next.js
- Autenticação: Next-Auth com provedor Google

### Banco de Dados

- ORM: Prisma
- Produção: PostgreSQL no Neon
- Desenvolvimento: PostgreSQL em container Docker

### Infraestrutura

- Deploy: Vercel
- Containerização: Docker para ambiente de desenvolvimento

## Features Implementadas
### Para Clientes
- 🔍 Busca inteligente de restaurantes
- 🛒 Sistema de carrinho com Context API
- ❤️ Lista de favoritos por usuário
- 📊 Sistema de avaliação de restaurantes
- 📦 Histórico de pedidos com opção de "Refazer pedido"

### Para Administração (Futuras implementações)
- 📊 Dashboard analítico
- 📦 Gestão de pedidos em tempo real
- 💰 Controle financeiro
- 🏬 Gerenciamento de múltiplos restaurantes

## Ambiente de Desenvolvimento
### Pré-requisitos

- Node.js 18+
- Docker e Docker Compose
- Conta no Google Developers para OAuth

## Configurações iniciais
### Cloning the repository

```shell
https://github.com/Matheusleal98/fullstackfoods.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID =
GOOGLE_CLIENT_SECRET =
```
### Setup Prisma ORM

```shell
npm run db:push

```

### Seed the app

```shell
npm run db:seed

```


### Start the app

```shell
npm run dev
```
