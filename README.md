# nodets-canil
## 1 - Criar um repositório no github
2 - Clonar o projeto na máquina e abrir no visual studio
3 - Iniciar o projeto(npm init)
4 - Criar arquivo do typescript(tsc --init)
5 - Configurar o arquivo do typescript descomentando as linhas("target": "es6", "module":"commonjs","rootDir": "./src", "moduleResolution": "node",  )
6 - Instalar dependências do projeto(npm install express mustache-express dotenv)
7 - Instalar types referente as dependências no ambiente de desenvolvimento(npm install --save-dev @types/express @types/mustache-express @types/node)
8 - Configurar script para start da aplicação no arquivo package.json("start-dev": "nodemon -e ts,json,mustache src/server.ts")
9 - Criar o servidor(configurar o express, dotenv, mustache e a pasta publica)
10 - Configurar as rotas
11 - Criar estrutura para os controllers e models
