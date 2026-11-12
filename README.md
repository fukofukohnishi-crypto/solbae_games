# solbae games

solbae がつくったゲームのあつまり。

## ダウンロードして遊ぶ

1. 遊びたいゲームの「ダウンロード」を開く
2. 右上の下向き矢印（Download raw file）を押す
3. 「ファイル」アプリの「ダウンロード」にできたファイルをダブルクリックすると、Chrome で開いて遊べる

| ゲーム | 内容 | ダウンロード |
|---|---|---|
| 🏎️ スカイフック・レーサー | 空のコースを走る3Dレース。12台レース・2人プレイ | [skyhook-racer.html](games/skyhook-racer.html) |
| 🎡 にじいろパーク | 3D遊園地経営ゲーム | [nijiiro-park.html](games/nijiiro-park.html) |
| ⚔️ サバイバルバトルX100 | 100人バトルロイヤル。武器500種 | [survival-battle-x100.html](games/survival-battle-x100.html) |
| 🍜 もぐりあん 3D | おでん・ラーメン経営ゲーム | [moguri-an-3d.html](games/moguri-an-3d.html) |

- ファイル1つで動きます。ネットにつながっていなくても遊べます。
- セーブデータはそのパソコンのブラウザに保存されます。

## ブラウザで遊ぶ

https://fukofukohnishi-crypto.github.io/solbae_games/

## しくみ（作る人向け）

- 各ゲームは `games/<名前>.html` の1ファイルで完結しています。`games/<名前>/` は前のURL用の転送ページです。
- three.js (r128, MIT License) はファイル内に埋め込み済み。外部から読むのはフォント（Google Fonts）だけで、読めなくても代わりのフォントで動きます。
- サバイバルバトルX100 は [survival-battleX100](https://github.com/fukofukohnishi-crypto/survival-battleX100) の `build.sh` で作った1ファイル版、もぐりあん 3D は [keieigame](https://github.com/fukofukohnishi-crypto/keieigame) から。スカイフック・レーサーとにじいろパークは Claude のアーティファクトで作ったもの。
- 元のゲームを直したら、`games/` の中のファイルを差し替えます。
