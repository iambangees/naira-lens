# Naira Lens

**What a dollar is really worth in Lagos.**

A one-page lens on the naira:

- **Live official USD→NGN rate** (plus GBP, EUR, AED, CAD, CNY), from the ExchangeRate-API open feed with a second public feed as fallback and cross-check.
- **A 90-day chart** built from dated daily snapshots of a public currency API, with the period change spelled out (including the reminder that a rising ₦ number means a weaker naira).
- **"What that buys in Lagos"** — the converted amount translated into rough Lagos ballparks (minimum-wage months, bags of rice, litres of petrol, danfo rides…), clearly labelled as November 2026 ballparks, not a price list.
- **Two-way conversion** (foreign → ₦ and ₦ → foreign), quick-amount chips, and a copy-the-result button.

## Honesty rules baked in

- The rate shown is the **official mid-market rate**. The parallel/street rate is usually different and is **not** quoted — no reliable public feed publishes it, and inventing one would make the tool a liar.
- Lagos prices are labelled ballparks with their month, because Nigerian prices move fast.

## How it works

One static page (`site/index.html`); all fetching and maths happen in the visitor's browser against free, keyless public APIs. No backend, no tracking, no accounts.

## Live

Published with GitHub Pages from this repo's `gh-pages` branch (the `site/` folder).
