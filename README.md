# Reproduction repo for RxJS with `node12` module resolution

```
yarn install
yarn build
```

```
main.mts:1:28 - error TS7016: Could not find a declaration file for module 'rxjs'. '/data/projects/various/rxjs-ts-node12/node_modules/rxjs/dist/cjs/index.js' implicitly has an 'any' type.
  Try `npm i --save-dev @types/rxjs` if it exists or add a new declaration (.d.ts) file containing `declare module 'rxjs';`

1 import { Observable } from "rxjs";
                             ~~~~~~


Found 1 error.
```
