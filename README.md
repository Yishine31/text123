影片網址: (https://www.youtube.com/watch?v=88iPjxeaXpg)

### github簡介

github是一個基於 git進行源代碼託管服務 與 版本控制 的網站。

- 每當要使用git時，就需對存放代碼檔案的資料夾進行初始化，
使其變成一個 git 可以控制的 repository(git 項目倉庫)。
    - 在資料夾中，可以通過 git指令對文件進行版本控制與代碼管理。
- githut拆開可以看成 git + hub(樞紐)。
    - git 可理解為基於git 或 git倉庫。
    - hub 就是樞紐，也就是許多開發者使用 git進行版本管理的開發項目上傳到網站上。
    當這個網站集合許多 git repository，他就成為 github。
- 為何開發者在本機作業，要將程式上傳到 github? github有兩大特點: 分享和協作。
    - github大部分功能都是免費提供給全球開發者，尤其被微軟收購後功能也更加完善。
        - 節至2019就累計 4千萬用戶，一年中創建 4400萬個倉庫。github已成為最大的 代碼存放與開源社群。
        - 只要打開 github就能進行搜索，搜尋結果就是別人創建的倉庫。當然也能創建無法搜尋的私人倉庫。

### github 基本操作

以搜尋 react的倉庫，Facebook/react 為例。

- img
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/9f11cc6b-1585-41da-add9-9fbc118517e2/98d41768-70ce-475d-a569-d3156a65a13d/Untitled.png)
    
- 搜尋清單 第一行是標題，包括上傳者 `/` 後是庫的名稱，接著是 簡介, 相關標籤(topic)。
最後一行是使用語言, 星星數, 更新時間。
    - 上傳者分成組織與用戶，組織如 Facebook 無法進行關注，用戶則可以。
        - 這個功能像社群媒體，可以讓你將感興趣的主題都關注起來，
        並建立自己的 Fork(分支)。
    - 不同程式語言製作的庫會用不同顏色區隔，例如JavaScript是黃色。
    - 星星數越多表示這個庫越多人點讚。可以作為是否好用的指標。
    - 左方側邊攔可以進階搜尋相關內容。
- 點擊標題可以進入倉庫查看內容，倉庫會默認顯示 readme.md 文件中的內容 .md 表示他是用 markdown語法建立的文件。
    - 關於倉庫介紹與注意事項都會寫在 readme.md 文件中。
    - 點擊 <>Code 按鈕可以將開源程式打包成zip下載
        - img
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/9f11cc6b-1585-41da-add9-9fbc118517e2/801d13e4-fe3e-4441-aa16-f0adaff2183a/Untitled.png)
            
    - 下載zip檔不用登入帳號，登入後可以對倉庫開啟通知(小鈴鐺), 或star(收藏)。
    - 點擊像龍蝦的符號 Fork(分支)，可以拷貝該完整項目到自己帳號下。
        - Fork完成後會跳轉到 自己的 Fork倉庫頁面，左上角會有 forked from {source}的提示。
- 建立倉庫
    - 登入帳號後可以建立倉庫，倉庫名稱必須使用英文。
        - img
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/9f11cc6b-1585-41da-add9-9fbc118517e2/2a5d7dc6-ad49-40fc-a8fb-b5936a78aaf8/Untitled.png)
            
    - 若勾選 初始化 readme文件，建立的倉庫下方會出現 readme文件內容。
    - 倉庫中可以直接建立文件，或選擇文件進行上傳。
        - 點擊 commit change就完成文件上傳，其他人就能透過倉庫地址來瀏覽你建立的文件。

### git 與 github協作

### github的開源項目協作流程
