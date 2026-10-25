# WebAura Studio — Creative redesign

A responsive static agency website for Muhammad Ahmad Raza, with custom introductory artwork, illustrated services, scroll transitions, hover effects, and an interactive Brand Playground.

## Brand Playground
Choose a business name, type, goal, and one of three visual styles. The live preview changes typography, palette, headline, and suggested services. Export a PNG direction card, or transfer the concept to the enquiry form. Recommendations are rule based, not trained AI predictions.

## Run and publish
Open index.html in a browser, or serve this directory with a static server. No build step, package install, or database is required. GitHub Pages can publish the main branch at the repository root after this redesign is reviewed and merged.

## Files
- index.html: accessible content, contact details, and location map
- style.css: responsive design, transitions, hover states, reduced-motion support
- app.js: Brand Playground, canvas export, menu, motion pause, email preparation
- assets/logo.png: supplied studio logo
- assets/intro-cover.webp: AI-generated campaign illustration, optimized for web

## Behavior and privacy
The enquiry form opens an email app for the visitor to review and send. It does not store or send submissions directly. Playground inputs remain on the page. Fonts and the embedded Google Map load from external services. WhatsApp, telephone, and email links use the supplied business details.

## Validation
JavaScript syntax and HTML anchors/assets checked. All 36 business/style/goal combinations exercised. Live browser checks verified image loading, desktop layout, style updates, and PNG download. Mobile layouts are implemented with responsive breakpoints; no mobile device browser test was available.

The redesign is proposed on a separate branch; merging it replaces the live homepage while retaining Git history.
