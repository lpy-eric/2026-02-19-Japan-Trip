🏔️ 東京長野滑雪五日遊 (Tokyo Nagano Ski Trip App)

這是一個基於 Vue.js 3 和 Tailwind CSS 構建的現代化單頁旅遊網頁應用程式 (Single Page Application)。

專為滑雪行程設計，整合了「互動式行程表」與「實用旅遊工具」，並採用無伺服器 (Serverless) 的單一檔案架構，無需複雜的建置過程即可直接運行。

✨ 主要特色 (Features)

1. 📱 極致的響應式設計 (Mobile-First UX)

iPhone 16 Pro Max 優化：針對大螢幕手機進行了佈局微調，確保在行動裝置上的閱讀體驗極佳。

玻璃擬態 (Glassmorphism)：使用半透明模糊背景與細緻陰影，營造現代且具有雪國氛圍的質感。

自適應圖片：封面與行程圖片會根據裝置尺寸自動調整高度與裁切範圍，確保視覺焦點準確。

2. 🗓️ 互動式行程時間軸 (Interactive Itinerary)

手風琴式摺疊 (Accordion Style)：點擊日期即可展開或收合詳細行程，讓畫面保持整潔。

視覺化標籤：針對「交通」、「美食」、「滑雪」等不同活動類型設計專屬標籤。

重要活動高亮：使用特殊的顏色標記重點行程（如新幹線時間、重要晚餐）。

內嵌圖片展示：行程卡片內直接整合景點或美食圖片，增加臨場感。

3. 🌐 隨身翻譯助手 (Travel Translator)

內建雙向翻譯：整合 MyMemory API，提供免費且即時的「繁體中文 <-> 日文」互譯功能。

語音朗讀 (Text-to-Speech)：利用瀏覽器原生的 Web Speech API，可直接發音翻譯結果，方便與當地人溝通。

直覺切換：提供一鍵切換語言方向的動畫按鈕。

4. 🎨 視覺風格

主題配色：以 Sky Blue (#38BDF8) 與 Snow White (#F0F9FF) 為主調，搭配深藍色文字，完美呼應滑雪主題。

視差滾動感：背景圖片採用固定定位 (background-attachment: fixed)，在滑動頁面時增加層次感。

🛠️ 技術棧 (Tech Stack)

本專案採用 No-Build 策略，所有依賴皆透過 CDN 引入，單一 HTML 檔案即可運作。

核心框架：Vue.js 3 (Global Build) - 處理頁面邏輯、狀態管理 (Reactivity) 與路由切換。

樣式庫：Tailwind CSS - 快速構建響應式與客製化介面。

圖示庫：FontAwesome 6 - 提供豐富的 UI 圖示。

字體：Google Fonts (Noto Sans TC & Montserrat) - 確保中英文顯示美觀。

API：

MyMemory API (翻譯)

Web Speech API (語音合成)

🚀 如何使用 (How to Run)

由於此專案是單一 HTML 檔案結構，您不需要安裝 Node.js 或執行 npm install。

下載 index.html 檔案。

直接雙擊檔案，使用任何現代瀏覽器 (Chrome, Safari, Edge) 開啟。

或者將檔案部署至 GitHub Pages、Netlify 或任何靜態網頁託管服務即可分享給旅伴。

📂 檔案結構

/
└── index.html  # 包含所有 HTML, CSS (Tailwind Config), 和 Vue.js 邏輯的完整檔案


📝 備註

封面圖片來源：Land110602

滑雪背景圖來源：Songchenwen

其餘圖片來自 Unsplash。

Have a nice trip! ⛷️