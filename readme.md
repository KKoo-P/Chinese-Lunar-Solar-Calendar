📅 萬年曆公曆農曆對照表

一個輕量、現代化且支援 PWA (Progressive Web App) 的萬年曆網頁應用程式。提供公曆與農曆對照、干支生肖、二十四節氣、黃曆宜忌查詢等功能，支援手機桌面安裝與完全離線使用。

✨ 功能特點

📍 自動跳轉今天：開啟網頁時自動定位並高亮顯示當前系統日期。

🗓️ 公農曆詳細對照：顯示干支紀年、生肖、農曆月日、二十四節氣及當日黃曆宜忌。

🔍 快速搜尋功能：支援關鍵字搜尋節氣、節日、宜忌（如「端午」、「立春」、「嫁娶」等）。

🌙 深色模式 (Dark Mode)：自動偵測系統主題，並提供一鍵手動切換。

📱 PWA 手機桌面應用：可將網頁安裝至 iPhone (iOS) 及 Android 手機主畫面，像原生 App 一樣流暢運作。

⚡ 完全離線可用：內建 Service Worker 快取機制，即使沒有網路也能隨時查閱日曆。

📐 響應式版面：支援網格與列表雙檢視模式， perfect 適配手機、平板與電腦螢幕。

📁 專案檔案結構

.
├── index.html       # 萬年曆主頁面 (含 UI、樣式與互動邏輯)
├── manifest.json    # PWA 清單配置文件 (應用程式名稱、主題色、圖示)
├── sw.js            # Service Worker 腳本 (負責離線資源快取)
├── icon.svg         # 高解析度 SVG 向量應用程式圖示
└── README.md        # 專案說明文件



📲 如何安裝至手機桌面 (PWA)



🍎 iOS (iPhone / iPad)

使用 Safari 瀏覽器 開啟您的 GitHub Pages 網址。

點擊螢幕底部的 分享 圖示（帶有向上箭頭的方塊）。

向下滾動選單，點擊 「加入主畫面」 (Add to Home Screen)。

確認名稱後點擊右上角 「新增」 即可。



🤖 Android (安卓系統)

使用 Chrome 瀏覽器 開啟您的 GitHub Pages 網址。

點擊右上角的選單圖示 ⋮。

點擊 「安裝應用程式」 (Install app) 或 「新增至主螢幕」 (Add to Home screen)。

按照指示確認安裝。



🛠️ 技術棧

前端核心：HTML5, CSS3 (CSS Variables), JavaScript (ES6+)

農曆核心算法：lunar-javascript

PWA 技術：Web App Manifest, Service Worker API (Cache First 策略)

📄 授權條款

本專案基於 MIT License 開源。

