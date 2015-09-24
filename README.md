# Pentaho Javascript Coding Style

Pentaho enforces Javascript coding style through the use of [JSCS](http://jscs.info).

This packages provides a "pentaho" preset.

## Installation

1. Install [JSCS](http://jscs.info/overview#installation):
2. Install [jscs-preset-pentaho](https://www.npmjs.com/package/jscs-preset-pentaho);
3. Create a .jscsrc where you need it;
4. Set "preset" property to "pentaho":

```json
{
    "preset": "pentaho"
}
```

**Note:** Currently jscs-preset-pentaho needs to be installed locally in the project, with ```npm install jscs-preset-pentaho```. There is a PR (https://github.com/jscs-dev/node-jscs/pull/1807) to allow global node modules (so it can be installed only once with ```npm install -g jscs-preset-pentaho```).
