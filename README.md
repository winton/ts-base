# ts-base

🪨 TypeScript base targeting server and browser

## Install

```bash
git clone git@github.com:winton/ts-base.git
cd ts-base
npm install
```

## Watch

```bash
npm run watch
```

## Build

```bash
npm run build
```

## Test

```bash
npm test
```

#### Versions

| Environment | [Target](https://www.typescriptlang.org/tsconfig#target) | [Module](https://www.typescriptlang.org/tsconfig#module) |
| :--- | :--- | :--- |
| Server (Node.js 16.x) | [ES2021](https://node.green/#ES2021) | ES2020 |
| Browser (all except IE) | [ES6](https://kangax.github.io/compat-table/es6) | ES2020 |

#### Transformers

| Transformer | Description |
| :--- | :--- |
| [`ts-import-transformer`](https://github.com/winton/ts-import-transformer) | ↔️ Transform import paths to work on client and server environments |