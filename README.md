```
npm i typescript prisma-client
npx tsc --init
npm i -D prisma
npx prisma init --datasource-provider sqlite
# create User model to schema.prisma
npx prisma migrate dev --name init
```
