# chromeExtension_mastodonTheme
マストドンの色合いを変えるChrome拡張です。
私はukadonのユーザなのでそこでのみ適用されるようにしています。
他鯖の方はmanifest.jsonの`"matches": [ "https://ukadon.shillest.net/*" ],`を良い感じに書き換えてください。
動作はユーザー設定 -> 外観 -> 上級者向けUIを有効にする。を使用した状態で確認しています。


## Usage
#### color
色合いを設定するにはstyle.cssの中を適当に書き換えてください。
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
絵文字入力の枠と選択する絵文字の表示を大きくしています。
適当に変更してください。



## Installation
[Chrome拡張](chrome://extensions/)下記のサイトでデベロッパーモードを有効化し、 パッケージ化されていない拡張機能を読み込む -> 解凍したこのフォルダを読み込ませてください。


## License
MIT


## 制作動機
これから長くお世話になりそうなので、目の負担を減らしたかった。


## Author
ambergon



