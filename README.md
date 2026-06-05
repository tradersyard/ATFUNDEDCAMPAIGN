# ATFunded Winback Campaign

Landing page for the TradersYard win-back campaign targeting displaced ATFunded traders. Offers 50% off the first challenge to verified ATFunded customers, gated behind a Google Form (proof of account required).

## Pages
- **`index.html`** — primary page. Dark theme, matches the current tradersyard.com identity. This is the deployable entry page.
- **`index-light.html`** — alternate light theme version.

Both reuse the real TradersYard nav and footer, brand colour `#4250EB`, Satoshi/Clash Display type, and link the claim CTA to the campaign Google Form.

## Assets
- `assets/ty-logo-white.svg` / `assets/ty-logo-blue.svg` — official TradersYard wordmark
- `assets/fonts/clash-display/` — bundled Clash Display weights
- `assets/favicon.ico`

## Deploy
Static site. Serve `index.html` directly, or point a host (Vercel/Netlify/GitHub Pages) at the repo root.
