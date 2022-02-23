---
layout: post
title:  "Setup pages and Jekyll!"
date:   2022-02-24 07:37:00 +0900
categories: jekyll
---
PagesとJekyllのセットアップ終了。
ちょっと苦戦したけど、ネットで検索してどうにか動くようになる。

Jekyllのインストール後にエラー(`require': cannot load such file -- webrick (LoadError`)が出て起動しなかった。

[ Jekyll serve fails on Ruby 3.0 #8523 ][jekyll-repo]

上記の記事を参考にして、下記コマンドの実行で解決。

`bundle add webrick`

先人の情報共有に感謝。

その他、簡単にページの記載をデフォルトから修正。

これから色々勉強して書いていきたい。

[jekyll-repo]:https://github.com/jekyll/jekyll/issues/8523

