# Frameworks

This page lists the frontend framework and version each example loads, tracing the evolution from PDExtension through PDRenderKit to QuickUI.

## Evolution Overview

| Framework | Examples | Loaded via |
|-----------|----------|------------|
| PDExtension | 1 | Local `js/PDExtension.js`, extending native prototypes (`String`, `HTMLElement`, ...) |
| PDRenderKit | 28 | `cdn.jsdelivr.net/npm/pdrenderkit@<version>/dist/PDRenderKit.js`, versions 1.0.0 to 1.5.2 |
| QuickUI | 4 | `cdn.jsdelivr.net/npm/@pardnchiu/quickui@0.6.2/dist/QuickUI.js` |
| No framework | 5 | Plain HTML + CSS |

PDMarkdownKit 1.6.0 pairs with PDRenderKit as an ES Module to render Markdown; the repo's own landing page `index.html` uses it to render `README.md`.

## Framework per Example

### PDRenderKit

| Example | Version | Note |
|---|---|---|
| [Basic (2022-04-08)](/example-20220408) | 1.0.2 | - |
| [Restaurant Introduction (2022-05-25)](/example-20220525) | 1.0.0 | loaded but not used by page code |
| [Personal Portfolio](/example-20230226) | 1.0.0 | - |
| [Service Info](/example-20230301) | 1.0.0 | loaded but not used by page code |
| [App Introduction (2023-03-02)](/example-20230302) | 1.0.0 | - |
| [App Introduction (2023-03-06)](/example-20230306) | 1.5.2 | - |
| [Gallery Page](/example-20230309) | 1.0.0 | - |
| [Basic (2023-03-10)](/example-20230310) | 1.5.2 | - |
| [Blog](/example-20230311) | 1.5.2 | - |
| [Basic (2023-03-12)](/example-20230312) | 1.5.2 | - |
| [Product Introduction](/example-20230313) | 1.0.0 | - |
| [Store Page](/example-20230314) | 1.0.0 | - |
| [Moneybook](/example-20230418) | 1.2.0 | - |
| [Personal Profile (2023-05-12)](/example-20230512) | 1.0.0 | - |
| [Restaurant Introduction (2023-06-04)](/example-20230604) | 1.0.0 | - |
| [Personal Page](/example-20230607) | 1.0.0 | - |
| [Personal Info](/example-20230610) | 1.0.0 | - |
| [About Me Page](/example-20230613) | 1.5.2 | - |
| [Gym Introducing](/example-20230619) | 1.5.2 | - |
| [Personal Page With Blog](/example-20230621) | 1.2.0 | also loads PDMarkdownKit 1.6.0 |
| [App Introduction (2023-07-10)](/example-20230710) | 1.2.0 | also loads PDMarkdownKit 1.6.0 |
| [Simplify Blog](/example-20230712) | 1.0.1 | - |
| [Magazine Blog](/example-20230719) | 1.2.0 | also loads PDMarkdownKit 1.6.0 |
| [Personal Blog](/example-20230720) | 1.5.1 | - |
| [Personal Blog with Cover](/example-20230721) | 1.0.1 | - |
| [Classic Blog](/example-20230722) | 1.5.1 | - |
| [Minimal Blog](/example-20230723) | 1.0.1 | - |
| [Social Networking](/example-20230730) | 1.0.1 | - |

### QuickUI

| Example | Version | Note |
|---|---|---|
| [Personal Introduction](/example-20230220) | 0.6.2 | - |
| [Personal Profile (2023-06-16)](/example-20230616) | 0.6.2 | - |
| [Zeczec](/example-20240625) | 0.6.2 | - |
| [Smart Clock (Voice Control)](/example-20241220) | 0.6.2 | - |

### PDExtension

| Example | Version | Note |
|---|---|---|
| [Instagram](/example-20221012) | local | - |

### No Framework

| Example | Version | Note |
|---|---|---|
| [Basic (2022-04-09)](/example-20220409) | - | - |
| [Basic (2022-04-12)](/example-20220412) | - | - |
| [Basic (2022-04-13)](/example-20220413) | - | - |
| [Basic (2022-04-18)](/example-20220418) | - | - |
| [Service Introduction](/example-20230605) | - | - |

## Related

- [Project Structure](/project-structure)
- [Styling Workflow](/styling-workflow)
