# AICUP 2023 TEAM_3558 

## 安裝配置環境
* python 3.8.13
* 套件包含在requirements.txt

## 重要模塊輸出/輸入
* **dict.txt.big**為jieba套件所需之檔案
* **data/all_test_data.jsonl**為public與private合併的測試資料
* **data資料夾**中存放訓練資料與測試資料
* **checkpoint資料夾**中存放訓練的checkpoint

## 路徑設定
* sentence retrieval以及claim verification中的**ckpt_name**要自行修改成訓練後產生的.pt檔

## 執行步驟說明
* 主要運行程式
*   **main.ipynb**
* libary
*   **dataset.py**
*   **utils.py**
*   **hw3_utils.py** 
* 直接執行**main.ipynb**即可
