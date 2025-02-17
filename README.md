# ブロック崩しゲーム

## 概要
このプロジェクトは、JavaScript と HTML5 Canvas を使用したシンプルなブロック崩しゲームです。プレイヤーはパドルを左右に動かしてボールを跳ね返し、ブロックをすべて破壊するとクリアとなります。

## デモ
ゲームの動作を確認したい場合は、下記リンクを押下してください。  
スマートフォンでは、ブロック崩しのパドルは操作できませんが、ゲーム画面は表示されます。   
[動作確認リンク](https://crux-daime.github.io/breakout-game/breakout-game.html)

## 使用技術
- HTML5 Canvas
- JavaScript
- CSS

## ダウンロード方法
1. `breakout-game.html`ファイルをダウンロード
2. ダウンロードしたファイルをブラウザで開くだけでプレイできます。

## 遊び方
1. ゲーム開始ボタンをクリックするとゲームが始まります。
2. 左右の矢印キーでパドルを操作します。
3. すべてのブロックを破壊するとクリアです。
4. ボールを落とすとライフが減り、すべてのライフがなくなるとゲームオーバーです。

## カスタマイズ方法

### ボールの大きさ変更
`ballRadius` の値を変更するとボールの大きさを変更できます。
```js
let ballRadius = 10;
```

### パドルのサイズ変更
`paddleWidth` の値を変更することでパドルの幅を調整できます。
```js
const paddleWidth = 75;
```
などその他コメントにいくつか書いてますが、数値を変更するとゲーム設定を変えることができます。

