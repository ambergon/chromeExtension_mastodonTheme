# chromeExtension_mastodonTheme
マストドンの色合いを変えるChrome拡張です。<br>
私はukadonのユーザなのでそこでのみ適用されるようにしています。<br>
他鯖の方はmanifest.jsonの`"matches": [ "https://ukadon.shillest.net/*" ],`を良い感じに書き換えてください。<br>
動作はユーザー設定 -> 外観 -> 上級者向けUIを有効にする。を使用した状態で確認しています。<br>


## Usage
#### color
色合いを設定するにはstyle.cssの中を適当に書き換えてください。<br>
```
:root {
/**/
    /* 全体の背景 */
    --all-color         : #002E1F;
    /* 左手側入力欄周りの色 */
    --menu-color        : #013205;
    /* スクロールバー スライダーの色 。*/
    --scrollbar-color   : #015C08;
    /* 投稿文字色 */
    --article-color     : #dcdcdc;
}
```

#### emoji
絵文字入力の枠と選択する絵文字の表示を大きくしています。<br>
適当に変更してください。
```
/* 絵文字周りの使用を便利にする。 */
/*スタンプ一覧を表示する枠の大きさを拡大。*/
/*999px位にすると明らかに使いやすくなる。 */
section.emoji-mart-light {
    width:499px !important
}

/*スクロール枠の高さを適当に調整。*/
.emoji-mart-scroll {
    height:470px !important;
    max-height:80vh !important;
}

/*一覧の絵文字アイコンを大きく表示する。*/
button.emoji-mart-emoji > img {
    width: 40px  !important;
    height: 40px !important;
}
```


#### 実際の表示サンプル
デフォルト設定にスタンプ表示枠を999pxに変更したもの。<br>
[うかどん](https://ukadon.shillest.net/deck/@ambergon/110932116645228172)<br>




## Installation
[Chrome拡張](chrome://extensions/)下記のページでデベロッパーモードを有効化し、 パッケージ化されていない拡張機能を読み込む -> 解凍したこのフォルダを読み込ませてください。


## License
MIT


## 制作動機
これから長くお世話になりそうなので、目の負担を減らしたかった。


## Author
ambergon



