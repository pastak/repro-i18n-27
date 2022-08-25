# Reproduce

```
% npm install
% npm exec tsc --noEmit index.ts
node_modules/i18n-js/typings/helpers/index.d.ts:3:10 - error TS2305: Module '"./expandRoundMode"' has no exported member 'expandRoundMode'.

3 export { expandRoundMode } from "./expandRoundMode";
           ~~~~~~~~~~~~~~~

node_modules/i18n-js/typings/helpers/index.d.ts:4:10 - error TS2305: Module '"./formatNumber"' has no exported member 'formatNumber'.

4 export { formatNumber } from "./formatNumber";
           ~~~~~~~~~~~~


Found 2 errors in the same file, starting at: node_modules/i18n-js/typings/helpers/index.d.ts:3
```
