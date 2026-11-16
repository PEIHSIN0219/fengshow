# 豐說享秀官網 V2 — 靜態網站 MVP

## 檔案
- `index.html`：所有網站內容、SEO 與外部連結
- `styles.css`：視覺樣式、RWD 手機版
- `script.js`：手機選單、頁尾年份
- `assets/favicon.svg`：網站圖示

## 本機預覽
直接用 Chrome / Edge 開啟 `index.html`。不需要安裝套件或執行伺服器。

## 部署至 GitHub Pages
1. 在 GitHub 建立公開 Repository（例如 `fengshow-v2`）。
2. 將 `index.html`、`styles.css`、`script.js` 和 `assets/` 資料夾放在 Repository 根目錄。
3. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save。
4. 幾分鐘後開啟 `https://你的帳號.github.io/fengshow-v2/`。

## 搬遷至智邦或其他付費主機
使用 FTP/SFTP 或主機控制台，把相同的檔案和 `assets/` 資料夾上傳至網站公開目錄（依主機商指示，常見為 `public_html`）。不需要資料庫、Node.js、PHP 或編譯。

## 上線前務必確認
- 網站目前為**提案版**，並非已核准的正式官方網站。
- 第四屆師資與課程資料依 2026 年 ACCUPASS 公開資訊整理，若要正式上線請再次核對。
- 「講者邀約與合作課程」屬未來發展方向，網站沒有假設已開放收費。
- 請替換舞台示意視覺為**取得授權的真實活動照片**，補入官方 Logo、歷屆活動及影片資料。
- 目前聯絡 Email 取自第四屆公開活動頁；正式上線前請取得團隊同意。
- 建議補上個資告知、隱私權政策，若未來改用表單蒐集資料，須依法告知蒐集與利用方式。
- 字體使用 Google Fonts；若要完全離線運作，可移除 CSS 第一行 `@import`，使用系統字體。

## 來源
- 品牌緣起：https://cancer.commonhealth.com.tw/article/359
- 2026 第四屆：https://www.accupass.com/event/2601101356044349215660
- 2025 兒童版：https://www.accupass.com/event/2505041243272101542310

## 內容修改
- 導覽、文案、課程、師資、聯絡方式均在 `index.html`。
- 顏色在 `styles.css` 開頭 `:root` 變數。
- 可在不改變網站技術架構的情況下新增獨立 HTML 頁面，例如 `speakers/index.html`、`courses/index.html`。
