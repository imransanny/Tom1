# TOMATO Clothing — polished storefront preview

A responsive Vite-based storefront derived from the provided TOMATO design. The **Shop by Category** and **Trending Products** sections retain solid black backgrounds and tomato-red product cards.

## Run locally

```bash
npm install
npm run dev
```

## Production compile

```bash
npm run build
npm run preview
```

Requires Node.js 20.19+ or 22.12+ for newer Vite releases. If you deploy to Vercel or Netlify, use `npm run build` and output directory `dist`. SPA rewrites are provided.

## Important

This remains a **frontend/storefront preview** until a secure commerce backend, live payment processing, verified catalog/inventory, business details, policies, and operational integrations have been configured. No customer payment data should be entered. The currency, ratings, shipping promises and product info are demo placeholders. Public search indexing is intentionally disabled in `public/robots.txt` until a verified launch. Please see `LAUNCH_CHECKLIST.md`.

## Verification

The JS syntax check and archive integrity were verified. A full npm installation/build and cross-browser manual review could not be completed in the execution environment; run the build above before deploying.
