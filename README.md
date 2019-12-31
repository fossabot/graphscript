
<pre align="center">

   ____                 _                   _       _   
  / ___|_ __ __ _ _ __ | |__  ___  ___ _ __(_)_ __ | |_ 
 | |  _| '__/ _` | '_ \| '_ \/ __|/ __| '__| | '_ \| __|
 | |_| | | | (_| | |_) | | | \__ | (__| |  | | |_) | |_ 
  \____|_|  \__,_| .__/|_| |_|___/\___|_|  |_| .__/ \__|
                 |_|                         |_|        
</pre>

<p align="center"> A simple boilerplate GraphQL using TypeScript and TypeORM </p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License MIT">
  </a>
</p>


## :bulb: Introduction 

Graphscript is a simple boilerplate using the most recents technologies of Javascript, made with TypeScript. Creating a layer of service that possibility the management of Middlewares and Schemas.

## :house: Getting started

1. Clone this repo using: `https://github.com/kevenleone/graphscript.git`
2. Install the packages using your preference package manager ( yarn install or npm install )
3. Rename the files
    1. ormconfig.example.json to ormconfig.json
    2. .env.example to .env
4. Inside ormconfig.json configure with your preferences, the database, you can check the TypeORM Docs and select the best database option. https://typeorm.io/#/
5. Run ( yarn dev or npm run dev ) and open on browser: http://localhost:3333/graphql

## :tada: Features

Graphscript implement the following features

- :zap: **Apollo GraphQL** - A GraphQL Server for Express Library
- :books: **TypeORM** - ORM for TypeScript and JavaScript
- :whale: **Docker** - To setup all the environment needs, ready to deploy
- :clipboard: **Winston** - A logger for just about everything. 
- :passport_control: **JWT** - For protection of GraphQL Content

## :zap: Commands
- `npm run dev` - start the playground with hot-reload at `http://localhost:3333/playground`
- `npm start` - start the playground pointing for dist index at `http://localhost:3333/playground`
- `npm run build` - Builds the project: Typescript to Javascript

## :art: Inspired on

Project inspired on Krakren -> https://github.com/wendelfreitas/kraken

## :handshake: **Contributing**
If you liked the project and want to cooperate feel free to fork this repository and send Pull Requests.

All kinds of contributions are very welcome and appreciated

-   ⭐️ Star the project
-   🐛 Find and report issues
-   📥 Submit PRs to help solve issues or add features

## :book: License
MIT license, Copyright (c) 2019 Keven Leone.
