# no-named-test-function

requires no function variable in it block

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `no-named-test-function`:

```
$ npm install no-named-test-function --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `no-named-test-function` globally.

## Usage

Add `it-block` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "it-block"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "it-block/rule-name": 2 // 2 for error or 1 for warn 
    }
}
```

## Supported Rules

* Fill in provided rules here





