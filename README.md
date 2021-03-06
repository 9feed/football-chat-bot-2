# football-chat-bot-2
Football chat bot build with NestJS framework

[![Build Status](https://travis-ci.org/tormozz48/football-chat-bot-2.svg?branch=master)](https://travis-ci.org/tormozz48/football-chat-bot-2)
[![codecov](https://codecov.io/gh/tormozz48/football-chat-bot-2/branch/master/graph/badge.svg)](https://codecov.io/gh/tormozz48/football-chat-bot-2)

## Install

1. Clone repository to your local filesystem from github:
```bash
git clone https://github.com/tormozz48/football-chat-bot-2.git
```
2. Install npm dependencies:
```bash
npm install
```
3. Set up all environment variables.
Also you can create `.env` file and fill them with environment variables described in "Configuration" section.

1. Launch application server:
```bash
npm start
```

## Configuration

Configuration is performed by modifying these environment variables:

* `TELEGRAM_BOT_TOKEN` - unique telegram bot token string
* `TELEGRAM_USE_PROXY` - true/false. If set to true then application will establish connection with telegram server via proxy.
* `TELEGRAM_PROXY_HOST` - proxy server host
* `TELEGRAM_PROXY_PORT` - proxy server port
* `TELEGRAM_PROXY_LOGIN` - proxy auth login
* `TELEGRAM_PROXY_PASSWORD` - proxy auth password
* `VK_TOKEN` - unique vk bot token string
* `DATABASE_URL` - connection url fot database. Used for production environment.

## Development

Configured commands:
* `npm run build` - compile TypeScript source code into js distributive.
* `npm run format` - perform code formatting via prettier tool.
* `npm start` - run application server
* `npm start:dev` - run application in "watch mode". Restart after source code chages.
* `npm start:debug` - run application in both "watch" and "debug" modes.
* `npm start:prod` - run application in production mode.
* `npm run lint` - perform code linting via tslint tool.
* `npm test` - run tests.
* `npm test:watch` - run tests in "watch mode".
* `npm test:cov` - run tests and calculate code coverage.

## Third-party software

* [NestJS](https://docs.nestjs.com/) - is a framework for building efficient, scalable Node.js server-side applications.
* [TypeORM](https://typeorm.io/#/) - TypeORM is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).
* [Telegraf](https://telegraf.js.org/#/) - modern Telegram Bot Framework for Node.js.
* [Handlebars](http://handlebarsjs.com/) - Minimal templating on steroids.
