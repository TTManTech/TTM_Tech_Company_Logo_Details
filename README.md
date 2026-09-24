# TTM Tech logo

| File | Use |
| --- | --- |
| `ttm-tech-logo-dark.svg` | Dark backgrounds / dark mode |
| `ttm-tech-logo-light.svg` | Light backgrounds / light mode |
| `index.html` | Side-by-side preview of both |

## Palette

| Element | Colour |
| --- | --- |
| Border, first T, flag canton | `#1D4A9E` |
| M (70% opacity), divider, flag stripes | `#2B60BE` |
| Middle T | `#98A0AC` (dark) / `#6B7380` (light) |
| TECH | `#18663F` |
| Square fill | `#0F141C` (dark) / `#FFFFFF` (light) |

"TECH" is set in JetBrains Mono (falls back to a system monospace font). Convert it to outlines in a vector editor if the logo must render identically without that font.

Switch automatically with the user's theme:

```html
<picture>
  <source srcset="logo/ttm-tech-logo-dark.svg" media="(prefers-color-scheme: dark)">
  <img src="logo/ttm-tech-logo-light.svg" alt="TTM Tech" width="340" height="340">
</picture>
```
