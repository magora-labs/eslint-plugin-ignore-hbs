# eslint-plugin-ignore-hbs

This plugin ignores `{{#block}}` `{{/block}}` and `{{variable}}` existence in `.hbs`, `.handlebars` and `.mustache` files as they break ESLint.

## Installation

You'll first need to install [ESLint](http://eslint.org):

```bash
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-ignore-hbs`:

```bash
$ npm install eslint-plugin-ignore-hbs --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-ignore-hbs` globally.

## Usage

Add `ignore-hbs` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": [
    "ignore-hbs"
  ]
}
```
