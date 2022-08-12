# esbuild repro

### Steps

1. Download repro

2. Run `yarn start` (if `yarn` isn't installed, run `corepack enable` first)

3. Observe the warning


___


(if you uncomment the resolved path in `tsconfig.json` and comment the bare module specifier, `yarn start` runs without issues)
