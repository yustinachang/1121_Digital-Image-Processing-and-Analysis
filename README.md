# 影像處理｜Digital Image Processing and Analysis

112 學年度第一學期的影像處理、深度學習與電腦視覺課程紀錄，包含課堂 Notebook、期中辨識專題與期末物件偵測作品。

國立彰化師範大學 · `1121_20009` · 授課教師：劉儼毅 · [課程大綱](https://webapt.ncue.edu.tw/DEANV2/UploadDEAN/SUBJECT/1121/20009_1SCSC0100930.pdf)


## 專題

| 專題 | 內容與入口 |
| --- | --- |
| [期中：鐘面時間影像識別](Mid-term_Project) | YOLOv4 訓練 Notebook、設定與報告；[原 Colab](https://colab.research.google.com/drive/1xxE2TiuNFGD_JHpJ-PszKZ1yP0uJZp9k) |
| [期末：司諾克撞球偵測](Final_Project) | YOLOv8、SAHI 影片推論 Notebook、成果與展示影片；[原 Kaggle](https://www.kaggle.com/code/yustinachang/snooker-balls-detection-with-yolov8) |

## 課堂練習

| 資料夾 | 主題 |
| --- | --- |
| [HW0](HW0) | Python 隨堂測驗 |
| [HW1](HW1) | Teachable Machine |
| [HW2](HW2) | TensorFlow 與 MNIST |
| [HW3](HW3) | 自主學習心得 |
| [HW4](HW4)、[HW5](HW5) | YOLOv4-tiny 訓練與自訂資料集 |
| [HW6](HW6) | OpenCV 人臉偵測 |
| [Practice](Practice) | LiverCT、UNet／ResUNet、YOLOv7＋ByteTrack |

## 重現前準備

使用 Jupyter、Colab 或 Kaggle 開啟對應 `.ipynb`，依各份 Notebook 的安裝儲存格準備環境，並修改資料集與輸出路徑。不同作業的模型版本與依賴不同，不共用一套固定需求檔。

訓練資料與完整權重未全部收錄。`Mid-term_Project/my_yolov4-tiny-custom_last.weights` 僅 2 bytes，不能作為可用模型載入，需另備完整權重或重新訓練。原雲端連結保留作為課程紀錄，執行前仍需確認存取權與資料位置。
