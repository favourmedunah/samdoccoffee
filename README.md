# Samdoc Coffee & More

Website for **Samdoc Coffee & More**, a café on 1T4 Road, Ekpoma, Edo State, Nigeria.
*"Life Happens, Coffee Helps."*

🌐 **Live site:** https://samdoc.coffee

## What the site does

- Full menu by category (beverages, protein, pastries, breakfast, appetizers, pasta, noodles, small chops)
- Shopping cart with quantity controls and a live total
- Orders are sent to the café as one WhatsApp message
- Opening hours, address, Google Maps embed and Google review link
- Mobile-first, fast, no frameworks and no build step

## Built with

HTML5, CSS3 and vanilla JavaScript in a single `index.html`, plus Google Fonts.

## Running locally

No setup needed. Open `index.html` in a browser.

## Updating content

Everything editable is in the config block at the top of the `<script>` in `index.html`
(phone, WhatsApp number, address, social links, menu items and prices, and the `SHOW_PROMO` flag
that turns the promo banner on or off). Hours are in the `HOURS` list in the same script.

## Deployment

Hosted on Netlify from the `main` branch. Pushing to `main` deploys the site.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole website |
| `favicon.ico`, `favicon-48.png`, `favicon-96.png`, `favicon-192.png`, `apple-touch-icon.png` | Site icons (also used by Google Search results) |
| `robots.txt`, `sitemap.xml` | Search engine crawling info |

## Credits

Website by [DevByFavour](mailto:devbyfavour@gmail.com).
© Samdoc Coffee & More. All rights reserved.
