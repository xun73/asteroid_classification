# 小行星軌道數據探究平台 (Asteroid Orbit Data Exploration Platform)

[中文說明](#中文說明) | [English Description](#english-description)

---

## 中文說明

這是一個專為地球科學教學設計的互動式大數據探究工具，旨在幫助學生透過視覺化手段深入了解太陽系的動態結構。

### 🌟 程式特點
* **自定義數據分析**：使用者可自行上傳從 Minor Planet Center 網站下載的 `MPCORB.DAT` 或是其他小行星、彗星的資料，並根據探究需求調整 X 軸與 Y 軸參數（如半長軸、離心率、軌道傾角、絕對星等）。
* **天體族群分類**：內建自動分類算法，可呈現近地小行星 (NEA)、主小行星帶 (Main Belt)、特洛伊群 (Trojans) 及海王星外天體 (TNO) 的空間分佈。
* **專業級視覺化**：整合 Plotly.js，支援上萬筆數據的流暢縮放、選取與即時資訊顯示。
* **隱私與效能**：採純客戶端 (Client-side) 技術，數據在瀏覽器本地處理，不需上傳至伺服器。

### 🚀 使用方式
1. 從 [MPC 官網](https://www.minorplanetcenter.net/iau/MPCORB.html) 下載 `MPCORB.DAT`。
2. 將檔案拖曳至網頁中。
3. 透過下拉選單切換參數，觀察小行星的分類特性。

---

## English Description

An interactive big-data exploration tool specifically designed for Earth Science education, helping students understand the dynamic structure of the Solar System through visualization.

### 🌟 Key Features
* **Custom Data Exploration**: Upload your own  Minor Planet Center asteroid orbital element data (`MPCORB.DAT`) and adjust various parameters to visualize asteroid classifications.
* **Asteroid Classification**: Features built-in algorithms to automatically categorize objects into Near-Earth Asteroids (NEA), Main Belt, Trojans, and Trans-Neptunian Objects (TNO).
* **Professional Visualization**: Integrated with Plotly.js to support smooth zooming, selection, and real-time hover info for tens of thousands of data points.
* **Privacy & Performance**: Powered by client-side technology. All data is processed locally in the browser, ensuring privacy and eliminating server latency.

### 🚀 How to Use
1. Download `MPCORB.DAT` from the [official MPC website](https://www.minorplanetcenter.net/iau/MPCORB.html).
2. Drag and drop the file into the platform.
3. Toggle different orbital elements and parameters to explore asteroid categories.


- **Data Source**: [Minor Planet Center (MPC)](https://www.minorplanetcenter.net/)

## 👨‍🏫 作者 / Author
**陳韋喨 (Wei-Liang Chen)** 台中市立惠文高中 地球科學老師  
*Earth Science Teacher, Taichung Municipal Hui-Wen High School, Taiwan.*
