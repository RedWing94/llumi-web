# Llumi Store — Technical Optimization Progress

## Completed
- [x] Product page collapsible accordions (Ingredients / How to Use / Warnings)
- [x] FDA disclaimer (always visible)
- [x] "Choose your flavor" cross-link picker (Hydrate products)
- [x] About Us page template (hero + story + mission)

## In Progress
- [x] **Task A: Quiz Funnel** — Custom "Find your ritual" quiz page. 3 questions, personalized product recommendation, no app. Live at /pages/find-your-ritual.
- [x] **Task B: Structured Data (JSON-LD)** — Enhanced Product schema (brand, audience, ingredients, directions, warnings from metafields), BreadcrumbList, shipping/returns policy, AI-readable meta content. Supplements Shopify's native schema.
- [x] ~~**Task C: FAQ Schema**~~ — Skipped. Google deprecated FAQ rich results May 2026.
- [x] **Task D: LLM-Optimized Content** — Audited: meta tags complete, semantic HTML clean, alt text dynamic, structured data comprehensive. Biggest remaining win is blog content targeting AI search queries.
- [x] **Task E: Page Speed Audit** — Audited: JS deferred, images lazy-loaded, fonts preloaded, only 1 app. Theme is well-optimized out of the box. Keep app count low.
- [x] **Task F: Blog Template** — Enhanced article template with featured image, branded CTA section (links to quiz + shop), and related products grid below every post. All editable in the theme editor.

## In Progress
- [ ] **Task G: Analytics Setup** — Switched to native Shopify app approach. Removed manual GTM code from theme.liquid and deleted lumi-datalayer.liquid snippet. Next: install Google & YouTube app (handles GA4 + Google Ads automatically), install Facebook & Instagram app (handles Meta Pixel + Conversions API). GTM container (GTM-TJ5GDDST) kept alive but unused for now. Also need to delete the Custom Pixel in Shopify admin.

## Backlog (Requires Apps / Owner Action)
- [ ] Subscription app setup (free tier — Seal Subscriptions or Propel per Supliful)
- [ ] Klaviyo email/SMS flows (owners investigating)
- [ ] Post-purchase cross-sell (custom thank-you section or AfterSell free tier)
- [ ] Judge.me photo/video reviews + review request automation
- [ ] Mobile sticky "Add to Cart" button
- [ ] Google PageSpeed Insights audit + fix top issues

## Notes
- All technical work targets the "Llumi - WIP" theme (live, ID #154080968858)
- Fulfillment via Supliful — no Shopify variants, each flavor is a separate product
- Free tools only for now; paid apps after initial sales traction
- SEO strategy includes LLM/AI assistant readability (Perplexity, ChatGPT, Google AI Overviews)
