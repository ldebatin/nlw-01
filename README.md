<h2 align="center">
   NextLevelWeek 1.0
</h2>
<h1 align="center">
    <img alt="Ecoleta" title="Ecoleta" src=".github/ecoleta.svg" width="220px" />
</h1>

<p align="center">
  <img alt="Project programing languages count" src="https://img.shields.io/github/languages/count/ldebatin/nlw-01?color=34cb79">
   <img alt="Repository size" src="https://img.shields.io/github/repo-size/ldebatin/nlw-01?color=34cb79">
  <img alt="Last commit on GitHub" src="https://img.shields.io/github/last-commit/ldebatin/nlw-01?color=34cb79">
  <img alt="Made by Stefano" src="https://img.shields.io/badge/made%20by-ldebatin-%20?color=34cb79">
  <img alt="Project top programing language" src="https://img.shields.io/github/languages/top/ldebatin/nlw-01?color=34cb79">
  <img alt="GitHub license" src="https://img.shields.io/github/license/ldebatin/nlw-01?color=34cb79">
    <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=7159c1&labelColor=34cb79">
</p> 

<br>

### Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)

### Projeto

Projeto desenvolvido durante a primeria [Next Level Week](https://nextlevelweek.com/) 
O Ecoleta é um marketplace que ajuda pessoas a encontrarem pontos de coleta de resíduos de forma eficiente.

### Layout

###  Requisitos

Para executar a aplicação você vai precisar:
* [Git](https://git-scm.com)
* [Node](https://nodejs.org/)
* [Yarn](https://yarnpkg.com/) 

### Backend
Primeiro será necessário clonar o repositório e instalar as dependências.
```bash
# clonar repositório
$ git clone https://github.com/ldebatin/nlw-01.git

# acessar a pasta do backend
$ cd server

# instalar as dependências
$ yarn

```
A aplicação já conta com um banco sqlite instalado sendo necessário apenas rodar as migrations, as configurações estão no arquivo connection.ts.

```bash
# executar as migrations
$ yarn knex:migrate

# executar as seeds
$ yarn knex:seed

# iniciar a aplicação
$ yarn dev
```

### Frontend

```bash
# em uma nova aba, acessar a pasta do frontend
$ cd web

# instalar as dependências
$ yarn

# iniciar a aplicação
$ yarn start
```

### Mobile

A aplicação mobile foi desenvolvida utilizando o [Expo](https://expo.io/learn).

```bash
# em uma nova aba, acessar a pasta do mobile
cd mobile

# instalar as dependências
$ yarn
```

Antes de iniciar a aplicação é necessário configurar a URL de acesso a aplicação de backend no arquivo api.ts com o ip da sua máquina, esse passo é necessário para conseguir testar o app no aplicativo do Expo no celular.

```bash
# iniciar a aplicação
yarn start

```

### Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.