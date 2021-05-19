# AWS-Lambda-Layer
## 概覽
提供 AWS Lambda 所需的 Layer😊。Layer 是一種可以為 AWS Lambda 新增函式庫的方法。例如，原生的 Lambda 並沒有支援 Pandas、Numpy、OpenCV 等知名套件，利用 Layer 便能解決該問題。   
## 使用方式
直接下載 .ZIP 檔案後，上傳至 AWS Lambda 即可。注意，上傳的 ZIP 檔案有資料大小的限制，cv2-python37.zip 需參照 [awslabs/lambda-opencv](https://github.com/awslabs/lambda-opencv) 的說明，以 AWS CLI 和 jq 上傳較為妥當。
