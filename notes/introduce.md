
- **src/**
    - **components/**：存放前端組件
    - **views/**：存放前端視圖頁面
    - **services/**：存放與後端 API 通信的服務
    - **styles/**：存放樣式文件
    - **assets/**：存放圖片等靜態資源


```
- **改寫-MVC pattern**
    - models/：
    這個資料夾存放應用程式的資料模型或數據模型，負責管理應用程式的數據。

    - views/：
    這個資料夾存放應用程式的視圖，即用戶界面的表示層，負責將數據呈現給用戶。

    - controllers/：
    這個資料夾存放應用程式的控制器，即業務邏輯的處理層，負責處理用戶的輸入和業務邏輯的處理。

    - services/：
    這個資料夾存放與後端 API 通信的服務，負責處理與後端的數據交互。

    - styles/：
    這個資料夾存放樣式文件，雖然在傳統的MVC模式中，樣式並不屬於MVC中的一部分，但在前端開發中，樣式通常是與視圖密切相關的，因此也可  
    以放在這個資料夾中。

    - assets/：
    這個資料夾存放圖片等靜態資源，這些資源可能會在視圖中使用。
```

#### components/：
在這個目錄下，您可以進一步細分組件，根據功能或共享性質進行組織。例如，可以有一個**navbar/目錄來存放導航欄相關的組件，有一個product/**目錄來存放商品相關的組件等等。

#### views/：
如果項目的規模足夠大，可以將每個頁面的代碼進一步細分。例如，將每個頁面的組件、樣式和服務分別存放在對應的子目錄中。

#### services/：
如果服務模塊非常龐大，可以進一步細分服務，根據功能或資源類型進行組織。例如，將與商品相關的API服務存放在一個**product/目錄中，將與用戶相關的API服務存放在一個user/**目錄中等等。

#### styles/：
根據需求，您可以進一步細分樣式文件。例如，將全局樣式存放在一個**global/目錄中，將組件專有的樣式存放在一個components/目錄中，將頁面專有的樣式存放在一個views/**目錄中等等。

#### assets/：
如果靜態資源非常多，可以根據類型或用途進行組織。例如，將圖片存放在一個**images/目錄中，將字體文件存放在一個fonts/**目錄中等等。

### 商品組件
商品組件通常指的是在網站或應用程式中用於顯示商品相關信息的可重用組件。這些組件可以是各種形式，取決於設計和功能需求，但通常包括以下一些基本元素：

商品圖片：顯示商品的圖片或圖像，讓用戶可以看到商品的外觀。

商品名稱：顯示商品的名稱或標題，讓用戶可以識別商品。

價格：顯示商品的價格，讓用戶知道商品的價格範圍。

庫存狀態：顯示商品的庫存狀態，讓用戶知道商品是否可購買。

加入購物車按鈕：提供用戶加入購物車的功能，讓用戶可以將商品添加到購物車中進行購買。

商品描述：提供商品的詳細描述，讓用戶了解商品的特性和功能。

