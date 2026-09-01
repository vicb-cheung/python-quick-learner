# 讀懂 ecgtizer 的 Python 課

一份個人 Python 學習紀錄：跟著 `ecgtizer-neurokit2`（一個真實的 ECG 訊號分析專案）的原始程式碼，從完全新手開始學 Python。每一課都直接拆解專案裡真的存在的一行程式碼。

發佈成 GitHub Pages 之後，網站在：`https://<你的 GitHub 帳號>.github.io/<這個 repo 的名稱>/`

## 結構

- `index.html` — 課程首頁，列出所有課程
- `lessons/` — 每一課一個 HTML 檔案
- `reference/` — 快速參考卡（語法備忘）
- `assets/style.css` — 共用樣式

## 更新

這個網站是純靜態頁面，不會自動生成新內容。想要新的一課時，回到跟 Claude 的對話裡說一聲，產生新的 HTML 檔案加進 `lessons/`、更新 `index.html`，再 `git commit && git push` 就會自動更新到 GitHub Pages（通常 1-2 分鐘內生效）。
