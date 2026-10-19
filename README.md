# 人生選擇扭蛋機（Life Gacha）

以復古扭蛋機替日常選擇增加驚喜的靜態網頁。

## 功能

- 吃什麼、做什麼、命運挑戰、自訂扭蛋四種主題
- 自訂 2–30 個選項與獨立稀有度
- 最近 20 次抽選紀錄
- 使用 LocalStorage 在目前瀏覽器保留自訂選項與紀錄
- 支援手機版面與減少動態效果偏好

## 本機開啟

直接以瀏覽器開啟 `index.html`，無需安裝套件或執行建置。

## 發布到 GitHub Pages

1. 在 GitHub 建立公開儲存庫（例如 `life-gacha`）。
2. 將 `index.html`、`.nojekyll` 與本檔上傳至儲存庫根目錄並提交到 `main` 分支。
3. 進入儲存庫的 **Settings → Pages**。
4. 在 **Build and deployment → Source** 選擇 **Deploy from a branch**。
5. 選擇 **main** 分支與 **/(root)**，按 **Save**。
6. 等待部署完成，使用 Pages 設定頁顯示的網址開啟網站。

一般專案網站網址為 `https://帳號.github.io/儲存庫名稱/`。
後續更新 `main` 分支的網頁檔案，GitHub Pages 會重新部署。

官方說明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 檔案

- `index.html`：網頁、樣式與互動程式
- `.nojekyll`：停用 Jekyll 處理，直接發布靜態檔案
- `人生選擇扭蛋機_規格書.md`：作品規格