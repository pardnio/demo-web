# 框架使用

本頁列出每個範例載入的前端框架與版本，對照框架從 PDExtension、PDRenderKit 到 QuickUI 的演進。

## 演進概覽

| 框架 | 範例數 | 載入方式 |
|------|--------|----------|
| PDExtension | 1 | 本地 `js/PDExtension.js`，在原生原型（`String`、`HTMLElement` 等）上擴充方法 |
| PDRenderKit | 28 | `cdn.jsdelivr.net/npm/pdrenderkit@<版本>/dist/PDRenderKit.js`，版本 1.0.0 至 1.5.2 |
| QuickUI | 4 | `cdn.jsdelivr.net/npm/@pardnchiu/quickui@0.6.2/dist/QuickUI.js` |
| 未使用框架 | 5 | 純 HTML + CSS |

PDMarkdownKit 1.6.0 以 ES Module 形式與 PDRenderKit 搭配，用於渲染 Markdown 內容；本 repo 首頁 `index.html` 也以它渲染 `README.md`。

## 各範例框架

### PDRenderKit

| 範例 | 版本 | 備註 |
|---|---|---|
| [基礎版型 220408](/zh/example-20220408) | 1.0.2 | - |
| [餐廳介紹 220525](/zh/example-20220525) | 1.0.0 | 有載入但頁面程式未使用 |
| [個人作品集](/zh/example-20230226) | 1.0.0 | - |
| [服務資訊](/zh/example-20230301) | 1.0.0 | 有載入但頁面程式未使用 |
| [App 介紹 230302](/zh/example-20230302) | 1.0.0 | - |
| [App 介紹 230306](/zh/example-20230306) | 1.5.2 | - |
| [相簿頁面](/zh/example-20230309) | 1.0.0 | - |
| [基礎版型 230310](/zh/example-20230310) | 1.5.2 | - |
| [部落格](/zh/example-20230311) | 1.5.2 | - |
| [基礎版型 230312](/zh/example-20230312) | 1.5.2 | - |
| [產品介紹](/zh/example-20230313) | 1.0.0 | - |
| [商店頁面](/zh/example-20230314) | 1.0.0 | - |
| [記帳本](/zh/example-20230418) | 1.2.0 | - |
| [個人簡介 230512](/zh/example-20230512) | 1.0.0 | - |
| [餐廳介紹 230604](/zh/example-20230604) | 1.0.0 | - |
| [個人頁面](/zh/example-20230607) | 1.0.0 | - |
| [個人資訊](/zh/example-20230610) | 1.0.0 | - |
| [關於我頁面](/zh/example-20230613) | 1.5.2 | - |
| [健身房介紹](/zh/example-20230619) | 1.5.2 | - |
| [含部落格的個人頁](/zh/example-20230621) | 1.2.0 | 另載入 PDMarkdownKit 1.6.0 |
| [App 介紹 230710](/zh/example-20230710) | 1.2.0 | 另載入 PDMarkdownKit 1.6.0 |
| [簡約部落格](/zh/example-20230712) | 1.0.1 | - |
| [雜誌風部落格](/zh/example-20230719) | 1.2.0 | 另載入 PDMarkdownKit 1.6.0 |
| [個人部落格](/zh/example-20230720) | 1.5.1 | - |
| [封面式個人部落格](/zh/example-20230721) | 1.0.1 | - |
| [經典部落格](/zh/example-20230722) | 1.5.1 | - |
| [極簡部落格](/zh/example-20230723) | 1.0.1 | - |
| [社群網站](/zh/example-20230730) | 1.0.1 | - |

### QuickUI

| 範例 | 版本 | 備註 |
|---|---|---|
| [個人介紹](/zh/example-20230220) | 0.6.2 | - |
| [個人簡介 230616](/zh/example-20230616) | 0.6.2 | - |
| [嘖嘖募資平台](/zh/example-20240625) | 0.6.2 | - |
| [語音智能時鐘](/zh/example-20241220) | 0.6.2 | - |

### PDExtension

| 範例 | 版本 | 備註 |
|---|---|---|
| [Instagram 仿製](/zh/example-20221012) | local | - |

### 未使用框架

| 範例 | 版本 | 備註 |
|---|---|---|
| [基礎版型 220409](/zh/example-20220409) | - | - |
| [基礎版型 220412](/zh/example-20220412) | - | - |
| [基礎版型 220413](/zh/example-20220413) | - | - |
| [基礎版型 220418](/zh/example-20220418) | - | - |
| [服務介紹](/zh/example-20230605) | - | - |

## 相關頁面

- [專案結構](/zh/project-structure)
- [樣式工作流程](/zh/styling-workflow)
