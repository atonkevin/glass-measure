# 眼鏡框參數量測工具

基於WebXR的眼鏡框參數量測Web應用程式。

## 功能特色
- 量測眼鏡框的五個關鍵參數(A-E)
- 支援AR量測(需要支援WebXR的裝置)
- 支援手動輸入資料
- 可儲存及匯出量測結果

## 使用方式
1. 存取: https://gitlab.atonkevin.tk/glass-measure
2. 使用iPhone的Safari瀏覽器開啟
3. 依照畫面提示進行量測

## 系統需求
- iPhone 12或更新機型(需要LiDAR)
- iOS 14.0以上版本
- Safari瀏覽器

## 本地開發
1. 複製專案:
   ```bash
   git clone https://gitlab.atonkevin.tk/atonkevin/glass-measure.git
   ```
2. 使用本地伺服器測試:
   ```bash
   python3 -m http.server 8000
   ```
3. 存取 http://localhost:8000

## 部署說明
- 推送至main分支後會自動部署
- 可在專案Settings > Pages查看部署狀態