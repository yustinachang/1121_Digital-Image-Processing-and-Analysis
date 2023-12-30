# 基於YOLOv4-tiny實作物件辨識
### 專案簡介
YOLO（You Only Look Once）是一個廣泛應用於物體檢測的類神經網路演算法。<br>
以小眾架構darknet實作深度學習模型，透過給定資料集進行物件辨識。
### 心得闡述
訓練YOLOv4-tiny模型是一項挑戰性的任務。<br>
需要仔細處理自定義資料集，設定模型參數，進行訓練並進行後續的模型評估。
1. **資料集**： 使用課堂提供的乾淨資料集。
2. **模型設定**： 透過darknet使用預先訓練的權重，並在這基礎上進行微調，以提高模型的訓練速度和效果。
3. **訓練參數**：在cfg中調整模型的訓練參數，如batch size、learning rate等。
4. **模型訓練與評估**： 在訓練結束後，使用測試集來評估模型的性能。可以計算準確率、召回率、F1分數等指標，評估後續操作。
![image](https://github.com/yustinachang/1121_20009_Digital-Image-Processing-and-Analysis/assets/104688505/7a33ff1e-3386-4c99-92e9-88686bad97ba)
