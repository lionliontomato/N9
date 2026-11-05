# Neniの歌單｜GitHub Pages 完整版 v4

## 檔案
- `index.html`：歌單首頁
- `style.css`：網站樣式與桌機／手機背景設定
- `script.js`：Google Sheets 資料讀取、搜尋、分類、隨機抽歌與複製功能
- `copyright.html`：完整著作權聲明與使用條款
- `assets/`：雛菊圖示、桌機與手機背景

## 著作權頁
已補回完整章節：使用限制、允許範圍、第三方內容說明、侵權處理，並保留 `© 2026 LionLionTomato. All Rights Reserved.`。

## 部署
將本資料夾內所有檔案（不是外層資料夾本身）上傳至 GitHub Repository 根目錄，再於 Settings → Pages 選擇 `main` 分支與 `/(root)`。

歌曲資料來源為指定 Google 試算表；讀取失敗時不會顯示舊歌單。


## 主標題試算表連動修正
- H 欄設定名稱、I 欄設定值：`網站標題`（亦支援 `網站主標題`）控制網頁主標題。
- `網站小標題` 控制網頁小標題。
- 網頁主標題與瀏覽器分頁標題會同步更新。
- 已更新 script.js 的版本參數，避免瀏覽器沿用舊版錯誤程式。
