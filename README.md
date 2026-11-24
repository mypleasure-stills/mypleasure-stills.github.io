# Mypleasure Stills

平面攝影作品網站。正式發布網址：https://mypleasure-stills.github.io/

來源為 `/Users/liao/Documents/Liao-Agent/mypleasurefilm-site` 的 `Photography/` 與 `shared/`，來源版本 `7185661`。攝影頁已移到本專案根目錄；原網站、影片頁與既有網址由原專案維持。

## 維護規則

- 保留全部作品卡、照片與分類。前八個作品為使用者手動排序，不得自行改變次序；其餘作品沿用目前編排；台灣登山國際研討會目前位於第20個。
- 不顯示照片總數：作品列表、相簿頁及放大看圖皆適用。
- `js/gallery-data.js` 保存相簿名稱、日期、標籤與照片次序。更新時同步提高 `gallery.html` 的資料檔版本字串，避免舊快取。
- 分享標題為「Mypleasure Stills｜平面攝影作品」，預覽圖位於 `images/social-preview.jpg`。首頁與相簿頁的 metadata 使用上述正式網址。
- 原始照片與作品卡的相對路徑已保留；共用導覽位於 `shared/`。

## 發布

這是無須建置的靜態網站，以 GitHub Pages 發布專案根目錄。`.nojekyll` 用於直接提供靜態檔案；本目錄不需要套件安裝或生成步驟。
