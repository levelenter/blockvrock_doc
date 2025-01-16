# ブロック名：ライト
<img width="612" alt="スクリーンショット 2025-01-16 13 32 12" src="https://github.com/user-attachments/assets/0ce88450-0b4a-4f8c-b59b-d2bdb51df9c3" />

## 機能説明
シーンスタート内にあるオブジェクトへの照明の当たり方を設定するブロックです。

## 光の種類
・周囲  
全てのオブジェクトに光が当たるようになります。  

・直線的  
指定したポジションから一方向に直線的に光を当てます。  
指定したポジションからオブジェクトまでの距離による光の減衰はありません。
光が当たっていない場所には影ができます。  
<img width="682" alt="スクリーンショット 2025-01-16 19 17 27" src="https://github.com/user-attachments/assets/6e2ddf3b-fc25-4b17-894b-8bee36b8ad81" />  
<img width="315" alt="スクリーンショット 2025-01-16 19 18 04" src="https://github.com/user-attachments/assets/044b3b4e-ae0e-41a1-866f-1719f27eb3f2" />

・半球  
指定したポジションから一方向から広がるように光を当てます。  
<img width="667" alt="スクリーンショット 2025-01-16 19 36 55" src="https://github.com/user-attachments/assets/1a9e6fc6-7885-4c9c-96e3-2dd17412cdbc" />  
<img width="321" alt="スクリーンショット 2025-01-16 19 36 20" src="https://github.com/user-attachments/assets/650d2fb3-07d4-4029-939a-278dc226f613" />

・ポイント  
指定したポジションから全方向に向かって光を当てます。  
光源に近いほどオブジェクトに当たる光の面積が狭くなり、明るく照らされます。
このブロックを入れていない場合、デフォルトで
<img width="696" alt="スクリーンショット 2025-01-16 19 45 22" src="https://github.com/user-attachments/assets/d566577d-4027-4e60-b94d-1d77369497c2" />
<img width="331" alt="スクリーンショット 2025-01-16 19 47 19" src="https://github.com/user-attachments/assets/0b86bdec-68a3-4d9a-8744-7e0535b11ac9" />

・スポット
指定したポジションから一方向に向かって光を当てます。  
光源に近いほどオブジェクトに当たる光の面積が狭くなり、明るく照らされます。
<img width="938" alt="スクリーンショット 2025-01-16 20 07 10" src="https://github.com/user-attachments/assets/8d8331b7-3e77-450f-befe-2f6d6c0f15aa" />
<img width="328" alt="スクリーンショット 2025-01-16 20 12 39" src="https://github.com/user-attachments/assets/4852b42e-a890-4069-8edd-68b6ea911052" />

## 使用例
球体に上としたから別々の光を当てたい  
<img width="950" alt="スクリーンショット 2025-01-16 20 19 33" src="https://github.com/user-attachments/assets/610f745c-05d7-46bb-ad5e-a4b1f61583b6" />
