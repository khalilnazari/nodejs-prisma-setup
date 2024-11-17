## Initiate npm project

## instlal prisma and typescript

```
npm install typescript tsx @types/node --save-dev
```

## Initialize TypeScript

```
npx tsc --init
```

## Install Prisma CLI

```
npm install prisma --save-dev
```

## Setup Prisma ORM

```
npx prisma init
```

## create the Prisma schema

prisma/schema.prisma

## Update PostgreSQL database in .env file

```
DATABASE_URL="postgresql://db-username:db-password@domain:PORT/?schema=public"
```

## Run migration in development env

```
npx prisma migrate dev --name init
```

## Add a new colum in User schema and run below

This will create new column (phone) in User table.

```
npx prisma migrate dev --AddPhoneToUser
```
