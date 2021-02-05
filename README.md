# Custom prettier-config for react/next projects

## Prettier configuration

```
{
  "arrowParens": "always",
  "bracketSpacing": true,
  "endOfLine": "lf",
  "htmlWhitespaceSensitivity": "css",
  "insertPragma": false,
  "jsxBracketSameLine": false,
  "jsxSingleQuote": false,
  "printWidth": 100,
  "proseWrap": "preserve",
  "quoteProps": "as-needed",
  "requirePragma": false,
  "semi": true,
  "singleQuote": false,
  "tabWidth": 2,
  "trailingComma": "es5",
  "useTabs": false
}
```

# Usage

## Install the package

```
npm i @milindsoorya/prettier-config --save-dev

```

## use it in the project

```
{
  "name": "projectname",
  "version": "0.1.0",
   "prettier": "@milindsoorya/prettier-config",
"devDependencies": {
    "@milindsoorya/prettier-config": "^1.0.1",
  }
}
```
