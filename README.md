# typescript-eslint consistent-type-imports decorator bug

How to reproduce:
- `npm install`
- `npx eslint classB.ts`

Expected output:

No Problems

Actual output:
```
  1:1  error  Type import "ClassA" is used by decorator metadata  @typescript-eslint/consistent-type-imports

✖ 1 problem (1 error, 0 warnings)
   1 error and 0 warnings potentially fixable with the `--fix` option.
```