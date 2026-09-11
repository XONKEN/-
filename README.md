# 燒金紙

純前端、無後端、無 API 的小型 Web App，可直接部署到 GitHub Pages。

## 操作
- 桌面：滑鼠點擊
- 手機：觸控點擊
- 每次金紙完整進入火焰後，計數 +1
- 可快速連點，前一張還在飛時也能丟下一張

## GitHub Pages
把 `index.html` 放在 GitHub repository 根目錄，Settings → Pages → Deploy from branch，選擇主分支與 `/root`。

## 自動煙霧測試
用瀏覽器開啟：`index.html?test=10`
頁面會自動快速投擲 10 張金紙，確認最後顯示 `已燒金紙：10 張` 且所有動畫物件都已清除。
