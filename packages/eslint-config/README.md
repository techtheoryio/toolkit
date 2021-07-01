# TechTheory ESLint Config

**@tchthry/eslint-config** is the base ESLint configuration for all our projects. It also includes different sub-configuration (for example React).

## Installation

1. Install all peer dependencies
```bash
npx install-peerdeps --dev @tchthry/eslint-config
```

2. Install `@tchthry/eslint-config` as a dev dependency:
```bash
npm i @tchthry/eslint-config --save-dev
```
or
```bash
yarn add -D @tchthry/eslint-config
```

## Usage

In your `.eslintrc`, simply extend `@tchthry` (eslint will automatically resolve the module).
```json
// .eslintrc
{
  "extends": ["@tchtry"]
}
```

If you want to use the react configuration, extend `@tchtry/eslint-config/react`
```json
// .eslintrc
{
  "extends": ["@tchtry/eslint-config/react"]
}
