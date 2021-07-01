# TechTheory Prettier Config

**@tchthry/prettier-config** exposes our [prettier](https://prettier.io) configuration.

## Installation

1. Install `@tchthry/prettier-config` as a dev dependency:
```bash
npm i @tchthry/prettier-config --save-dev
```
or
```bash
yarn add -D @tchthry/prettier-config
```

## Usage

In your `.prettierrc`, simply export this packages name as a string.

```json
// .prettierrc
"@tchthry/prettier-config"
```

or reference it in your `package.json`

```json
{
  "name": "my-package",
  "version": "67.0.1",
  "prettier": "@tchthry/prettier-config"
}
```
