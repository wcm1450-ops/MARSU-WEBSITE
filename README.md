# MARSU Website

## AI-Friendly Static Website

這是一個為 AI Agent 優化設計的靜態 HTML 網站，基於 juoku.com.tw 的設計風格打造。

### 📁 目錄結構

```
MARSU-WEBSITE/
├── index.html              # 主頁
├── about.html              # 關於我們
├── products.html           # 產品頁面
├── services.html           # 服務頁面
├── contact.html            # 聯絡頁面
├── css/
│   └── style.css          # 樣式表
├── api/
│   └── data.json          # 結構化數據 API
├── sitemap.xml            # SEO 站點地圖
├── robots.txt             # 爬蟲指令
└── README.md              # 本文件
```

### 🤖 AI 友善特性

#### 1. **結構化數據**
- 使用 **Schema.org** 標記
- JSON-LD 格式的結構化數據
- 清晰的語義 HTML 標籤

#### 2. **API 端點**
- `api/data.json` - 提供所有公司、產品、服務信息的 JSON 格式
- 機器可讀的數據結構
- 便於 AI 爬蟲解析

#### 3. **SEO 優化**
- 完整的 meta 標籤和 Open Graph 標籤
- `sitemap.xml` - 站點地圖
- `robots.txt` - 爬蟲指令
- 清晰的 URL 結構

#### 4. **語義標記**
- 使用 `<article>`, `<section>`, `<nav>` 語義標籤
- Microdata 標記（itemscope, itemtype 等）
- 清晰的標題層級

### 📄 頁面內容

| 頁面 | 內容 | AI 搜尋友善 |
|------|------|------------|
| index.html | 首頁、公司亮點、精選產品、服務概述 | ✅ |
| about.html | 公司介紹、使命、願景、核心價值、歷史 | ✅ |
| products.html | 產品系列、功能、特性 | ✅ |
| services.html | 服務類別、詳細描述 | ✅ |
| contact.html | 聯絡信息、聯絡表單 | ✅ |

### 🔍 AI 搜尋範例

AI Agent 可以輕鬆搜尋：

```json
// 從 api/data.json 獲取結構化數據
{
  "company": {...},
  "products": [...],
  "services": [...],
  "values": [...],
  "history": [...]
}
```

### 🚀 部署

1. **GitHub Pages**
   ```bash
   git push origin main
   # 在 GitHub 設置中啟用 GitHub Pages
   ```

2. **靜態服務器**
   ```bash
   # Python 3
   python -m http.server 8000
   ```

### ✏️ 內容自定義

編輯以下文件以自定義內容：

- **HTML 文件** - 修改頁面內容和結構
- **api/data.json** - 修改結構化數據
- **css/style.css** - 自定義樣式

### 🔗 重要鏈接

- **結構化數據驗證**: https://schema.org/validator
- **SEO 檢查**: https://www.seobility.net
- **AI 爬蟲友善性**: https://support.google.com/webmasters

### 📧 聯絡信息

- 郵箱: contact@marsu.com
- 電話: +886 2 1234-5678
- 地址: 台灣台北市信義區

### 📄 授權

Copyright © 2026 MARSU. 版權所有。