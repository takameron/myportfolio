---
title: 『Rocket Answer』のランキング機能
summary: 大学編入試験解答共有サービス『Rocket Answer』のランキング機能を実装
thumbnail: featured.png
tags:
- Ruby on Rails
- Web App
date: "2017-09-07T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: https://www.google.com/

links:
- icon_pack: fa-solid
  icon: fa-link
  name: Rocket Answer
  url: https://rocket-answer.com/
- icon_pack: fa-brands
  icon: fa-github
  name: GitHub
  url: https://github.com/KosenVenture/RocketAnswer
---

『Rocket Answer』というWebアプリケーションの、投稿者のランキング機能（[このページ](https://rocket-answer.com/ranking)）を実装しました。

Webアプリケーションについての知識は全くなかったため、Ruby on Railsの学習から始まりました。
既存のソースコードを解読して、やっとランキングが表示できるようになりましたが、レビューしていただくと、N+1クエリであることが判明したり、無駄に複雑なコードを書いていたことがわかりました。
ソースコードをリファクタリングしていただいて解説していただくと、いろいろとWebアプリに関する理解が深まりました。

開発環境をそろえるためにDockerを用いたので、Dockerについても触れる経験になりました。
また、データベースの扱い方、HTMLやCSS、セキュリティなど、Webアプリケーションに関するたくさんの知識を身につけられたので、貴重な経験になりました。


|  |  |
| ---- | ---- |
| 言語 | Ruby |
| フレームワーク | Ruby on Rails |
