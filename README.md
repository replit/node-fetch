**NEW!** Want to just `require` any ES module with zero setup? Try [`esm-hook`](https://github.com/proteriax/esm-hook).


# node-fetch-commonjs


[node-fetch](https://github.com/node-fetch/node-fetch) but in CommonJS format. This module is built from `node-fetch` directly.

## Version check

![Latest upstream version](https://img.shields.io/npm/v/node-fetch?label=latest%20upstream)
![Current upstream version](https://img.shields.io/badge/current%20upstream-v3.2.10-brightgreen)

## Differences

1. You can `require("node-fetch-commonjs")` directly.
2. You will not see the `ExperimentalWarning: stream/web is an experimental feature` warning.
3. It works on older Node.js versions that don’t support [requiring built-in modules with a `node:` prefix](https://github.com/node-fetch/node-fetch/issues/1367).

## Build

```bash
yarn
./build.js # Output to `lib` folder
```

## Install

```bash
yarn add node-fetch-commonjs
```
