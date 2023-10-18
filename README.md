# revert.css
CSS の全てのプロパティを初期化します。

## 目次
- revert.css: CSS 本体
- revert.min.css: CSS 本体（圧縮版）

## 使用目的の示唆
- ブログの中で素の CSS で表示したいのにブログのテーマになっている CSS が効いて装飾されてしまうことがあります。そんなときにこの revert.css を当てれば初期化された上で自由に自作 CSS の表示を公開することができます

## 使い方
- @import なり <link> なり 本編の CSS にペーストするなりして使用してください
- 目的の箇所を <div class="revert"> として囲ってください

## 説明
- まず全てのプロパティを unset します。このことでよけいな設定が全てリセットされます。このままだと思いどおりの設定ができないので Chrome のユーザーエージェントスタイルシートを利用して revert （ブラウザの既定値）を適用しています

## CDN
https://cdn.jsdelivr.net/gh/satsuki-thyme/revert.css@main/revert.min.css
