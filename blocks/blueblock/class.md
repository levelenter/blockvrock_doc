# ブロック名：クラス
<img width="233" alt="スクリーンショット 2025-01-17 12 02 16" src="https://github.com/user-attachments/assets/833ecd3d-a84f-4843-8d5f-f4a7ee54517d" />

## 機能説明
物理ブロックにクラスを割り振ることによって、同じクラスを持つオブジェクトの属性などを一括で設定することができるようになります。

## 使用例
直方体が2つと、球体が1つあります。
この合計3つのオブジェクトを全て前方に直進させたいです。

・直方体と球体をブロックで作り、全てのオブジェクトにクラス"A"を割り振る。  
<img width="668" alt="スクリーンショット 2025-01-17 11 51 57" src="https://github.com/user-attachments/assets/7dc8b1dd-8448-4280-a404-09f5389bd845" />

・HTMLモードを開いてコードを全てコピーする。

・CODEモードにコピーしたコードを貼り付ける。
redy(async() => {})の中に以下のコードを入れる。  
let elements = document.querySelectorAll('.A');  
elements.forEach((element) => {  
  element.setAttribute('ahead', 'speed:1; pitch:false; stopattouch:false');  
});  

・BLOCKモードで実装したコードを"シーンスタート"以外全て消す。  
　※CODEモードを使っているため、BLOCKモードで実装したコードと衝突が怒ってしまうからです。
