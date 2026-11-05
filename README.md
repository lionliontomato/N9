# Neniの歌單 - GitHub Pages 版 (修正版 v2)

這一版**以原 NIAN 網站備份的 style(4).css 與 index(6).html 為基礎**，保留版面尺寸：主容器 1180px、卡片最小寬度 230px、卡片高度/間距與桌機手機響應式比例。僅替換主題色、圖片、名稱和 Google 試算表。

## 背景
使用之前提供的「霧藍水面上的雛菊漣漪.png」作品；手機版保留完整直幅，桌機版是同作品以模糊延展兩側構成的橫幅，不是新畫的替代背景。

## 資料
指定試算表 `18BWphlrXzA3VC765bpRVuwsu62Spnuk4Pp4j5DXrsUg`，預設 gid=0。如資料在不同分頁，請在 script.js 更改 `SHEET_GID`。試算表須設為可供網站存取。每次更新帶隨機參數且不保存舊歌單。若讀取失敗會清空並顯示錯誤。

## GitHub Pages
解壓縮後將此資料夾**內部檔案**放在 Repository 根目錄，進入 Settings → Pages → Deploy from a branch → main / (root) → Save。請記得刪除舊版已不存在的背景檔案，以免混淆。

## 注意
原參考網站未能透過本環境直接連線抓取即時版本；版面是依保留在使用者檔案庫的 NIAN 原始 CSS 與 HTML 精確還原，並非即時截圖逐像素驗證。
