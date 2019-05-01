# React-Ts-Practice
ReactでTypeScriptを使ってみる

## 参考記事
- [TypeScript Deep Dive](https://typescript-jp.gitbook.io/deep-dive/browser)
- [TypeScriptでReactを書く – webpackを使った開発環境の構築方法](https://github.com/basarat/react-typescript)  
上記記事を参考にカスタマイズ

## Build Setup
``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:8080
$ npm run dev

# build for production and launch server
$ npm run build

# Lint Fix
$ npm run lint
```


## Vscode設定
vscodeの場合、setting.jsonに以下の設定も忘れないこと
``` 
"eslint.validate": [
  "javascript",
  "javascriptreact",
  {
    "language": "typescript",
    "autoFix": true
  },
  {
    "language": "typescriptreact", 
    "autoFix": true 
  }
```
