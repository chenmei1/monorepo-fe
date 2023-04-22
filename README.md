# Monorepo

[Better practice npm Package Design in Monorepo](https://www.rustc.cloud/monorepo-pkg) with [pnpm](https://pnpm.io/, deploying into [Vercel](https://vercel.com/).

## Quick Start

Preinstall

```bash
$ npm i -g pnpm
$ pnpm -v # should >= 6.20.0
```

Install dependencies

```bash
$ pnpm install
```

### Apps

Preview:
- [Vue 3 Cli App](https://monorepo-vue3-cli-app.vercel.app/)



#### Node.js App

```bash
$ pnpm --filter "node-app" start
```


## Packages Development

### packages/shared

```bash
$ pnpm --filter "@infras/shared" dev
```

### packages/ui

```bash
$ pnpm --filter "@infras/ui" dev
```
