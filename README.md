# `@avv/eslint-plugin`

## Install

For projects using Typescript. Therefore, the plugin uses the [@typescript-eslint/parser](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/parser).
To work correctly, you need to install the required dependencies::

```sh
npm i -D @avv/eslint-plugin eslint eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks eslint-config-airbnb eslint-config-airbnb-typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin
```

#### To view required dependencies:

```sh
npm info "@avv/eslint-plugin@latest" peerDependencies
```

## Using

```json
{
  "plugins": [
    "@avv"
  ],
  "extends": [
    "plugin:@avv/typescript"
  ]
}
```

##### Note: Make sure that ```parserOptions``` uses ```tsconfig``` of the project:
```json
{
  "parserOptions": {
    "project": ["./tsconfig.json"]
  }
}
```
