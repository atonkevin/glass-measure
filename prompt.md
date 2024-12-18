# 眼鏡框參數量測工具

## 實作方案一：基於影像處理的量測方法
使用百格方格紙治具
輸入上下左右四個方向的照片
輸出眼鏡框五個參數

## 實作方案二：基於WebXR的AR量測方法（目前採用）

### 技術架構
- 純Web應用程式(HTML + CSS + JavaScript)
- WebXR API用於AR功能
- iPhone的LiDAR感測器用於精確量測

### 主要功能
1. 量測五個關鍵參數:
   - A: 鏡片寬度
   - B: 鼻橋寬度
   - C: 鏡腳長度
   - D: 鏡框總寬度
   - E: 鏡片高度

2. 兩種量測模式:
   - AR模式: 使用iPhone的LiDAR進行即時量測
   - 手動模式: 直接輸入數值(作為備選)

3. 資料管理:
   - 本地儲存量測歷史
   - 匯出量測結果

### 部署方式
- 使用自架GitLab伺服器託管
- 透過HTTPS存取 (https://gitlab.atonkevin.tk)
- 支援PWA安裝至主畫面

### 設備需求
- iPhone 12或更新機型(需要LiDAR)
- iOS 14.0以上版本
- Safari瀏覽器

### 使用流程
1. 存取Web應用程式 (https://atonkevin.gitlab.atonkevin.tk/glass-measure)
2. 允許相機和AR權限
3. 選擇要量測的參數
4. 使用AR介面進行量測
5. 儲存並匯出結果
