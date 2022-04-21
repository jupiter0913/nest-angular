# angular-nest

Simple web app template with Angular v13 + NestJS v8 + ng-openapi-gen.

Deployable on Heroku (with/without Docker) and other [Docker based servers](https://github.com/mugifly/angular-nest/wiki#deployments).

[![Build](https://github.com/mugifly/angular-nest/actions/workflows/build.yml/badge.svg?event=push)](https://github.com/mugifly/angular-nest/actions/workflows/build.yml)

---

## Key Elements

- Angular -- for Frontend app.
- NestJS -- for Backend app.
- ng-openapi-gen -- for API Client generation.
- Docker -- for Production environment.
- Karma + Jasmine -- for Unit testing of Frontend (with Puppeteer + Headless Chromium)
- Jest -- for Unit testing of Backend
- GitHub Actions -- for CI

---

## Quick Start

### Deployment on Heroku

This app supports deploying as a production environment to Heroku.
Also you don't have to do the build process locally or in CI, so it's easy.

Try it now from the Heroku Button:<br>
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Or, this app can also be deployed to Container stack on Heroku, as Docker based application.

Please see [Deploy to Heroku](https://github.com/mugifly/angular-nest/wiki/Deploy-to-Heroku) page on the wiki to learn more.

### Deployment on Docker based servers

https://github.com/mugifly/angular-nest/wiki/#Deployments

### Development on Local

Before you start, you should install the following software:

- Git

- Node.js v16+

- Visual Studio Code

Then, please execute as the following in your terminal:

```
$ git clone git@github.com:mugifly/angular-nest.git
$ cd angular-nest/

$ npm install

$ npm run start:dev
```

After that, open the web browser and navigate to `http://localhost:4200/`.

Also, when you edit the frontend source-code, auto-reloading applies it to your browser immediately.

---

## Testing

### Unit test for Frontend

Requirements: Google Chrome and [dependencies of Puppeteer](https://github.com/puppeteer/puppeteer/blob/main/docs/troubleshooting.md)

```
$ npm run test -w client
```

### Unit test for Backend

```
$ npm run test -w server
```

### E2E test

#TODO

---

## License and Author

This project is released under the [CC0 1.0 Universal](https://github.com/mugifly/angular-nest/blob/master/LICENSE) license, by Masanori Ohgita ([mugifly](https://github.com/mugifly)).

Therefore, a copyright notice is NOT required.
Feel free to use or copy it to your project :)

NOTE: However, some sample codes and documents (e.g. client/README.md and server/README.md) that generated by Angular CLI or Nest CLI may be based on their respective licenses.
