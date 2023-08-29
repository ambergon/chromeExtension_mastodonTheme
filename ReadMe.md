# chromeExtension_mastodonTheme
マストドンの色合いを変えるChrome拡張です。<br>
私はukadonのユーザなのでそこでのみ適用されるようにしています。<br>
他鯖の方はmanifest.jsonの`"matches": [ "https://ukadon.shillest.net/*" ],`を良い感じに書き換えてください。<br>
動作はユーザー設定 -> 外観 -> 上級者向けUIを有効にする。を使用した状態で確認しています。<br>


## Usage
#### color
色合いを設定するにはstyle.cssの中を適当に書き換えてください。<br>
また、ベースの色はマストドン本体機能のテーマをご使用ください。<br>
```
    /*    色設定    */
    /* 背景色 */
    --all-color         : #002E1F;
    /* 入力欄周り */
    --menu-color        : #013205;
    /* スクロールバーのスライダー */
    --scrollbar-color   : #015C08;
    /* 投稿文字色 */
    --article-color     : #dcdcdc;
```

#### emoji
スタンプパレットとパレットに表示されるスタンプの表示を大きくしています。<br>
適当に変更してください。<br>
パレットの幅は999px位がおすすめです。<br>
```
    /*    絵文字パレット設定    */
    /* パレットの幅 */
    --ColorPalette-Width     : 499px;
    /* パレットの高さ */
    --ColorPalette-Height    : 470px;
    --ColorPalette-MaxHeight : 80vh;
    /* パレット内のスタンプの大きさ */
    --ColorPalette-StampSize : 40px;
    /* パレットを展開する位置(左上基準 X,Y ) */
    --ColorPalette-Translate : translate( 10px , 10px ) ;
```


#### 実際の表示サンプル
デフォルト設定にスタンプ表示枠を999pxに変更したもの。<br>
[うかどん](https://ukadon.shillest.net/deck/@ambergon/110932116645228172)<br>




## Installation
[chrome://extensions/](chrome://extensions/)下記のページでデベロッパーモードを有効化し、 パッケージ化されていない拡張機能を読み込む -> 解凍したこのフォルダを読み込ませてください。


## License
MIT


## 制作動機
これから長くお世話になりそうなので、目の負担を減らしたかった。


## Author
ambergon



