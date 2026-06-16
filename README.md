# Felicia Childcare Website Update v10

## 更新內容

1. Availability 選擇流程調整
   - 使用者在「選擇詢問時段」視窗按下「加入詢問」後，會自動開啟「已選詢問時段」視窗。
   - 使用者可直接看到「複製後用 LINE 詢問」按鈕，不需要滑到頁面底部尋找。
   - 原本底部 floating basket 仍保留，方便使用者繼續查看或修改已選時段。

2. Header 維持目前方向
   - 無整條框線，只保留下方細線。
   - 左上方 logo 路徑維持：`images/felicia-childcare-wordmark-transparent.png`
   - 三個頁面選單維持膠囊按鈕格式。

## GitHub 上傳方式

請將 `index.html` 上傳到 GitHub 專案根目錄，覆蓋原本的 `index.html`。

## 圖片資料夾提醒

本 ZIP 不包含 `images` 資料夾。請自行確認 GitHub 專案中存在以下檔案：

- `images/felicia-childcare-wordmark-transparent.png`
- `images/atmosphere_01.png`
- `images/atmosphere_02.png`
- `images/atmosphere_03.png`
- `images/certificate_childcare_redacted.jpg`
- `images/moment_01.jpg`
- `images/moment_02.jpg`
- `images/moment_03.jpg`
- `images/moment_04.jpg`
- `images/feedback_01.jpg`
- `images/feedback_02.jpg`

## Logo 透明背景提醒

若網站 header 的 logo 顯示灰白網格，代表目前上傳的 logo 圖檔本身可能不是透明背景，而是把透明網格存成了圖片內容。

請改用真正透明背景的 PNG，並將檔名命名為：

`images/felicia-childcare-wordmark-transparent.png`

## 測試重點

上傳後建議測試：

1. 手機版 Availability 點選任一可預約時段。
2. 選擇開始 / 結束時間後，點「加入詢問」。
3. 確認會自動開啟「已選詢問時段」視窗。
4. 點「複製後用 LINE 詢問」，確認可複製並開啟 LINE。
5. 確認 Google Sheets availability 資料可正常載入。
6. 確認 header logo 沒有灰白網格背景。
