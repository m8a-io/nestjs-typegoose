---
id: install
title: Installation
---

Welcome to the nestjs-typegoose. The Typegoose module/ plugin for NestJS.

This project is a fork of the original [nestjs-typegoose](https://github.com/kpfromer/nestjs-typegoose) and credit where credit is definitely due, practically all of the coding was done by [Kyle Pfromer](https://github.com/kpfromer). Many thanks to him for putting this module together. This project aims to continue that work and to maintain the plugin for the long run. 

:::note
This assumes you have a nestjs project to work with. If you don't it is recommended that you use the [nestjs cli](https://docs.nestjs.com/cli/overview) to jump start an example project to get started using `nestjs-typegoose`.
:::

Using `npm`:

`npm install --save @m8a/nestjs-typegoose`

Using `yarn`:

`yarn add @m8a/nestjs-typegoose`

:::note
This package follows the major versions of Typegoose and the peer dependencies accordingly, since `@typegoose/typegoose` version 10. So, if you need to use older versions of Typegoose, you need to use older versions of nestjs-typegoose that match it too. For example, if you need to use Typegoose v10, you need to use nestjs-typegoose v10.
:::
## Peer Dependencies

The latest version of nestjs-typegoose (v13) requires a few peer dependencies to be installed for things to work. You need to install the following:

- `@typegoose/typegoose` v13+
- `@nestjs/common` v10, v11 or v12
- `@nestjs/core` v10, v11 or v12
- `mongoose` v9+

- be sure you have TypeScript 5.2 or higher also installed
- Node.js v20.19+ is required. NestJS v12 additionally requires Node.js v20.19+ or v22.12+ (Node.js v21 and v22.0–v22.11 are not supported), see the [NestJS migration guide](https://docs.nestjs.com/migration-guide)

Using `npm`:

`npm install --save @typegoose/typegoose @nestjs/common @nestjs/core mongoose`

Using `yarn`:

`yarn add @typegoose/typegoose @nestjs/common @nestjs/core mongoose`

Using `pnpm`:

`pnpm install --save @typegoose/typegoose @nestjs/common @nestjs/core mongoose`

:::note
If you are upgrading from older versions, please also check the [migration guides for Typegoose](https://typegoose.github.io/typegoose/docs/guides/migration/migrate-12).  
:::

Now you are [ready to start](usage.md) using `nestjs-typegoose`!