# ts-base

🪨 TypeScript base targetting Lambda and Browser

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

### ECMAscript versions

| Description | [Target](https://www.typescriptlang.org/tsconfig#target) | [Module](https://www.typescriptlang.org/tsconfig#module) |
| :--- | :--- | :--- |
| Browser (all except IE) | [ES6](https://kangax.github.io/compat-table/es6) | ES2020 |
| Node.js 14.x (Lambda runtime) | [ES2020](https://node.green/#ES2020) | ES2020 |

### Custom transformers

* [`ts-transform-paths`](https://github.com/zerkalica/zerollup/tree/master/packages/ts-transform-paths)
* [`typescript-transformer-append-js-extension`](https://github.com/Zoltu/typescript-transformer-append-js-extension)

## Test

```bash
npm test
```