---
workflow: general-video
flow: companion
storyboard: yes
message: "その一瞬を、AIが解説するARグラス『アニレコ！』"
destination: x-and-instagram-feed
aspect: 1920x1080
language: ja
length: 15s
angle: "ゴリラの意外な行動をフックに、見るだけで意味がわかる体験を見せる"
---

## Intent

XとInstagramで発信する15秒のプロダクトCM。動物園の俯瞰からARグラスをかけた
女性主人公がゴリラ舎へ到着し、ゴリラの一瞬の行動をアニレコがAI解説する。
短い時間でも、商品が何をするかを実写主体で直感的に伝える。

## Assets

- `assets/zoo-aerial.png` - 動物園への進入を示す俯瞰ショット。
- `assets/gorilla-arrival-ar-woman.png` - ARグラスをかけた女性主人公がゴリラ舎へ向かうショット。
- `assets/gorilla-display-clean.png` - 空の手で威嚇行動を見せるゴリラ。
- `assets/ar-gorilla-view.webp` - ARグラス越しのAI解説完成イメージ。

## Customizations

- ナレーションなし。投擲の衝撃音、ARスキャン音、解析完了音、ロゴ着地音を使う。
- 俯瞰からアニレコ実行までは、遠い会話、足音、鳥の声など軽い動物園の環境音を入れる。
- アニレコ実行時に環境音をダッキングし、ARのサウンドマークを前面に出す。
- ラストは `Animal Recorder` -> `AR` -> `アニレコ！` の文字変形で、最後はロゴのみ。

## Notes

- 機能説明に「15秒」など未確定の数値を使わない。
- 時間表現は「今」「一瞬」「瞬間」を使う。
- 元サイトの濃紺、ライム、オレンジ、Noto Sans JP、JetBrains Monoを踏襲する。
- 主要コピーとロゴはXとInstagram双方で読める中央セーフエリアに置く。
- 元サイトの `index.html` は変更しない。
