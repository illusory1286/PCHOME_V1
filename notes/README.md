## PCHOME筆記 - 課程內容紀錄

**專案名稱：**
PCHOME_V1

**日期：**
113/3/31

**課程目的：**
使用最基礎不依賴框架仿刻出PCHOME

**內容摘要：**
1. [概述](#概述)
2. [重點紀錄](#重點紀錄)
3. [問題與討論](#問題與討論)
4. [目前進度](#目前進度)



專案結構
```
原本-
- **src/**
    - **components/**：存放前端組件
    - **views/**：存放前端視圖頁面
    - **services/**：存放與後端 API 通信的服務
    - **styles/**：存放樣式文件
    - **assets/**：存放圖片等靜態資源
```

```
改寫-MVC pattern
- models/：
這個資料夾存放應用程式的資料模型或數據模型，負責管理應用程式的數據。

views/：
這個資料夾存放應用程式的視圖，即用戶界面的表示層，負責將數據呈現給用戶。

controllers/：
這個資料夾存放應用程式的控制器，即業務邏輯的處理層，負責處理用戶的輸入和業務邏輯的處理。

services/：
這個資料夾存放與後端 API 通信的服務，負責處理與後端的數據交互。

styles/：
這個資料夾存放樣式文件，雖然在傳統的MVC模式中，樣式並不屬於MVC中的一部分，但在前端開發中，樣式通常是與視圖密切相關的，因此也可以放在這個資料夾中。

assets/：
這個資料夾存放圖片等靜態資源，這些資源可能會在視圖中使用。
```

### 概述
簡要描述本次課程的主題和目標。
1. 使用

### 重點紀錄
- NodeJs服務器
  1. [導入http模組](#導入http模組)

  ```NodeJs
  const http=require("http")
  ```
  2. 使用http模塊,用回調函數參數(request,response)

  ```
  const server =http.createServer((request,response)=>{
    response.end("Welcone My World")
  })
  ```
  3. 創一個伺服器監聽
  ```
  const port=3000;
  const ip="127.0.0.1"
  server.listen(port,ip,()=>{
      console.log(`server is running at http://${ip}:${port}`)
  })
  ```


### 問題與討論
過程中並無碰到問題
- 熟悉const定義
- 分三大步驟
    1. 導入http模組
    2. http模組,使用回調函並賦予兩個參數(request,response)
    3. 創一個伺服器監聽
### 目前進度







