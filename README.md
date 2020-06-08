<h1 align='center'>
  Ecoleta :recycle:
</h1>

## Sobre 💻
Projeto desenvolvido durante a Next Level Week #01 da Rocketseat 
com o objetivo de conectar empresas e entidades que realizam coleta de resíduos 
com as pessoas que precisam descartar seus resíduos de maneira ecológica.

## :rocket: Tecnologias usadas

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)

## Como rodar o projeto
### Criando o banco de dados
```
# Acesse a pasta do projeto no terminal/cmd
$ cd Ecoleta

# Vá para a pasta Backend
$ cd server

# Crie o banco de dados
$ npm run knex:migrate

# Adicione os items de coleta no BD
$ npm run knex:seed
```

### Executando o Backend
```
# Acesse a pasta do projeto no terminal/cmd
$ cd Ecoleta

# Vá para a pasta Backend
$ cd server

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm run dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333 
```

### Executando o Frontend
```
# Acesse a pasta do projeto no seu terminal/cmd
$ cd Ecoleta

# Vá para a pasta da aplicação FrontEnd
$ cd web

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```

### Executando o Mobile
```
# Acesse a pasta do projeto no seu terminal/cmd
$ cd Ecoleta

# Vá para a pasta da aplicação FrontEnd
$ cd mobile

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm start

# A aplicação será aberta na porta:19000. Leia o QR Code com seu celular 
ou utilize um simulador IOS ou Android para executar o projeto
```
