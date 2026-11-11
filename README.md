# solbae games

solbae がつくったゲームのあつまり。

遊ぶ: https://fukofukohnishi-crypto.github.io/solbae_games/ （GitHub Pages を有効にすると開けます）

| ゲーム | 内容 | 元のリポジトリ |
|---|---|---|
| [スカイフック・レーサー](games/skyhook-racer/) | 空のコースを走る3Dレース。12台レース・2人プレイ | （Claude のアーティファクトで作成） |
| [サバイバルバトルX100](games/survival-battle-x100/) | 100人バトルロイヤル。武器500種 | [survival-battleX100](https://github.com/fukofukohnishi-crypto/survival-battleX100) |
| [INK ARENA](games/ink-arena/) | インクで戦う3Dバトル | [ink-battle](https://github.com/fukofukohnishi-crypto/ink-battle) |
| [もぐりあん 3D](games/moguri-an-3d/) | おでん・ラーメン経営ゲーム | [keieigame](https://github.com/fukofukohnishi-crypto/keieigame) |

## しくみ

- 各ゲームは `games/<名前>/index.html` の1ファイルで完結しています。
- 外部サイトから読み込むものはほぼありません（学校など、フィルタのある環境でも動きやすくするため）。
  - three.js (r128, MIT License) はファイル内に埋め込み済み。
  - フォント（Google Fonts）だけは外部読み込み。読めなくても代わりのフォントで動きます。
- サバイバルバトルX100 は元リポジトリの `build.sh` で作った1ファイル版です。

## 更新のしかた

元のリポジトリでゲームを直したら、このリポジトリの `games/` の中のファイルを差し替えます。
