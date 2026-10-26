# Prettier Config

A shareable [Prettier](https://prettier.io) config.

## Installation

npm:

```shell
npm install --save-dev @moonjellydigital/prettier-config
```

pnpm:

```shell
pnpm add -D @moonjellydigital/prettier-config
```

yarn:

```shell
yarn add -D @moonjellydigital/prettier-config
```

bun:

```shell
bun add -D @moonjellydigital/prettier-config
```

## Usage

Add to your `package.json`:

```json
{ "prettier": "@moonjellydigital/prettier-config" }
```

Import in a `.prettierrc.js` file if you want to override settings:

```javascript
import config from '@moonjellydigital/prettier-config' with { type: 'json' };

export default { ...config, semi: false };
```
