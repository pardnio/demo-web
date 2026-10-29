# Styling Workflow

This page covers recompiling an example's SCSS into the CSS it actually loads.

## Entry Files and Output

Most examples compile `sass/index.scss` to `css/index.css`; the early 2022 examples use different names:

| Examples | SCSS entry | Output CSS |
|----------|------------|------------|
| `20220409`, `20220412`, `20220413`, `20220418` | `sass/PDWebsitemplate.min.scss` | `css/PDWebsitemplate.min.css` |
| `20220525` | `sass/PDWebsiteImitationCss.scss` | `css/PDWebsiteImitationCss.css` |
| The other 33 examples | `sass/index.scss` | `css/index.css` |

Before compiling, check which file the example's `index.html` `<link rel="stylesheet">` points to; the "Styling" section of each example page lists the matching paths.

## Compile One Example

```bash
cd target/20230719
npx sass sass/index.scss css/index.css --no-source-map || { echo "SCSS build failed"; exit 1; }
```

## Watch Mode

```bash
cd target/20230719
npx sass --watch sass/index.scss:css/index.css --no-source-map
```

## Related

- [Project Structure](/project-structure)
- [Frameworks](/frameworks)
