# Gee Travel Agency — Concept Website

Editorial, mobile-first website prototype made with React, Vite and plain CSS (JSX; no TSX, Tailwind, icon library or UI kit).

## Run locally

```bash
npm install
npm run dev
```

Build with `npm run build`; production output is in `dist/`.

## Deploy to GitHub Pages

The `main` branch is built and deployed to GitHub Pages by the workflow in
`.github/workflows/deploy.yml`. In the repository settings, set **Pages >
Build and deployment > Source** to **GitHub Actions**. After the workflow
completes, the site is available at
https://codevenientlab.github.io/Gee-Travels/.

## Current functionality

- Responsive desktop/mobile navigation, scroll-to-section links
- Travel inspiration content with sample destination imagery, not actual commercial offers
- Enquiry modal, required-field validation, travellers input limits, prepared WhatsApp enquiry
- Click-to-call, Google Maps, privacy and terms draft dialogs
- SEO page title, description, OpenGraph tags, SVG favicon, image lazy-loading, accessible labels, reduced-motion preference

## Before presenting as an official client website

1. **Obtain owner approval** for business name, logo/brand, phone (+27 78 721 4877 from public listing), services, operating hours, address and images.
2. Replace inspiration copy with verified offerings, destinations, images, package details and real service policies; don't represent sample destinations as bookable.
3. Get legal approval for the **draft** Privacy and Terms content. Add POPIA-compliant operator identification, retention, security, data subject rights, cookie and third-party image disclosures as applicable.
4. Supply real licensed/owned travel photography and branded logo. Current demo uses images from Unsplash CDN.
5. Replace copy calling the website a concept, remove developer attribution if requested, obtain public-launch approval.
6. Test WhatsApp enquiry across browser pop-up blockers, mobile and desktop. This demo does not store booking or payment data.
7. Configure domain, canonical URL, OG preview image, analytics (consent where needed), and sitemap once the live domain is known.
8. For GitHub Pages repository subpath hosting, set Vite `base` and use relative favicon path; custom-domain/root deployments work without modification.

Business source: https://maps.app.goo.gl/9ASD6kPaA4igmnyh7

Design direction: deep botanical green, sand, photographic editorial storytelling; no fake reviews, pricing, glowing gradients, glassmorphism, icons or generic SaaS cards.
