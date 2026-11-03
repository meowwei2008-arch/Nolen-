# 英中單字卡 v1.5 — GitHub Pages 發布包

本資料夾檔案須上傳到 GitHub 儲存庫的**根目錄**（不要多包一層資料夾）。

1. 登入 GitHub，建立 Public repository，例如 `vocab-cards`，並選擇新增 README（或建空儲存庫後上傳檔案）。
2. 在儲存庫按 **Add file → Upload files**，將本資料夾的 `index.html`、`service-worker.js`、`manifest.webmanifest`、`icons/` 目錄（含兩張 PNG 圖）放到儲存庫根目錄。`.nojekyll` 是可選檔案。
3. 到 **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save**。
4. GitHub Pages 公開網址通常會是 `https://帳號.github.io/儲存庫名稱/`，等 GitHub 顯示實際發布網址後再開啟確認。
5. 用 Android Chrome 開啟該 HTTPS 網址，點選選單 → 安裝應用程式 / 加到主畫面。

**資料移轉**：PWA 會使用和單檔 HTML 不同的儲存空間。先在舊 App 匯出 JSON，進入 PWA 後再還原。JSON 還原會覆蓋目前資料。

**隱私提醒**：GitHub Pages 公開網站的原始碼與圖示可被任何人看到，**不要把自己的單字資料 JSON 備份、帳號密碼或私密文件上傳到儲存庫**。單字資料仍應留在手機本機儲存。

**離線限制**：首次至少要連網載入成功並安裝快取；Cambridge 字典需連網；語音的離線能力依手機支援。建議真機測試一次飛航模式重新開啟。
