# 大二影展專題：《半畝方糖》網頁專案

本專案為逢甲大學行銷學系大二影展專題介紹網頁，聚焦臺中東區「帝國製糖廠臺中營業所與星泉湖畔」，透過「出站即達的都市慢活文化綠洲」的核心定位，翻轉大眾長期以來對歷史古蹟老舊、無聊的刻板印象。

## 專案功能特色
- **SEO 最佳化**：包含完整的 Meta 標籤、Open Graph 社交協議與語意化 HTML5 標記。
- **RWD 響應式佈局**：支援手機、平板與桌上型電腦，影片與地圖採 16:9 自適應縮放與響應網格。
- **CSS Grid & Flexbox 系統**：實作深焙咖啡色調（`#4a2e1b`）與泛黃紙張色（`#fdf5e6`）之雙欄側邊導覽與卡片網格。
- **檔案模組化切割**：CSS 樣式表獨立抽離至 `css/style.css`，圖片資源統籌於根目錄與 `images/`。
- **多分頁獨立架構**：劃分專題首頁 (`index.html`)、分鏡剖析 (`film.html`)、地點介紹 (`location.html`) 與團隊企劃 (`team.html`)。

---

## Vibe Coding 指令紀錄 (Prompts Log)

本專案運用 Vibe Coding 模式，透過明確架構、情緒調性與技術邊界進行人機協同開發。以下為生成此專案的核心提示詞紀錄：

### Prompt 1：專案架構與基礎骨幹建立
> **Prompt:**  
> 「請扮演資深前端工程師與數位行銷策展人。我正在製作大二影展專題介紹網頁，主題是針對臺中帝國糖廠與星泉湖的短片企劃《半畝方糖》。  
> 請幫我規劃一個包含分頁（首頁 index.html、分鏡剖析 film.html、團隊企劃 team.html）的靜態網站。  
> 規範要求：  
> 1. 具備頂端導覽列與側邊選單欄。  
> 2. 具有完整的 SEO Meta 標籤（含 Title, Description, Keywords, Open Graph）。  
> 3. 需將樣式抽離至獨立的 `css/style.css`，圖片放置於 `images/` 資料夾。  
> 4. 採用語意化 HTML5 標籤。」

### Prompt 2：CSS Grid 系統與 RWD 跨裝置適配
> **Prompt:**  
> 「請為上述影展專案撰寫完整的 `css/style.css`，滿足以下要求：  
> 1. 版面採用雙欄結構（左側邊欄 + 右側主內容），並使用 CSS Grid 實作卡片響應式排列（`repeat(auto-fit, minmax(240px, 1fr))`）。  
> 2. 影片區塊需設定 16:9 自適應 RWD 比例，在手機小螢幕上不會破版。  
> 3. 使用 Media Queries 設定斷點（900px），在行動裝置自動轉為單欄並摺疊導覽選單。」

### Prompt 3：嵌入專題影片與分鏡內容精修
> **Prompt:**  
> 「請將 YouTube 影片以 Privacy-Enhanced 模式（youtube-nocookie.com）無邊框嵌入首頁影片區。同時在 `film.html` 內加入分鏡表（Shot 2-1、Shot 2-5、Shot 3-8）的運鏡與音效重點，展現專業影展專案水平。」

### Prompt 4：版面重構與復古咖啡色調調整
> **Prompt:**  
> 「請幫我調整網站版面為左側固定標語欄 + 右上角選單，色調改為深焙咖啡色（#4a2e1b）與泛黃舊紙張色（#fdf5e6），並採用思源宋體營造懷舊文青手帳風格。將 CSS 獨立抽離，將各分頁程式碼完全獨立切割。」

### Prompt 5：獨立地點介紹頁面與外部資源串接
> **Prompt:**  
> 「請新增獨立的 `location.html` 頁面放在右上角選單中，內容包含帝國製糖廠臺中營業所的地標簡介、圖片（`1.png`）、連至『臺中觀光旅遊網』的外部連結，以及 Google Maps 地圖 iframe 嵌入碼。」

---

## 專案部署連結

1. **Prompt 說明檔 (GitHub)**：  
   `https://github.com/yunching0327-alt/mid_D1577157/blob/main/README.md`
2. **InfinityFree 部署網址**：  
   `http://d1577157midterm.infinityfree.me`
3. **Vercel 部署網址**：  
   `https://d1577157midterm.vercel.app`
