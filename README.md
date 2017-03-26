# eslint-plugin-prefer-class-properties

Prefer class properties instead of defining them in the constructor()

> This plugin/rule is lifted from [eslint-plugin-shopify](https://github.com/Shopify/eslint-plugin-shopify)

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-prefer-class-properties`:

```
$ npm install eslint-plugin-prefer-class-properties --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-prefer-class-properties` globally.

## Usage

Add `eslint-plugin-prefer-class-properties` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "prefer-class-properties"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "prefer-class-properties/prefer-class-properties": 2
    }
}
```

## Rule Documentation

See the [prefer-class-properties documentation here](./docs/rules/prefer-class-properties.md) for examples and settings.
