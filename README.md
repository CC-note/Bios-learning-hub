# BIOS PM 0→1 Learning Hub · 正式版 v2

Public Edition · 教材快照：2026-09-15

## 開啟網站

解壓縮 ZIP 後，雙擊 index.html。請讓 assets 資料夾與 index.html 放在同一層。
不需安裝套件、建立帳號或執行建置指令；建議使用近期版本的 Edge、Chrome 或 Firefox。

## 部署到 GitHub Pages

1. 開啟你要使用的 GitHub repository。
2. 選 Add file → Upload files。
3. 上傳解壓縮後的 index.html、assets/、.nojekyll 與說明檔；保留資料夾結構。不要只上傳 ZIP。
4. Commit changes。
5. 到 Settings → Pages，Source 選 Deploy from a branch。
6. Branch 選實際存放這些檔案的分支（常見為 main），Folder 選 / (root)，按 Save。
7. 等候部署成功後，使用 Pages 頁面提供的網址。

若既有網站檔案放在子資料夾，應將本包內容放到你選定的發布根目錄。
本網站使用相對資產路徑與 hash 導覽，可放在 repository 的 GitHub Pages 路徑下。

官方操作依據：
[GitHub Pages 發布來源設定](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 網站內容

- 四大 Layers：Common Technical Knowledge / Insyde Know-how / PM Professional Competency / PM Daily Practice。
- Learning Path、Technical Knowledge Base、Insyde Know-how、PM Practice & Collaboration。
- Case Study & Issue Analysis、Technical Glossary、Competency Assessment。
- Diagram Library、Learning Progress。
- 四份既有教材正文、三張既有 BIOS 圖解、117 個術語。
- 基礎練習 8 題、逐題回饋、虛構案例與 PM 更新文字練習。

## 教材狀態

核對時，教材追蹤表未有 Done 的 Module。既有正文作為可閱讀教材正式收錄；
尚未完成的課程整合及正式評量保持 In Progress，不把本次網站建置誤認為教材完成。
追蹤表中的 Planned / Backlog / Review 等未完成狀態，在公開學習入口統一以 In Progress 呈現。

網站增加的比喻、基礎題、虛構案例與通用更新示例，是補充學習活動，不宣稱為已完成教材。
L1–L4 採既有框架；正式 Rubric、題庫與能力認證尚未完成。

## 公開資料範圍

套件僅包含通用技術教材、公開學習架構與虛構練習。
未放入標記 Internal Only 的正文、客戶名稱、專案代號、原始 Issue、內部工具設定、
組織操作流程、受限圖解、存取權杖、登入憑證或限時圖片下載網址。
Insyde Know-how 保留學習入口；授權教材需透過組織另外提供的管道取得。
網站沒有假登入，也沒有以 CSS 隱藏受限資料。

## 操作與資料保存

- 左側導覽切換區域；手機上方導覽可左右滑動。
- 點圖可開啟原尺寸；教材目錄可跳到段落。
- 搜尋支援術語與說明文字，也可按分類篩選。
- 已讀與最近基礎練習分數僅保存於目前瀏覽器的 localStorage。
- Learning Progress 可匯出紀錄或清除本機資料；沒有跨裝置同步。
- PM 練習文字只保留於當前頁面，請在離開前下載；請使用虛構資料。
- 選擇題分數與已讀紀錄不代表 L3/L4 能力認證，也不會更動教材追蹤狀態。

## 檔案

- index.html：網站入口。
- assets/styles.css：響應式版面。
- assets/app.js：導覽、教材閱讀、搜尋、練習與進度。
- assets/content.js：本次整合的通用教材正文。
- assets/images/：三張原始圖解。
- CONTENT-NOTES.md：來源、編輯說明與維護範圍。
- .nojekyll：使用靜態檔案發布。

## 驗證

已檢查 JavaScript 語法、桌面與 390px 手機首頁、圖片載入、術語搜尋及無結果提示、
開機階段切換、已讀重新載入保存、8 題評分與重做清除。
本包為可部署成品；尚未上傳 GitHub 或建立公開網址。
