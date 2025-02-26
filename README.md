# [@wagtail/stylelint-config-wagtail](https://www.npmjs.com/package/@wagtail/stylelint-config-wagtail) [<img src="https://raw.githubusercontent.com/wagtail/stylelint-config-wagtail/main/.github/stylelint-logo.svg?sanitize=true" alt="Stylelint" width="90" height="90" align="right">](https://stylelint.io)

[![@wagtail/stylelint-config-wagtail on npm](https://img.shields.io/npm/v/@wagtail/stylelint-config-wagtail.svg)](https://www.npmjs.com/package/@wagtail/stylelint-config-wagtail)

> Shareable stylelint config for CSS and SCSS, following Wagtail’s code style.

## Usage

Our default export contains all of our Stylelint rules, along with specific plugins for SCSS syntax.

1. Run `npm install stylelint @wagtail/stylelint-config-wagtail --save-dev`
2. Add `"extends": "@wagtail/stylelint-config-wagtail"` to your `.stylelintrc`

## Links

- [Stylelint](https://stylelint.io/)
- [stylelint-config-recommended-scss](https://github.com/stylelint-scss/stylelint-config-recommended-scss)
- [stylelint-config-prettier-scss](https://github.com/prettier/stylelint-config-prettier-scss)

## Contribution Guidelines

### Install

- Required [Node](https://nodejs.org)
- We recommend using [nvm](https://github.com/creationix/nvm)
- Clone the project on to your computer
- Run `nvm install` to ensure you have the correct Node version
- Run `npm install` to install project dependencies
- Ensure your editor is set up to use [editorconfig](https://editorconfig.org/), [Prettier](https://prettier.io/), [Eslint](https://eslint.org/) and [Stylelint](https://stylelint.io/)

### Development

- Run `nvm use` to set Node to the correct version
- Run tests via `npm run test`
- Run linting via `npm run lint`
- Run preflight checks before commiting final code via `npm run preflight`
- Note: When working with the rule set, only modify the `index.js` file, not the `.eslintrc` file as it is for local linting only
