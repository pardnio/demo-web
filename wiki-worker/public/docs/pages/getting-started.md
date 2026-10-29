# Getting Started

This page covers getting the source and previewing the landing page and any example locally.

## Prerequisites

| Item | Description |
|------|-------------|
| Browser | Any modern browser with ES Module support (Chrome, Safari, Firefox, Edge) |
| HTTP static server | The landing page reads `README.md` via `fetch('./README.md')`, which fails under `file://`; example pages open directly from disk |
| Network | Every example loads Font Awesome (and, in 32 of them, PDRenderKit or QuickUI) from `cdn.jsdelivr.net`; the landing page and 5 examples also load fonts from `fonts.googleapis.com` |
| Dart Sass (optional) | Needed only to change styles, run through Node.js `npx sass` |

## Get the Source

```bash
git clone https://github.com/pardnchiu/demo-web.git
cd demo-web
```

## Local Preview

```bash
python3 -m http.server 8080 || { echo "port 8080 is in use"; exit 1; }
```

| URL | Content |
|-----|---------|
| `http://localhost:8080/` | Landing page: `README.md` (project overview) rendered by PDMarkdownKit |
| `http://localhost:8080/target/20241220/` | A single example (folder name is the creation date) |

## Online

- GitHub Pages: <https://pardnio.github.io/demo-web/>
- This documentation site serves a copy of the repo's `target/` directory at `https://demo-web.pardn.io/target/<YYYYMMDD>/`, the canonical URL each example declares in its `<head>`; every example page here shows a screenshot and links to the running example.

## Next Steps

- [Project Structure](/project-structure): folder naming and what each example contains
- [Styling Workflow](/styling-workflow): how to recompile SCSS
