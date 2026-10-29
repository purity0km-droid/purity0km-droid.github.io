# purity0km-droid

https://purity0km-droid.github.io/

AI チャットのキャラクターと過ごす時間のための、ブラウザだけで動く小さな道具をまとめたページです。
個人で作っている非公式のツールで、zeta 向けのツールは zeta の運営とは関係ありません。

## 道具

| | 名前 | できること | ページ |
|---|---|---|---|
| 01 読 | Talklog Viewer | talklog で保存したトークを、トーク画面に近い見た目で読み返す・立ち絵つきで再生する | https://purity0km-droid.github.io/log-viewer/ |
| 02 作 | userkit | zeta の user のための道具（プロフィール帳・名前隠し・トーク保存など） | https://purity0km-droid.github.io/userkit/ |
| 03 繋 | Pair Canvas | 2 人の画像と名前、関係性の説明を 1 枚の画像にまとめる | https://purity0km-droid.github.io/pair-canvas/ |
| 04 集 | キャラクター図鑑 | 画像生成のプロンプトと生成設定を、キャラクターごとに登録して探す | https://purity0km-droid.github.io/prompt/ |

どの道具も、入力した文字や画像はブラウザの中だけで扱い、どこにも送りません。

## このページについて

- `index.html` 1 枚でできています（外部から読み込むのはフォントだけ）。
- WebGPU が使えるブラウザでは、クラフト紙の背景・活版の押し込み・紋章の箔・ページをめくる動きを GPU で描きます。
  Chrome で試験中の機能「HTML-in-Canvas」が使えるときは、カードの文字も canvas に描きます
  （このページは Chrome の試験運用＝オリジントライアルに参加しています。2027 年 3 月 4 日まで）。
- どちらも使えないブラウザでは、同じ内容を CSS だけで表示します。

## フォント

- Zen Old Mincho（Google Fonts、SIL Open Font License 1.1）
- EB Garamond（Google Fonts、SIL Open Font License 1.1）

## 利用条件

- このページ（index.html）の再配布と、手を加えたものの公開はお断りします。
  紹介するときは https://purity0km-droid.github.io/ を案内してください。
- 各道具の利用条件は、それぞれのページに従ってください。

© 2026 purity0km-droid
