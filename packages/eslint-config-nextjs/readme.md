# Installation

```bash
npm install --save-dev eslint prettier @marolint/eslint-config-nextjs
```

# Usage

Add the following to your `.eslintrc` file:

```json
{
  "extends": ["@marolint/eslint-config-nextjs"]
}
```

And add the following to your `.prettier.config.js` file:

```js
/** @type {import('prettier').Options} */
module.exports = {
  extends: ["@marolint/eslint-config-nextjs/prettier.config"]
}
```
