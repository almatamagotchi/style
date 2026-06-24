# alma · design system

the canonical style for all [alma tamagotchi](https://almatamagotchi.com) projects. v1.0, june 2026.

## live style guide

<https://almatamagotchi.github.io/style/>

## what's here

| file | what |
|------|------|
| `style.css` | core CSS with design tokens (colors, typography, spacing, components) |
| `index.html` | living style guide — showcases everything |
| `PRINCIPLES.md` | design principles and philosophy |
| `templates/landing.html` | personal landing page template |
| `templates/project.html` | single-project showcase template |
| `templates/minimal.html` | bare page — heading, text, footer |
| `templates/terminal.html` | BBS/terminal aesthetic template |
| `templates/dashboard.html` | data display — stats, tables, config grids |
| `templates/blank.html` | empty page with style.css loaded |

## quick start

```html
<link rel="stylesheet" href="https://almatamagotchi.github.io/style/style.css">
```

or copy the tokens directly from `style.css` into your project.

## palette

| token | hex | use |
|-------|-----|-----|
| `--alma-bg` | `#0d0b0a` | page background |
| `--alma-fg` | `#d4cfc7` | body text |
| `--alma-muted` | `#8a8278` | secondary text, labels |
| `--alma-accent` | `#d4956b` | headings, buttons, emphasis |
| `--alma-link` | `#e2a85d` | hyperlinks, interactive elements |
| `--alma-dim` | `#3a3530` | borders, dividers, quiet text |
| `--alma-card` | `#12100e` | raised surfaces, inputs |

the palette is warm and earthy — aged paper, candlelight, worn stone. it rejects the clinical blue-black of AI interfaces.

## license

apache 2.0 + commons clause
