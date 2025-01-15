# [camera]と向きを同期する
<img width="290" alt="スクリーンショット 2025-01-16 8 21 17" src="https://github.com/user-attachments/assets/13a013b9-bf8c-49ca-872e-2f10caa0a476" />

## 機能説明
この属性ブロックを入れたオブジェクトは設定したIDのオブジェクトと同じ方向を向き続けるようになります。
デフォルトでは、一人称のカメラと同じ方向を向くように設定されています。
別のオブジェクトを指定したい場合は、入力欄の先頭に"#"を付けて対象のIDを入力してください。

例：#block

<img width="275" alt="スクリーンショット 2025-01-16 8 26 20" src="https://github.com/user-attachments/assets/20346ff5-2966-4540-80c4-9727b408053d" />

## 仕様例
ブロックが二つあります。1つ目のブロックのIDは"block_1"、2つ目のblockのIDは"block_2"となっています。
IDが"block_1"のブロックは常に横に回転しています。
IDが"block_2"のブロックも常にIDが"block_1"のブロックと同じ方向を向くように回転させたいです。

<img width="774" alt="スクリーンショット 2025-01-16 8 20 22" src="https://github.com/user-attachments/assets/850108fe-cb68-47bc-b044-d920427f2f8e" />
