# manifest.json
此檔案為對外掛程式的描述及定義，像是名稱、程式描述、版本號等等的定義。

## 參考資料
[Chrome Developer](https://developer.chrome.com/extensions/manifest)

## 必輸欄位
manifest.json中有三個必輸的參數: `manifest_version`、`name`、`version`
* `manifest_version`: 定義檔格式的版本，在Chrome 18時全面改為2，如果此外掛沒有要在Chrome 18以前的版本使用的話請直接設為2。
* `name`: 外掛程式名稱，最多45個字元。
* `version`: 程式版本號，Chrome會以此號碼決定要不要更新外掛程式，假設使用者安裝的程式版本小於現在發布的版本，Chrome就會自動更新。

## 建議輸入欄位
此類別為Chrome建議輸入的欄位但不是必輸，不輸入會影響顯示的品質(例: 圖示、描述等)

* `description`: 外掛程式描述，最多不能超過132字元。此描述會顯示在Chrome Web Store上。
* `icons`: 設置外掛圖標，有三種大小的圖標(16\*16、48\*48、128\*128)，支援PNG、BMP、GIF、ICO、JPEG格式。