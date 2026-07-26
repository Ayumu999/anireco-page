---
format: 1920x1080
duration: 15s
message: "その一瞬を、AIが解説するARグラス『アニレコ！』"
arc: Approach -> Surprise -> Understanding -> Brand
audience: X and Instagram viewers
mode: collaborative
---

## Frame 1 - ゴリラ舎へ

- status: built
- src: compositions/frames/01-approach.html
- duration: 3.98s
- transition_in: cut
- poster: 1.88s
- scene: 動物園の俯瞰に「Future Zoo Experience」が現れ、ARグラスをかけた女性主人公がゴリラ舎へ到着する。
- blueprint: camera-journey

俯瞰中央の「Future Zoo Experience」で未来の動物園体験を宣言し、前進するカメラを、
ゴリラ舎へ向かう女性主人公の背中へ連続的につなげる。到着カットには文字を重ねない。

## Frame 2 - 今の行動、なに!?

- status: built
- src: compositions/frames/02-anireco.html
- duration: 7.8s
- transition_in: cut
- poster: 5.7s
- scene: ゴリラの一瞬をロックオンし、AR上にAI解説が現れる。
- blueprint: compose
- rules: coordinate-target-zoom, ai-tracking-box, gradient-text-sweep

ゴリラが空の手で見せる警告動作をフックにする。アニレコ実行後、
フォーカス枠が対象を捉え、解説「威嚇行動」「周囲への警告を示している可能性があります。」と
「その一瞬を、AIが解説。」が読み切れる状態で着地する。

## Frame 3 - アニレコ！

- status: built
- src: compositions/frames/03-brand.html
- duration: 4.5s
- transition_in: cut
- poster: 3.75s
- scene: Animal RecorderがARへ収束し、アニレコ！のロゴだけが残る。
- blueprint: logo-assemble-lockup
- rules: depth-scatter-assemble, gradient-text-sweep

`Animal Recorder`のAとR以外が下方へ落ち、残った2文字が中央で`AR`に合体する。
`AR`が渦状に縮退し、反対回転から`アニレコ！`が現れる。配色は元サイトと同じ
`#A3E635`から`#FB923C`のグラデーション。最後はロゴのみを静止させる。

