# @zlatjs/style-config

## Installation

```
$ npm i @zlatjs/stylelint-config
```

## Usage

package.json

```
"scripts": {
    ... ,
    "stylelint": "stylelint '{SCSS URL}'"
  },
```



.stylerc.json

```
{
  "extends": "@zlatjs/stylelint-config",
  "settings": {
    "import/resolver": {
      "node": {
        "paths": "./src"
      }
    }
  }
}
```
