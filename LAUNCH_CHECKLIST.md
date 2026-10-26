# TOMATO CLOTHING — REQUIRED BEFORE PUBLIC SALES

## Current status
This package is a **storefront preview**, not a live commerce platform. Product pricing, ratings, reviews, inventory, imagery and claims are sample content. Cart and wishlist are saved only in the browser. No payments or orders are collected.

## Blocking tasks
- [ ] Confirm company legal name, country of operation, address, business registration and support channels.
- [ ] Set the actual store currency and country-specific taxes. All $ prices are currently demo figures.
- [ ] Replace product catalog with approved SKUs, correct images, sizes, colours, descriptions, stock and prices.
- [ ] Set up a hosted commerce platform (e.g. Shopify) or a secure server-side commerce backend with inventory and orders.
- [ ] Connect an approved payment provider using provider-hosted checkout, never frontend secret API keys.
- [ ] Validate shipping zones, carrier rates, free-shipping thresholds and delivery SLAs.
- [ ] Publish reviewed Terms, Privacy, Returns, Shipping and consumer-law-compliant refund rules.
- [ ] Connect real email/contact and newsletter infrastructure with consent, unsubscribe and anti-spam protection.
- [ ] Verify official social accounts and customer service contact information.
- [ ] Test checkout end-to-end in sandbox and then with a controlled live transaction and refund.
- [ ] Configure HTTPS, production domain, access controls, backups and monitoring.
- [ ] Replace screenshot-derived sample imagery with licensed original high-resolution assets.
- [ ] Run device testing, accessibility audit, SEO checks and real-browser performance tests.
- [ ] Change public/robots.txt to permit indexing only when approved for launch.

## Build and preview
`npm install && npm run build` then `npm run preview`.

## Deploy preview
Vercel or Netlify can serve this SPA for staging, but publishing it **does not** implement checkout or backend systems.
