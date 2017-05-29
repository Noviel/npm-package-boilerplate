# NPM Package Boilerplate

## Features

- babel (env and stage-2 presets)
- eslint (based on create-react-app config)
- jest

## Install
1. 
```sh
git clone git@github.com:Noviel/npm-package-boilerplate.git my-awesome-npm-package
cd my-awesome-npm-package
```
2. Remove `.git` directory

3. `yarn install` or `npm install`

### Usage

1. Write code in `src` directory
2. `npm run build` or `yarn build`
3. `npm publish`

#### Scripts

- test - run jest
- lint - run eslint
- build - build `src` to `dist`
- major-release - update major version and publish
- minor-release - update minor version and publish
- patch-release - update patch version and publish