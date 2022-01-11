# vue-site

## プロジェクトの立ち上げ
```
npm install
```

### 開発者サーバの実行
```
npm run serve
```

### デプロイ準備のためのコマンド
```
npm run build
```

### ドキュメント詳細

[Vuejs公式サイト](https://cli.vuejs.org/config/).

# 開発過程

# ディレクトリ

```
C:.
│  .browserslistrc
│  .gitignore
│  babel.config.js
│  package-lock.json
│  package.json
│  README.md
│
├─node_modules
│
├─public
│      favicon.ico
│      index.html
│
└─src
    │  App.vue
    │  main.js
    │
    ├─assets
    │      logo.png
    │
    ├─components
    │  │  HelloWorld.vue
    │  │
    │  └─layout
    │          Navbar.vue
    │
    ├─router
    │      index.js
    │
    ├─store
    │      index.js
    │
    └─views
        │  About.vue
        │  Home.vue
        │  LogIn.vue
        │  SignUp.vue
        │
        └─dashboard
                DashBoard.vue
                MyAccount.vue
```