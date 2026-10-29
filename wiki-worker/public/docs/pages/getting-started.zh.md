# 快速開始

本頁說明如何取得原始碼、在本機預覽首頁與任一範例。

## 前置需求

| 項目 | 說明 |
|------|------|
| 瀏覽器 | 任一支援 ES Module 的現代瀏覽器（Chrome、Safari、Firefox、Edge） |
| HTTP 靜態伺服器 | 首頁以 `fetch('./README.md')` 讀取 `README.md`，`file://` 協定下會失敗；範例頁本身可直接開檔 |
| 網路 | 每個範例都從 `cdn.jsdelivr.net` 載入 Font Awesome（其中 32 個另載入 PDRenderKit 或 QuickUI）；首頁與 5 個範例另從 `fonts.googleapis.com` 載入字型 |
| Dart Sass（選用） | 只有要改樣式時才需要，透過 Node.js 的 `npx sass` 執行 |

## 取得原始碼

```bash
git clone https://github.com/pardnio/demo-web.git
cd demo-web
```

## 本機預覽

```bash
python3 -m http.server 8080 || { echo "port 8080 已被佔用"; exit 1; }
```

| 網址 | 內容 |
|------|------|
| `http://localhost:8080/` | 首頁：以 PDMarkdownKit 渲染 `README.md`（專案概覽） |
| `http://localhost:8080/target/20241220/` | 單一範例（資料夾名即製作日期） |

## 線上瀏覽

- GitHub Pages：<https://pardnio.github.io/demo-web/>
- 本文件站在 `https://demo-web.pardn.io/target/<YYYYMMDD>/` 提供 repo `target/` 目錄的副本，也就是各範例 `<head>` 宣告的 canonical 網址；站內每個範例頁顯示截圖並連到實際執行的範例。

## 下一步

- [專案結構](/zh/project-structure)：資料夾命名與每個範例的組成
- [樣式工作流程](/zh/styling-workflow)：如何重新編譯 SCSS
