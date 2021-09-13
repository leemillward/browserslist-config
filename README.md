### @leemillward/browserslist-config

[![npm version](https://badge.fury.io/js/%40leemillward%2Fbrowserslist-config.svg)](https://badge.fury.io/js/%40leemillward%2Fbrowserslist-config)

This package provides a base JS .eslintrc as an extensible shared config.

It extends the [eslint-config-airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base) ruleset with our own set of JS linting rules.

Many thanks to the work that the Airbnb and Just Eat teams have put in on creating their template for extension rules – we have liberally borrowed from their structure and documentation in creating this ruleset.

## Usage

### @leemillward/browserslist-config

The default export contains a browserlist array. Full information on browsrlist shareable configs [can be found in their README](https://github.com/browserslist/browserslist#shareable-configs).

To use this config, add the following to your package.json once you have installed the `@leemillward/browserslist-config` package.

```json
"browserslist": [
    "extends @justeat/browserslist-config-fozzie"
]
```
