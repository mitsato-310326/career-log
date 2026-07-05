# miniRT

C言語で書くレイトレーサー(42 Tokyoカリキュラム)。

## 概要
- 言語: C
- 方式: Whitted-style direct lighting(シャドウレイ + 環境光、乱数なし)
- 元は "Ray Tracing in One Weekend" のMonte Carloパストレーシングから開始し、後にWhitted-styleへ移行

## できるようになったこと
- カメラの初期化(FOV処理、外積による基底ベクトル構築)
- クォータニオンを使ったオブジェクトの回転変換(ローカル座標系へのレイ変換)
- 球・円柱・平面などの交差判定ロジック(円柱はキャップ判定含む)

## 技術的に苦労した点
- 円柱交差判定でのローカル座標系変換のデバッグ
- 座標系の不一致による見た目のバグの切り分け

## タグ
`#C` `#raytracing` `#quaternion` `#miniRT`
