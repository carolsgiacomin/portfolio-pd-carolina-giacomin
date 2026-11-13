# Carolina Giacomin — Product Design Portfolio

An editorial, responsive portfolio built with Astro 5, semantic HTML, modern CSS, and small vanilla JavaScript interactions.

## Run locally

```sh
npm install
npm run dev
```

Create a production build with `npm run build` and preview it with `npm run preview`.

## Pages

- `/` — portfolio home and selected work
- `/work/fintech-products/` — password-gated confidential fintech products case study
- `/work/docket-atlas/` — case study with a before/after comparison slider
- `/work/guido/` and `/work/ai-art-archive/` — additional case studies
- `/resume/` — print-ready resume; use your browser’s print dialog and choose “Save as PDF”

The fintech products demo password (`FINTECH2026`) is checked in client-side JavaScript. This is a presentation gate only: the password and page content are included in the static site and it must not be used to protect confidential information. Use server-side authentication or a protected hosting service for real access control.

Before publishing, replace the sample email and LinkedIn URLs with your preferred contact details and confirm resume/project details. The Google Fonts are loaded from Google Fonts; system fallbacks are provided.
