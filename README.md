# GitBook-starter-pack
GitBook-starter-pack(試験版)は、node.jsの環境下で利用してください。

## 使い方
### パッケージのインストール

1. このリポジトリ(GitBook-starter-pack)をダウンロードする。
2. .zipファイルを解凍し、任意のディレクトリに配置する
3. ターミナル(Mac)、コマンドプロンプト(Windows)を起動し、下記を入力する

```
//GitBook-starter-packに移動する
cd ./desktop/GitBook-starter-pack

//package.jsに従って、GitBookの導入に必要なものをインストールする（しばらくするとインストールが開始され、node_modulesのフォルダが作成される）。
npm i

```

### Buildするファイルの準備
GitBook-starter-packのフォルダ内にある、book.js, README.md, SUMMARY.mdを開き確認する。

* book.js (コンテンツのタイトルや著者を記載)
* README.md (ページの紹介等を記載)
* SUMMARY.md（GitBook形式に変換する.mdのパスを記載）

### GitBookコマンドの実行

```
//SUMMARY.mdのパスに従って、.mdがhtmlに変換される
npm run build

//ローカルサーバーを起動し、Gitbookの動作を確認する
npm start

```



