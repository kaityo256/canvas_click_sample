# JavaScriptのCanvasのサンプル

## 概要

JavaScriptのCanvasのマウスクリックイベントを取得し、対応するデータ配列を書き換え、それを描画するサンプル。

* 9x9マスに10個ランダムに赤いセルが配置される。
* 左クリックすると、その場所が赤くなる
* 右クリックすると、その場所が黒くなる
* リロードの度に初期化

[動作サンプルはこちら](https://kaityo256.github.io/canvas_click_sample/).

## 原理

* マウスイベントを取得し、クリックされた座標から、データ配列の座標を取得、そこを書き換える。
* クリックイベント後に、データから表示を毎回全て書き直す関数`draw`を呼び出している

## LICENSE

MIT