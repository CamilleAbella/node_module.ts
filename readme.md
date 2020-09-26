# node_module.ts

## How to use this template ?

1. [Use this template](https://github.com/CamilleAbella/node_module.ts/generate).
2. Replace all `project-name` by your own project name.
3. Run `npm install` or `yarn install`.
4. Add your own packages and keep existant dev packages.

## Remove unit test system (jest) ?

1. Remove this files from project and from `prettier` script in package.json:
    - `jest.config.js`
    - `test.js`
2. Remove `test` script from package.json and from `build` script.
3. Run `npm remove --purge jest`.

## Use npm CLI instead of yarn ?

¯\_(ツ)_/¯   
bad move.

## Some detail

- The `prepublish` script runs prettier and tsc.
- Think to fill description and keywords in package.json.