# Web 的世界

### 主從式架構

1. Client 用戶端/客戶端

    只要是在使用者自己機器上（例如電腦、手機）上跑的東西，就是 Client

    ###### _注意：任何來自 Client 端的東西都是不安全的、不可信_

2. Server 伺服器/服務端

    Server 就是在遠方的機器，使用者不知道裡面有什麼，使用者也沒辦法進去裡面，可以想像成是一個黑盒子

![](https://i.imgur.com/wtJIQ9p.png)

-   Client

    -   主動的角色(主)
    -   發送請求(Request)
    -   等待直到收到回應

-   Server
    -   被動的角色(從)
    -   等待來自用戶端的請求
    -   處理請求並傳回結果(Response)

### 網頁

-   什麼是網頁？又是怎麼看到網頁的？

網頁其實就是一個「瀏覽器」看得懂的檔案 `.html`
由「瀏覽器」負責顯示出來給使用者看
如果沒有「瀏覽器」，`.html` 就只是一個純文字檔案而已（你可以用編輯器打開看看）

### 瀏覽器主要功能

-   瀏覽器的主要功能就是向伺服器發出請求，在瀏覽器窗口中展示您選擇的網絡資源
-   這裡所說的資源一般是指 HTML 文檔，也可以是 PDF、圖片或其他的類型
-   資源的位置由用戶使用 URI（統一資源標示符）指定
    -   補充：[URL 是一種 URI](https://zh.wikipedia.org/wiki/%E7%BB%9F%E4%B8%80%E8%B5%84%E6%BA%90%E6%A0%87%E5%BF%97%E7%AC%A6)
-   瀏覽器解釋並顯示 HTML 文件的方式是在 HTML 和 CSS 規範中指定的
-   這些規範由網絡標準化組織 W3C（萬維網聯盟）進行維護
-   多年以來，各瀏覽器都沒有完全遵從這些規範，同時還在開發自己獨有的擴展程序，這給網絡開發人員帶來了嚴重的兼容性問題
-   如今，大多數的瀏覽器都是或多或少地遵從規範 (但 IE 就是任性)

### 前後端簡易區分

1. 前端：使用者看得到的

    只要你在瀏覽器上面看到的東西，都可以是前端工程師的範疇
    例如：Google 首頁

2. 後端：使用者看不到的

    後端處理那些你看不到的商業邏輯
    例如：Google 怎麼執行搜尋，怎麼把搜尋結果從「資料庫」裡面撈回來，並且丟回前端

![](https://i.imgur.com/h1lvwHN.png)

### 前端三劍客

網頁又可以說是由三個部分組成

1. HTML，網頁的結構跟內容
2. CSS，網頁的外觀
3. JavaScript，程式相關的東西（與使用者互動、商業邏輯、表單驗證、運算）

![](https://i.imgur.com/gMWT1uN.png)

### 後端語言

![](https://i.imgur.com/gLlM0TM.png)

### 前台、後台、前端、後端

-   前台
    -   想像蝦皮買家（一般使用者）可以看到的頁面
-   後台
    -   想像蝦皮賣家（管理員）可以看到的頁面
-   前端
    -   所有使用者看得到的地方
-   後端
    -   所有使用者看不到的地方

所以前台不是前端，後台也不是後端的意思！

### 前端地圖與生態圈

-   Web 開發者學習地圖

![](https://i.imgur.com/BS5Xg9k.png)

-   前端學習地圖
    -   「紅色」是「前端小小班」要上的
    -   「粉紅色」是「我們部門」有在用的

![](https://i.imgur.com/KWzTVS1.png)

### 編輯器

-   前端工程師常用編輯器

    -   Sublime Text <img src="https://i.imgur.com/BHFa38G.png" width="30" height="30"/>
    -   VSCode <img src="https://i.imgur.com/bWsQKNY.png" width="30" height="30"/> (市佔率較高、很多大神的插件給你裝)
    -   Atom <img src="https://i.imgur.com/dWWRgze.png" width="30" height="30"/>
    -   Webstorm <img src="https://i.imgur.com/7dA1rpg.png" width="30" height="30"/>(PhpStorm 的兄弟)

-   常用線上編輯器
    -   [jsbin](https://jsbin.com/)
    -   [codepen](https://codepen.io/) (可以去挖寶)
    -   [jsfiddle](https://jsfiddle.net/)
