# 樣式工作流程

本頁說明如何把範例的 SCSS 重新編譯成它實際載入的 CSS。

## 入口檔與輸出

多數範例的入口為 `sass/index.scss`、輸出為 `css/index.css`；2022 年的早期範例使用不同檔名：

| 範例 | SCSS 入口 | 輸出 CSS |
|------|-----------|----------|
| `20220409`、`20220412`、`20220413`、`20220418` | `sass/PDWebsitemplate.min.scss` | `css/PDWebsitemplate.min.css` |
| `20220525` | `sass/PDWebsiteImitationCss.scss` | `css/PDWebsiteImitationCss.css` |
| 其餘 33 個範例 | `sass/index.scss` | `css/index.css` |

編譯前先確認該範例 `index.html` 的 `<link rel="stylesheet">` 指向哪個檔案；每個範例頁的「樣式」段落也列出了對應路徑。

## 編譯單一範例

```bash
cd target/20230719
npx sass sass/index.scss css/index.css --no-source-map || { echo "SCSS 編譯失敗"; exit 1; }
```

## 監看模式

```bash
cd target/20230719
npx sass --watch sass/index.scss:css/index.css --no-source-map
```

## 相關頁面

- [專案結構](/zh/project-structure)
- [框架使用](/zh/frameworks)
