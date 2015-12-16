# eslint-plugin-sinon

ESLint rules for [Sinon.JS](http://sinonjs.org/).

## Install and configure

This plugin requires ESLint `1.4.1` or later.

`npm install --save-dev eslint-plugin-sinon`

Then add a reference to this plugin and selected rules in your eslint config:

```json
{
  "plugins": [
    "sinon"
  ],
  "rules": {
    "sinon/no-fakes": 2
  }
}
```
See [Configuring Eslint](http://eslint.org/docs/user-guide/configuring) on [eslint.org](http://eslint.org) for more info.
