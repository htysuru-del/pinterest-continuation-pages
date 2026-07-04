# Long Road Trip Essentials

This folder is the GitHub Pages publishing source.

## Files

```text
docs/
├── index.html
├── .nojekyll
└── assets/
```

## Before Publishing

The current `index.html` is an MVP page.

Hero image status:

- The page is still waiting for the actual Pinterest posted image.
- Do not use `Assets/Generated Images` or `Assets/Approved Images` as the Hero image.
- After the Pinterest image is posted, copy the actual posted image into `docs/assets/hero.png`.
- Then replace the Hero placeholder in `docs/index.html` with:

```html
<img src="assets/hero.png" alt="Long Road Trip Essentials Pinterest checklist">
```

## Publishing Source

Use this folder as the GitHub Pages source:

- Branch: `main`
- Folder: `/docs`
Deployment retry: 2026-07-05
