# Installation

```bash
npm install --save-dev eslint prettier @marolint/eslint-config-core
```

# Usage

Add the following to your `.eslintrc` file:

```json
{
  "extends": ["@marolint/eslint-config-core"]
}
```

And add the following to your `.prettier.config.js` file:

```js
/** @type {import('prettier').Options} */
module.exports = {
  extends: ["@marolint/eslint-config-core/prettier.config"]
}
```
