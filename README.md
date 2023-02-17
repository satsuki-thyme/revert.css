# revert.css
CSS の全てのプロパティを初期化します。

## 目次
* revert.css  
  CSS 本体。
* revert.min.css
  CSS 本体。圧縮版。

## 使い方
* @import なり <link> なり 本編の CSS にペーストするなりして使用してください。

## 説明
* まず全てのプロパティを unset します。このことでよけいな設定が全てリセットされます。このままだと思いどおりの設定ができないので Chrome のユーザーエージェントスタイルシートを利用して revert （ブラウザの既定値）を適用しています。

## CDN
https://cdn.jsdelivr.net/gh/satsuki-thyme/revert.css@main/revert.min.css
