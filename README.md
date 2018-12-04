# TS helper bug

Steps to reproduce:

1. Install dependencies with `yarn install`
2. Run tsc via `yarn build`
3. Notice badly hoisted variable `var _b` in generated output
