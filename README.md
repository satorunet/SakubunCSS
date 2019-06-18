# SakubunCSS (横書きバージョン)
sample: http://satoru.net/sakubun/
![SakubunCSS Sample Image](https://raw.githubusercontent.com/satorunet/SakubunCSS/master/sample.png)

## 概要

いわゆる作文や原稿用紙風を実現するCSSです。

※fork元の縦書きの横書きバージョンです。

https://github.com/cawpea/SakubunCSS

## 使い方
sakubun.cssを読み込み、
class=sakubunb内に本文。

<style src="sakubun.css"></style>
<div class="sakubun">
<p>
吾輩は猫である。<br>
夏目漱石<br>
</p>
</div>


## 注意点

本CSSは不完全のため、以下の点に注意すること（誰か治せるならプルリクください）

<s>- 作文の領域内で横スクロールが発生した場合に罫線が途切れる</s>
- ふりがな(ruby)を使用した場合にブラウザごとに位置が多少ずれる
