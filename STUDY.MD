# README

## AtomでMDファイルのプレビューを行う
- Ctrl + Shift + M

## 開発環境
- npm
- ライブラリ
    - webpack
    - vue.js
    - vue-cli

## vueコマンド

- プロジェクト作成
```
vue create {Project_Name}
```

- GUI起動
```
vue ui
```


## npm操作
### 使用したコマンドなどをまとめる

- モジュールのインストール
```
npm install {lib} --save
```

- モジュールの一覧取得
```
npm ls
```

- 単体インストール(dev環境へのモジュールインストール、UNMET DEPENDENCYの解消)
```
npm i -D {lib}
```

- モジュール間の依存関係解消
```
rm -r node_modules
npm cache clean --force
```
