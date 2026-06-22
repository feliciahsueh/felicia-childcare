# Felicia Childcare v15

## 本版更新

- Availability：`台北 Taipei` 標籤字級調小，與時間膠囊文字一致。
- Availability 手機版：`台北 Taipei` 會顯示在 `×` 後方，並對齊原本時間膠囊的位置。
- About：「其他 / Notes」新增拍照與家庭隱私說明。

## 上傳方式

1. 將本 ZIP 內的 `index.html` 上傳或覆蓋到 GitHub Pages 專案根目錄。
2. 本 ZIP 不包含 `images` 資料夾，請自行保留 / 上傳圖片。
3. 請確認以下圖片路徑存在：
   - `images/felicia-childcare-wordmark-transparent.png`
   - `images/felicia-childcare-logo-transparent-600.png`
   - `images/atmosphere_01.png`
   - `images/atmosphere_02.png`
   - `images/atmosphere_03.png`
   - `images/certificate_childcare_redacted.jpg`
   - `images/certificate_police_clearance_redacted.jpg`
   - `images/moment_01.jpg` ～ `images/moment_04.jpg`
   - `images/feedback_01.jpg`、`images/feedback_02.jpg`

## Google Sheets Note 欄位

若某日期要顯示台北標籤，請在該日期資料列的 `Note` 欄位填寫：

```text
台北 Taipei
```

只有完全符合 `台北 Taipei` 的 Note 會顯示；其他 Note 不會顯示在網站 Availability 月曆上。

## 測試重點

- Availability 可正常讀取 Google Sheets。
- Available 時段仍可正常開啟選擇時段視窗。
- 加入詢問後，會自動開啟「已選詢問時段」視窗。
- LINE 複製與跳轉正常。
- `Note = 台北 Taipei` 時，Unavailable / Full 日期顯示 `× 台北 Taipei`。
- 手機版 `台北 Taipei` 標籤與 `×` 在同一列，並對齊時間膠囊位置。
- About > 其他 / Notes 顯示拍照與家庭隱私說明。
