# Plurk-Backup-Master

Easily download all Plurks images, messages and replies posted by a specific Plurks user ( including images and message in the replies below ) from plurk.com

輕鬆下載特定 Plurks 用戶發布的所有 Plurks 圖像,訊息和回复

I edited the code using Chatgpt so that the script can now downloads all images, messages and replies  ( including images and message in the replies below ) not just only downlond images in the Plurk Crawler.

我使用 ChatGPT 編輯了程式碼，讓腳本現在可以下載所有文字訊息和圖片，包括回覆中的圖片和文字訊息，而不僅僅是 Plurk Crawler 中的圖片。

## Acknowledgment 致謝

Most of this project is based on the original Plurk Crawler by [freelze](https://github.com/freelze). I express my sincere thanks to freelze for their contribution to the Plurk Crawler project.

本專案大部分基於  [freelze](https://github.com/freelze) 原始的 Plurk Crawle 。我衷心感謝 freelze 對 Plurk Crawler 專案的貢獻。 

## Disclaimer免責聲明
I want to clarify that I do not own any of the code in this project. This project is based on the original Plurk Crawler by [freelze](https://github.com/freelze), and ChatGPT enhances it.
我想澄清的是，我並不擁有本專案中的任何程式碼。這個專案大部分基於 [freelze](https://github.com/freelze) 的原始 Plurk Crawler，我使用 ChatGPT 編輯。

## Getting Started 前置作業 

### 安裝 Python 3.11+
### Clone the repository 下載程式碼
    
    git clone https://github.com/dunc4009/Plurk-Backup-Master.git
=======

### Open a terminal or command prompt 開啟終端機或命令提示字元

### Install Python dependencies: 安裝 Python 相關套件    
    pip install -r requirements.txt

### Obtain Plurk API credentials as described in the original Plurk Crawler project. 

### 註冊 Plurk 帳號：https://www.plurk.com/signup 

### 申請 API 服務：http://www.plurk.com/PlurkApp/ 

  請參考 dada 的教學文: https://dada.tw/2011/10/28/426/ 

  取得
+   App Key
+   App Secret 
+   Access Token  
+   Access Token Secret
    
### Rename .env.example to .env and update the credentials accordingly. 修改檔名，將 .env.example 檔案重新命名為 .env

### 修改 .env 檔案的金鑰:

+ CONSUMER_KEY=***你的App Key放這裡***
+ CONSUMER_SECRET=***你的App Secret放這裡***
+ ACCESS_TOKEN=***你的Access Token放這裡***
+ ACCESS_TOKEN_SECRET=***你的Access Token Secret放這裡***


# Run the script: 執行程式
    python main.py username1 username2 username3

`username` 就是網址 http://www.plurk.com/使用者帳號 的 `使用者帳號`

Replace username1, username2, etc., with the Plurk usernames whose images and messages you want to download.
