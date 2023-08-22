# basic-node-with-typescript

Iniciarlizar o projeto
`npm init -y`

Adicionar dependências
`npm i -D typescript ts-node nodemon @types/node`

Gerar o arquivo tsconfig.json
`npx tsc --init`

Adicionar ao package.json no campo scripts o comando pra inicializar o servidor
`"start": "nodemon src/server.ts",`

Iniciar via terminal o servidor
`npm run start`

## Gerar código JS
- Editar o arquivo tsconfig.json alterando as propriedades outDir e rootDir
```
{
 "outDir": "./dist",
 "rootDir": "./src"
}
```

- Rodar o comando `npx tsc`
