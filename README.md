
# NJOS Group 3D Website Prototype

## Files
- index.html
- styles.css
- app.js

## Run locally
The entry button now works when opening `index.html` directly. For the 3D globe, an internet connection is required. A local web server is still recommended:

```bash
python3 -m http.server 8080
```

Then open:
http://localhost:8080

## Deploy
Upload the whole folder to GitHub Pages, Netlify, Vercel, Cloudflare Pages, or any static web host.

## Included
- Entry splash screen and “Enter Official Website” flow
- Black-gold premium visual system
- Browser-based “naked-eye” 3D globe with cursor parallax
- Animated glowing routes from Newark to Asia, Middle East, Europe and the Americas
- Clickable main sections and nested detail modules
- Management team and contact details
- Multilingual architecture with language selector
- Responsive desktop/tablet/mobile layout

## Important
The current build is a front-end prototype. The quotation form, tracking, schedule search,
CMS, real shipping data, and full professional translations require backend/API integration.


## Fixed in this version
- The Enter Official Website button works when `index.html` is opened directly with `file://`.
- The 3D engine is loaded only after entering the website.
- If the 3D library cannot load, the rest of the website remains usable and a visible fallback is shown.


## Flagship V2 upgrade
- Real Earth surface texture with recognizable continents and oceans
- Independent rotating cloud layer
- Atmospheric rim lighting and premium black-gold night glow
- Dense 3D star field
- Newark beacon as the global route origin
- Animated light particles along routes to Asia, the Middle East, Europe and the Americas
- Mouse parallax, drag-to-rotate, and wheel zoom
- Local Earth texture assets included in the package

The Three.js engine is still loaded from jsDelivr, so keep an internet connection active
or later bundle Three.js locally during production deployment.


## Flagship V3 — completed multilingual switching
The following languages now switch the full interface and internal page content without Google Translate:
English, 简体中文, 繁體中文, 日本語, 한국어, ภาษาไทย, ភាសាខ្មែរ, Español, Français, Deutsch and Português.

The language switch updates the landing screen, homepage, navigation, service cards,
internal pages, management biographies, contact form and detail dialogs.
