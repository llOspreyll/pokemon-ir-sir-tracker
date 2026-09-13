# Pokémon TCG IR & SIR Master Catalog

A single-page collector catalog for English Pokémon TCG Illustration Rare (IR) and Special Illustration Rare (SIR) cards.

## Open locally
Open `index.html` in a browser. Desktop browsers usually allow the live API request. iPhone/iPad may block live requests when the page is opened with the `file://` protocol.

## Host it
This folder is ready for static hosting. Upload the contents as-is to GitHub Pages, Netlify, Cloudflare Pages, or Vercel. No build command is required; `index.html` is the site entry point.

## Features
- IR and SIR grouped by set
- card art, names, numbers, rarity
- search and filters
- owned checklist stored in localStorage
- overall and per-set completion percentage
- collapsible set sections
- export/import collection backup as JSON
- mobile responsive layout

## Data
Card metadata and artwork load at runtime from the Pokémon TCG API. The site filters the official `Illustration Rare` and `Special Illustration Rare` rarity values and excludes cards from sets released after the catalog cutoff date embedded in `index.html`.
