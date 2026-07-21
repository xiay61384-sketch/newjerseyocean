
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


## Flagship V4 module-detail sample
This version adds a working nested-detail sample for the homepage mini modules.

Included sample sections:
- Detailed hero section
- Corporate metrics
- Development timeline
- Mission and values cards
- FCL operating flow
- Key partner-port grid
- Responsive desktop and mobile layouts
- English, Simplified Chinese and Traditional Chinese detail-page copy

Click any small module under About Us, Services, Global Network or Contact to open the sample detail experience.


## Flagship V5 — third-level clickable content
This version adds another content level inside the sample module page.

Clickable items now include:
- Integrity
- Efficiency
- Innovation
- Global Collaboration
- Every step in the FCL operating process
- Every displayed partner port

Each item opens its own third-level detail view with:
- Dedicated title and introduction
- Key indicators
- Core principles
- Practical applications
- Back navigation to the parent module

English, Simplified Chinese and Traditional Chinese content is included for this sample.


## Flagship V6 — complete page hierarchy
This build implements the intended navigation structure:

1. Entry screen
2. Main website homepage
3. Clickable main sections
4. Clickable child modules
5. Third-level detail pages
6. Clickable executive management profiles

Management profiles include:
- Portrait placeholder
- Name and position
- Basic information
- Responsibilities
- Areas of expertise
- Leadership philosophy

Upload approved executive portraits later and replace the placeholders.


## Flagship V7 — all modules are clickable

The navigation hierarchy now works consistently across the full prototype:

1. Entry screen → Enter Official Website
2. Homepage → click a main section
3. Main-section page → every displayed child card is clickable
4. Child-module internal page → contains further clickable detail modules
5. Third-level detail page → complete detailed content
6. Management Team → every executive card opens an individual profile

Clickable child modules include all items under:
- About Us
- Services & Solutions
- Global Network
- News
- Contact shortcuts
- Management Team

The homepage mini-module links and the child cards displayed inside each main section use the same internal-page navigation system.
