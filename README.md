# Custom Create React App TypeScript Template

> Custom Create React App TypeScript Template

[![NPM Version](https://img.shields.io/npm/v/@phatnguyenuit/cra-template-typescript)](https://www.npmjs.com/package/@phatnguyenuit/cra-template-typescript) 
[![NPM License](https://img.shields.io/npm/l/@phatnguyenuit/cra-template-typescript)](https://github.com/phatnguyenuit/cra-template-typescript/blob/master/LICENSE) 
[![NPM Downloads](https://img.shields.io/npm/dt/@phatnguyenuit/cra-template-typescript)](https://www.npmjs.com/package/@phatnguyenuit/cra-template-typescript) 
[![Dependency Status](https://img.shields.io/librariesio/release/npm/@phatnguyenuit/cra-template-typescript)](https://www.npmjs.com/package/@phatnguyenuit/cra-template-typescript)

## Using

```shell
$ create-react-app <app_name> --template @phatnguyenuit/typescript
```

## Features

- Inherit from package [`cra-template-typescript`](https://www.npmjs.com/package/cra-template-typescript)
- Configure `eslint` with `prettier`
- Configure [`husky`](https://typicode.github.io/husky/#/)
- Configure [`lint-staged`](https://github.com/okonet/lint-staged#readme)
- Configure [`prettier`](https://prettier.io/)
- Configure [`commitlint`](https://commitlint.js.org/)
- Configure [`release-it`](https://github.com/release-it/release-it)
- Add default `jest` test coverage options
- Configure sample GitHub actions including test, release and deploy
- Provide sample vscode snippets


## Configure

- Update [`README`](./README.md)
  - Replace `:user` and `:repository` by your own.
  - Navigate to [Codecov](https://codecov.io) login and get `Repository Upload Token` for your repository.
  - Replace `:TOKEN` with your markdown Codecov badge.
- Add repository secrets `DEPLOY_ACCESS_TOKEN` generated from `https://github.com/settings/tokens/new` with the first four checked options of `repo`.