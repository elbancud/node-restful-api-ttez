<div align="center">

</div>

### About the project

> Under heavy construction and optimization

Restful Api integration and testing. A practical usage of OOP & TDD.

### Tech stack

- [Express](http://expressjs.com/)
- [Node JS](https://nodejs.org/en/docs/)

### Dependencies breakdown

- [dotenv](https://www.npmjs.com/package/dotenv) - For .env configs
- [winston](https://www.npmjs.com/package/winston) - For logs alternate for console.log
- [winston-express](https://www.npmjs.com/package/winston-express) - Log winston in web
- [debug](https://www.npmjs.com/package/debug) - lightweight nodejs debugger

### Commands

```bash
$ npm init -y
$ npm i express debug winston express-winston cors shortid
$ npm i --save-dev @types/cors @types/express @types/debug @types/shortid source-map-support tslint typescript
$ npm run debug
```

### Configs

```bash
script:
    - "start": "tsc && node --unhandled-rejection=strict ./dist/app.ts"
    - "debug": "export DEBUG=* && npm run start"
tsconfig:
    - outDir: ./dist
```

### Bibliography

- DAOs (Data access objects)
- DTOs (Data transfer objects)
- Singleton many contained one instanciating class.

<!-- Ref
https://www.toptal.com/express-js/nodejs-typescript-rest-api-pt-1
https://www.toptal.com/express-js/nodejs-typescript-rest-api-pt-2 -->
