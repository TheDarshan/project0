# devbydarshan — Portfolio Website

A two-page personal portfolio site built with plain HTML and CSS (no frameworks, no JS libraries).

**Live:** [devbydarshan.vercel.app](https://devbydarshan.vercel.app)

## Pages

| File | Purpose |
|---|---|
| `welcome.html` | Landing/hero page — name, short bio, tags, CTA into the main portfolio |
| `index.html` | Main portfolio page — about section, selected works (filterable), contact/footer |
| `style.css` | Shared stylesheet for both pages |

## Tech

- HTML5
- CSS3 (custom properties, flexbox, media queries)
- No JavaScript — the project filter tabs on the "Selected Works" section use a CSS-only radio button + sibling selector trick, not JS

## Structure

```
.
├── welcome.html
├── index.html
└── style.css
```

## Features

- Dark, editorial-style theme using CSS custom properties (`:root` variables) for colors, spacing, and fonts
- Fully responsive layout, mobile-first from 375px up
- Sticky site header with nav links
- About section with a portrait placeholder and bio
- Filterable project grid (All / Web / Tools) — CSS-only, no JavaScript
- Contact section with primary/secondary buttons in the footer


Darshan — [devbydarshan.vercel.app](https://devbydarshan.vercel.app)
