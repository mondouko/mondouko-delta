# mondouko-delta

[![Jekyll CI](https://github.com/mondouko/mondouko-delta/actions/workflows/jekyll.yml/badge.svg)](https://github.com/mondouko/mondouko-delta/actions/workflows/jekyll.yml)

## About me
問答庫で覚えたい、知ってほしいと思う情報を**アウトプットを重視して**お伝えしています。
<https://mondouko.com/>

## 開発の目的

現状、mondouko-gammaという開発コードで、非公開レポジトリにて開発が進んでいます。

gammaのソースコードはすべて生JSとhtml,CSSのみで書かれており、様々な問題がありました。

また、Netlifyを使用していましたが、無料プランでできることに限界がありました（ex. BASIC認証ができない、そもそも複数ユーザーでの管理を想定しておらず、Netlifyに関しては一つのアカウントでログインが必要になっている、etc...）

そこで、deltaでは以下の点を重視して開発しています。

1. 階層整理
1. 記事投稿、管理をスマートに
1. サイト自体の軽量化 
1. Orgを使って、GitHubアカウント（と少しのGitHub知識）があれば記事作成可能

## 仕様
GitHub Pages + Jekyllで運用されています。

## 開発メンバー
  - [植物好き（Mondouko_team）](https://github.com/mondouko_team) gammma開発(1人で!?)
  - [0505Keitan](https://github.com/0505Keitan) deltaバックエンド
  - [まっさー🐍（massasnake）](https://github.com/massasnake) deltaフロントエンド、進捗管理
  - 開発メンバー募集中


## ライター
　- Coming Soon...

---

## 問答庫でできること

### タイピング
答えが隠された状態でタイピングが行えます。スペースキーを押すことで答えが表示され、正解するまで次の問題に進めません。この仕組みにより、学習意欲の低い分野の勉強もはかどるのかもしれません。
<https://mondouko.com/typing>

### クイズ
多くの記事はクイズを含んでいます。クイズの形式は入力式クイズ、択一式クイズ、〇×クイズがあります。重要な語句は隠すこともできます。

現サイトステータス[![Netlify Status](https://api.netlify.com/api/v1/badges/db5af307-3f81-4653-a6c2-8045bfdb7da2/deploy-status)](https://app.netlify.com/sites/mondouko-gamma/deploys)

---

## ライター向け 開発情報

### ドキュメント
- [記事ジェネレーター使用方法](./)
- [記事追加・管理方法](./)