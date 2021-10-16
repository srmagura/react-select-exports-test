# react-select-exports-test

First, run `yarn install`. The run each of the three tests:

- `yarn test-cjs` (succeeds)
- `yarn test-mjs` (fails with import error)
- `yarn test-webpack` (fails with import error)

Now patch `node_modules/react-select/package.json` according to [my PR](TODO).

Rerun each test. Now all of them pass.
