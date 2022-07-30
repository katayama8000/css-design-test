### px em 違い
- px --- 絶対的な単位
- em(エム) --- 相対的な単位
  - emは使われている書体（フォント）や、CSSで指定している文字の大きさによって変化する相対単位。例えば文字の大きさを10pxにしていたなら、1emは10pxということになり、30pxを指定していたなら、1emは30pxに変化する。

### block inline inline-block 
- block → 要素が横までいっぱいに広がり、縦に並んでいく
  - p
  - div
  - ul
  - h1~h6
- inline → 要素が平ぺったく横に並んでいく
  - a
  - span
  - img
- inline-block → blockとinlineの中間

https://saruwakakun.com/html-css/basic/display

### padding margin
- つかいわけかた


marginとpaddingを使い分けるポイントは「親要素と子要素の間（親子間）の余白はpadding、隣り合った要素（兄弟間）の余白はmarginを使う」


https://eclair.blog/difference-between-margin-and-https://eclair.blog/difference-between-margin-and-padding/

### positon relative absolute
要素や位置を変えるプロパティ


- relative：現在の位置を基準に相対的な位置を決める
- absolute：親要素を基準に絶対的な位置を決める
```index.html
<div id="example">
  <img src="bear.jpg"/>
  <span>クマさん</span>
</div>
```
```style.css
#example {
  position: relative;
  /*要素内の余白は消す*/
  padding:0;
}
/*文字*/
#example span {
  position: absolute;
  bottom: 0;
  right: 0;
  /*以下装飾*/
  color: white;
  background: #74c1f8;
  padding:0 2px;
  line-height:1.5;
}
```
- fixed：画面のきまった位置に固定する
  - headerとかによく使う --- 位置の基準は親要素ではなく「ウィンドウ全体」

https://saruwakakun.com/html-css/basic/relative-absolute-fixed

### reset.css
リセットCSSとは、ブラウザによって異なるデフォルトのCSSを打ち消してブラウザ間の表示を揃えるためのCSSファイルのこと


### max-width min-width
widthの取ることのできる最大値、最小値

- max-width --- PCで見ると大きくなりすぎるを防ぐ
- min-width --- スマホで見ると小さくなりすぎるを防ぐ

https://saruwakakun.com/html-css/basic/max-min-width

### flexbox
簡単にレイアウトが組めちゃう素敵ボックス

https://www.sejuku.net/blog/56401

### 擬似要素タグbeforeとafter
https://www.asobou.co.jp/blog/web/before-after



