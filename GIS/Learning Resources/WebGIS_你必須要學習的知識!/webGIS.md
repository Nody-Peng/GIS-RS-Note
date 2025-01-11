# 你必須要知道該學哪些東西!

---

## 學習優先順序!

- [ ] Leaflet（入門首選）
  > **原因：**
  > 簡單易學，適合初學者。
  > 基本的地圖操作（如標記、圖層切換）能快速上手，建立對地圖應用的基礎概念。

* **學習目標：能夠建立互動式地圖，顯示基礎地圖圖層，並添加標記、彈出框等簡單功能。**

- [ ] Openlayer（進階地圖功能）
  > **原因：**
  > 支援更複雜的地圖功能和投影系統，能夠處理多樣化的地圖來源。
  > 是 Leaflet 的進一步提升，學習後能夠對地圖進行更高自由度的操作。

* **學習目標：熟悉多種地圖來源的整合，能夠自訂地圖樣式，並處理地理數據可視化。**

- [ ] CesiumJS（3D 地圖入門）
  > 原因：
  > 在熟悉 2D 地圖後，學習 3D 地圖的概念和技術，進一步提升地理可視化能力。
  > CesiumJS 的學習門檻較高，但功能強大，能處理真實 3D 場景。

* **學習目標：能夠使用 CesiumJS 展示 3D 地形、衛星影像，並進行簡單的空間分析。**

- [ ] ArcGIS API for JavaScript（高階 GIS 系統）
  > 原因：
  > 適合需要開發完整 GIS 應用的需求，學習曲線相對陡峭，但提供豐富的 GIS 工具。
  > 學習此工具後，能開發專業級 GIS 應用，具備強大的數據分析和視覺化能力。

* **學習目標：掌握空間分析、地理處理工具，並與 ArcGIS 平台整合，實現高級 GIS 功能。**

- [ ] geoserver（地理數據伺服器）
  > 原因：
      當需要將地理空間數據分發給多個客戶端時，Geoserver 是不可或缺的工具。
      最後學習 Geoserver，能將之前所學技術整合，進行數據共享與發布。

* 學習目標：熟悉 Geoserver 的配置與數據發布，能將數據服務提供給 Leaflet、OpenLayer 等前端工具。

---

# 以下將會分述這幾種技術!

## Leaflet

> 概念：
> Leaflet 是一個輕量級的開源 JavaScript 地圖庫，專門用於建構互動式地圖應用。它具備簡單易用的 API，適合處理基本的地圖視覺化需求。

- 優點：

  1. 輕量且效能優秀。

  2. 支援多種地圖圖層，如 OpenStreetMap。

  3. 方便整合第三方插件，功能擴展性強。

**適用場景**：適合需要快速部署輕量地圖應用的專案，例如旅遊地圖、事件追蹤。

- 資源：

  1. 官方網站：https://leafletjs.com

  2. 文件與範例：https://leafletjs.com/examples.html

## CesiumJS

> 概念：
> CesiumJS 是一個用於建構 3D 地球和地理空間數據視覺化的開源 JavaScript 庫。它可以呈現大規模 3D 影像與地理資訊。

- 優點：

  1. 支援真實 3D 視覺化。

  2. 可呈現地理資料如 3D 模型、衛星影像、地形數據。

  3. 高性能，適合處理大量數據。

**適用場景**：適合需要高精度 3D 地理視覺化的專案，如城市規劃、飛行模擬。

- 資源：

  1. 官方網站：https://cesium.com/platform/cesiumjs/

  2. 文件與範例：https://cesium.com/learn/cesiumjs-learn/

## ArcGIS API for JavaScript

> 概念：
> ArcGIS API for JavaScript 是由 Esri 提供的強大地圖 API，用於開發高階地理資訊系統 (GIS) 應用程式。它整合了多種 GIS 功能。

- 優點：

  1. 提供豐富的 GIS 工具，例如空間分析、地理處理。

  2. 完美支援 ArcGIS 平台的數據與服務。

  3. 功能全面，適合高需求的 GIS 專案。

**適用場景**：適合需要複雜 GIS 功能的應用，如城市基礎建設管理、資源分配分析。

- 資源：

  1. 官方網站：https://developers.arcgis.com/javascript/latest/

  2. 教學與範例：https://developers.arcgis.com/javascript/latest/sample-code/

## OpenLayer

> 概念：
> OpenLayer 是一個開源的 JavaScript 庫，專為在網頁上展示動態地圖而設計。它支持多種地圖源，包括 Google Maps、Bing Maps、OpenStreetMap。

- 優點：

  1. 支援多種地圖來源和投影方式。

  2. 功能全面，能夠實現自訂地圖樣式和互動。

  3. 開源且社群活躍，資源豐富。

**適用場景**：適合需要多元地圖來源與高自由度自訂的專案，如氣象地圖、運輸規劃。

- 資源：

  1. 官方網站：https://openlayers.org

  2. 教學與範例：https://openlayers.org/en/latest/examples/

## Geoserver

> 概念：
> Geoserver 是一個開源的伺服器，用於發布、共享和編輯地理空間數據。它支持多種標準協議，如 WMS、WFS，方便 GIS 數據的分發。

- 優點：

  1. 支援多種 GIS 格式和標準協議。

  2. 易於整合其他地圖工具，如 Leaflet、OpenLayer。

  3. 開源且社群支持良好。

**適用場景**：適合需要分發大量地理空間數據或進行 GIS 數據共享的專案，如環境監測系統、地理數據中心。

- 資源：

  1. 官方網站：https://geoserver.org

  2. 文件與教學：https://docs.geoserver.org/latest/en/
