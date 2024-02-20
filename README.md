# Plurk-Backup-Master

Easily download all Plurks images, messages and replies posted by a specific Plurks user ( including images and message in the replies below ) from plurk.com

輕鬆下載特定 Plurks 用戶發布的所有 Plurks 圖像,訊息和回复

I edited the code using Chatgpt so that the script can now downloads all images, messages and replies  ( including images and message in the replies below ) not just only downlond images in the Plurk Crawler.
Important:This enhancement was developed by ChatGPT.

## Acknowledgment

Most of this project is based on the original Plurk Crawler by [freelze](https://github.com/freelze). I express my sincere thanks to freelze for their contribution to the Plurk Crawler project.
## Disclaimer

I want to clarify that I do not own any of the code in this project. This project is based on the original Plurk Crawler by [freelze](https://github.com/freelze), and ChatGPT enhances it.

## 前置作業

### 安裝 Python 3.11+
### 下載程式碼
    
    git clone https://github.com/dunc4009/Plurk-Backup-Master.git
=======

### 安裝 Python 相關套件    
    pip install -r requirements.txt

### 註冊 Plurk 帳號：https://www.plurk.com/signup 

### 申請 API 服務：http://www.plurk.com/PlurkApp/ 

  請參考 dada 的教學文: https://dada.tw/2011/10/28/426/ 

  取得
+   App Key
+   App Secret 
+   Access Token  
+   Access Token Secret
    
### 修改檔名，將 .env.example 檔案重新命名為 .env

### 修改 .env 檔案的金鑰:

+ CONSUMER_KEY=***你的App Key放這裡***
+ CONSUMER_SECRET=***你的App Secret放這裡***
+ ACCESS_TOKEN=***你的Access Token放這裡***
+ ACCESS_TOKEN_SECRET=***你的Access Token Secret放這裡***


# 執行程式
    python main.py username1 username2 username3

`username` 就是網址 http://www.plurk.com/使用者帳號 的 `使用者帳號`
