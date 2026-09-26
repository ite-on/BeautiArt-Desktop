# BeautiArt Desktop Website

This repository serves the public BeautiArt Desktop website through GitHub Pages:

- Home: <https://ite-on.github.io/BeautiArt-Desktop/>
- Download: <https://ite-on.github.io/BeautiArt-Desktop/download.html>
- Privacy: <https://ite-on.github.io/BeautiArt-Desktop/privacy-policy.html>
- Support: <https://ite-on.github.io/BeautiArt-Desktop/support.html>

BeautiArt Desktop is a Windows application for arranging Explorer desktop icons into letters, words, geometric designs, and decorative shapes. The site is intentionally static and has no build step, analytics, account system, or application download hosted outside Microsoft Store.

## Site Files

| File | Purpose |
| --- | --- |
| `index.html` | Product landing page and screenshot gallery |
| `download.html` | Microsoft Store download and system-requirement page |
| `privacy-policy.html` | Public privacy policy |
| `support.html` | Support and recovery guidance |
| `store-pages.css` | Shared responsive visual system |
| `sample-s.png`, `sample-he.png` | Authentic desktop-layout examples |

## Microsoft Store Link

The download page currently uses this deliberate placeholder:

```text
https://apps.microsoft.com/detail/STORE_PRODUCT_ID
```

After Partner Center assigns the public Store product ID, replace `STORE_PRODUCT_ID` in `download.html`. Do not replace it with a package identity name or Partner Center-only identifier.

## Publish With GitHub Pages

1. Update the Store link when available.
2. Open `index.html`, `download.html`, `privacy-policy.html`, and `support.html` locally.
3. Confirm links, screenshots, responsive layout, support email, and policy dates.
4. Commit and push to the branch configured under **Settings > Pages**.
5. Wait for the Pages deployment, then verify all four public URLs above.

```powershell
git add README.md index.html download.html store-pages.css sample-s.png sample-he.png
git commit -m "Add Store download page and product gallery"
git push
```

## Content Rules

- Distribution must point to Microsoft Store only.
- Keep privacy and support claims aligned with the released application.
- Use real application screenshots and avoid showing private user data.
- Update this README whenever public pages, URLs, or deployment requirements change.

Copyright 2026. Published by LA FRET. All rights reserved.
