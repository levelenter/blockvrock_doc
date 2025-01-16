# [camera]をリードする距離(3)Y方向を(うごかす)ブロック
<img width="512" alt="スクリーンショット 2025-01-16 8 34 36" src="https://github.com/user-attachments/assets/515650cb-24b7-4d77-b96c-bf651bb4c45b" />

## 機能説明
この属性ブロックを入れたオブジェクトは操作者の向いている方向を基準に座標が移動し続けます。
デフォルトでは、一人称のカメラが向いている方向を基準としています。
別のオブジェクトを指定したい場合は、入力欄の先頭に"#"を付けて対象のIDを入力してください。

例：#block

<img width="498" alt="スクリーンショット 2025-01-16 8 37 30" src="https://github.com/user-attachments/assets/15f2494d-4d1e-4b59-b03f-88b9021bc914" />

## 使用例
ブロックが二つあります。1つ目のブロックのIDは"block_1"、2つ目のblockのIDは"block_2"となっています。
IDが"block_1"のブロックは常に横に回転しています。
IDが"block_2"のブロックも常にIDが"block_1"のブロックと同じ方向を向くように回転させたいです。

<img width="627" alt="スクリーンショット 2025-01-16 8 51 39" src="https://github.com/user-attachments/assets/a67f22f1-99e6-4699-ac70-5fa434b600e7" />
