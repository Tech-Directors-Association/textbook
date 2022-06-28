# はじめに

このドキュメントはTech Director's Associations のメンバーにより作成される「テクニカルディレクション」に関する知識やベストプラクティスなどを共有・ストックするドキュメントです。

# 記述方法
## インストール

本ドキュメントは、ドキュメント静的サイトジェネレーターである [docsify](https://docsify.js.org/#/) を利用して作成されています。

ドキュメントの編集を開始するにあたり docsify-cli のインストールを推奨しています。

| npmの利用にはnode.jsのインストールが必要です。

`npm i docsify-cli -g`

docsify-cliをインストールするとdocsifyコマンドが利用可能になります。

`docsify -v`

## 起動

ローカルでdocsifyを起動するには以下のコマンドを実行し、ブラウザで `http://localhost:3000` にアクセスするとプレビューがでいます。

`docsify serve docs`

| 3000番ポートが別のプロセス、利用されている場合自動的に別のポートで立ち上がります。

### pythonで起動する

docsify-cliをインストールせず、pythonでプレビューする場合は以下のコマンドを実行し `http://localhost:3000` にアクセスするとプレビューがでいます。

`python -m http.server 3000 -d ./docs/`

## 記述方法

docsifyはmarkdownで記述することができます。
記述方法などは公式ドキュメントをご覧ください。

[Docsify公式ドキュメント](https://docsify.js.org/#/)




