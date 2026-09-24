# 陳懷萱個人網站（部落格版型）

純 HTML／CSS 的靜態網站，收錄「關於我」與 Medium 上所有已發表文章（共 50 篇）。

## 檔案結構

- `index.html` — 首頁（部落格文章列表，最新 12 篇＋側欄）
- `about.html` — 關於我（品牌故事：展齡、工作方法、代表現場）
- `articles.html` — 全部文章（依年份分組，可依專欄分類篩選）
- `practice.html` — 跨域實作軌跡（學經歷、著作、場域實踐紀錄）
- `works.html` — 實踐成果集（數位策展成果、課程探索實作成果）
- `media.html` — 現聲說法（廣播、Podcast 與文字專訪，共 9 則）
- `collaborate.html` — 合作邀請（四類服務、曾合作單位、聯絡方式）
- `articles/` — 每一篇文章的獨立頁面（含上一篇／下一篇）
- `assets/style.css` — 網站樣式

## 放上 GitHub Pages 的步驟

1. 到 [github.com](https://github.com/) 註冊帳號並登入。
2. 右上角「+」→「New repository」。
   - Repository name 建議取 `你的帳號名稱.github.io`（例如帳號叫 `huaihsuan`，就取 `huaihsuan.github.io`），網址最簡潔。
   - 設為 Public，其他保持預設，按「Create repository」。
3. 進入該 repository，點「Add file」→「Upload files」。
4. 把這個資料夾裡的**所有檔案與資料夾**（`index.html`、`about.html`、`articles.html`、`assets/`、`articles/`）整個拖進去上傳（要先解壓縮，不要上傳 zip）。
5. 按「Commit changes」。
6. 到「Settings」→ 左側「Pages」。
7. 「Build and deployment」的 Branch 選 `main`、資料夾選 `/ (root)`，按「Save」。
8. 等 1–2 分鐘後重新整理，頁面上會出現網站網址（通常是 `https://你的帳號名稱.github.io/`）。

## 之後要更新內容

- 改文字：在 GitHub 網頁上點該檔案 → 右上角鉛筆圖示編輯 → Commit。
- 加新文章或改版型：回來跟我說，我重新產生整批檔案給妳。

## 說明

- 文章內的圖片連結回 Medium 的公開圖片網址（cdn-images-1.medium.com），網站上線後讀者可以正常看到，不需另外處理。
- 有 2 篇很短的「感謝回覆」貼文（非正式文章）沒有收錄，其餘所有已發表文章都完整收錄。
- 專欄分類是從文章標題的括號標籤整理出來的，相近的系列名稱已歸併（例如「劇做老年隨想」「劇做老年工作坊」都併入「劇做老年練功房」）。沒有標籤的 19 篇歸在「其他」。
- 「關於我」頁面文字是草擬版本，可再修改。
