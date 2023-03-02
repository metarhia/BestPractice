# Metarhia best practice for relative technologies

| Purpose        | Recommended                   | Allowed        | Unwanted                  | Unacceptable              |
| -------------- | ----------------------------- | -------------- | ------------------------- | ------------------------- |
| Applied code   | JavaScript                    | Python, LISP   | TypeScript .ts, Java, C#, Go | Ruby, PHP, VB          |
| Typings        | Metaschema, TypeScript .d.ts  |                | JSDoc                     |                           |
| Linters        | Eslint, prettier, TypeScript  |                |                           | JSHint                    |
| Runtime        | Node.js                       | Bun            |                           | Deno                      |
| Server OS      | CentOS, Fedora, FreeBSD, Arch | Suse, RHEL, Debian | Ubuntu                | Windows                   |
| Contracts      | Metaschema                    | OpenAPI, Swagger | SOAP, XML, gRPC, protobuf, GraphQL |                |
| Cryptography   | Node.js crypto, openSSL       |                | bcrypt, argon2            |                           |
| JS helpers     |                               | Core-js        | lodash, underscore        | jQuery, cheerio           |
| Frameworks     | Fastify                       |                | Nest.js                   | connect, express, koa     |
| App server     | Impress application server    |                | Loopback                  | Apollo server, IIS        |
| Low-code       | Lowscript                     |                |                           | Node-RED                  |
| Auth           | OAuth 2.0 + GoF: strategy     |                |                           | passport, JWT             |
| Templates      | Template strings, tickplate   |                |                           | EJS                       |
| CPU intensive  | C, Rust, C++, WASM            |                | Java, C#                  |                           |
| SQL database   | Postgres                 | SQLite, cassandra, DynamoDB, Elastic | MySQL, Oracle, DB2, MariaDB | MS SQL |
| NoSQL          | Redis, Kafka                  | Clickhouse     | Memcached                 | Neo4j, MongoDB            |
| CI             | Github Actions                | Travis         | Jenkins                   |                           |
| Process man.   | Docker                        | k8s, terraform, ansible |                  | Pm2, forever              |
| CDN            | Cloudflare, Nginx             |                |                           |                           |
| Frontend       | React, Vue.js, Web components | Angular        |                           |                           |
| Modules        | CommonJS, ESM, vm, metavm     |                | Inversify                 |                           |
| Tests          | assert, node:test, Metatests  |                |                         | Mocha, Jest, Jasmine, Karma |
| CMS            | Blogger                       | Wix            |           | Magento, Wordpress, Joomla, Drupal, Tilda |
| Multithreading | worker_threads, child_process |                |                           | cluster                   |
| Async context  | closures, collections, async_hooks |           |                           | zone.js                   |
| Date and Time  | ES6 + Intl                    |                |                           | moment.js                 |
| HTTP Client    | Node.js fetch, undici         |                |                          | axios, node-fetch, request |
| Management     | Github, Gitlab (projects, issues, kanban) | |                              | Jira, Trello              |
| Repo hosting   | Github, Gitlab, npm           |                |                           | Bitbucket                 |
| Work chat      | Telegram                      |                | Discord                   | Teams, Slack              |
| Mobile         | Kotlin, Swift, PWA            |                |                           |                           |
| File storage   | S3, MinIO                     |                |                           |                           |
| Serverless     |                               | Cloudflare     | | AWS Lambda, Google cloud functions, Azure functions |
| ORM & QBuilder | Knex, metasql                 | Prisma         |                        | TypeORM, Sequelize, Mongoose |
| Interactive    | Websocket, metacom, npm:ws    |                | jstp                      | socket.io                 |
| Async code     | Native Promise, async/await   | Rx.js, EventEmitter |                      | Async.js, bluebird, q, co |
| Build          | Webpack                       |                | Gulp                      |                           |
| Visualization  | D3                            |                |                           |                           |
| Message Queue  | Redis                         | RabbitMQ       |                           | Azure, AWS SQS            |
| Mailing        |                               | nodemailer     |                           |                           |
| Security       | npm audit, snyk               |                |                           |                           |
| Distributed    | SQRS, Event Sourcing, CRDT    | OT             | Akka                      |                           |
| Logging        | metalog, pino                 |                | winston                   |                           |
| Telemetry      | new relic                     |                |                           |                           |
| DSL            | markdown, metavm, json5       |                |                           |                           |
| Design         | Figma                         |                |                           |                           |
| Utilities      | metautil                      |                |                         | mkdirp, zone.js, node-fetch |
