# basic-node-with-typescript

Iniciar um projeto nodejs
`npm init -y`

Adicionar dependências 
`npm i -D typescript ts-node nodemon @types/node`

Gerar o arquivo tsconfig.json
`npx tsc --init`

Adicionar ao package.json no campo scripts o comando pra inicializar o servidor
`"start": "nodemon src/server.ts",`

Usar o comando no terminal
`npm run start`
