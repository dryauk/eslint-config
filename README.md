# @dryauk/eslint-config

[**ESLint**](https://eslint.org/) shareable config.

## Install

```bash
yarn add -D eslint prettier @dryauk/eslint-config
```

## Usage

The shareable config can be configured in your `package.json`.

```json
{
  "eslintConfig": {
    "extends": "@dryauk/eslint-config"
  }
}
```

If you don’t want to use `package.json`, you can use any of the [supported extensions](https://eslint.org/docs/user-guide/configuring/configuration-files#configuration-file-formats) to export a string, e.g. `.eslintrc`:

```json
{
  "extends": "@dryauk/eslint-config"
}
```
