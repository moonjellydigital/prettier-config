# Prettier Config

A shareable [Prettier](https://prettier.io) config.

## Installation

npm:

```
npm install --save-dev @moonjellydigital/prettier-config
```

yarn:

```
yarn add -D @moonjellydigital/prettier-config
```

bun:

```
bun add -D @moonjellydigital/prettier-config
```

## Usage

Add to your `package.json`:

```json
{
    "prettier": "@moonjellydigital/prettier-config"
}
```

Import in a `.prettierrc.js` file if you want to override settings:

```javascript
import config from "@moonjellydigital/prettier-config";

export default {
    ...config,
    semi: false,
};
```
