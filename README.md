# Felicia Childcare Website - v12

## 本次更新

1. Availability 最下方「使用說明 / How to use」改為置左閱讀。
2. Availability 的提醒區塊加入與 header 同寬的分隔線，讓版面更一致。
3. 手機版 header 的 wordmark logo 改為置中，桌機版維持左 logo、右側選單。
4. 電腦版 Gallery 說明文字字級調整為與其他頁面更一致。
5. 電腦版 Words from Parents 的回饋圖片移除框線與米白背景，改為與 Care Moments 更接近的乾淨圖片排版。
6. 保留「加入詢問」後自動開啟「已選詢問時段」視窗的流程。
7. 修正 floating basket 中重複的 LINE 詢問按鈕。

## 上傳方式

請將 `index.html` 上傳到 GitHub 專案根目錄，取代原本的 `index.html`。

ZIP 檔未包含 `images` 資料夾，請自行確認 GitHub 專案中已有以下圖片：

- `images/felicia-childcare-wordmark-transparent.png`
- `images/felicia-childcare-logo-transparent-600.png`
- `images/felicia-childcare-logo-light-bg-600.png`
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

## 測試重點

上傳後建議測試：

1. Availability 是否能正常載入 Google Sheets 時段。
2. 手機版選擇時段後，是否會自動開啟「已選詢問時段」視窗。
3. 「複製後用 LINE 詢問」是否能正常複製並開啟 LINE。
4. 手機版 header wordmark 是否置中且未顯示透明網格。
5. 電腦版 Words from Parents 圖片是否已移除框線背景。
6. About / Gallery / Availability 三頁切換是否正常。
