# v5 sources (2026-10-30 America/Los_Angeles)

## Brand blue
- **Rock Blue `#25649F`** — YWR Brand Bible `/workspace/brand-bible/YWR-Brand-Bible.html` (`--rock:#25649F`, labeled “Rock Blue” on-site).

## Hero mockup
- Lexi attachment copied to `assets/hero-dad-mom-mockup.png` (Dad + Mom books on sky/yellow background).

## Judge.me reviews
- Same 10 verbatim reviews as `assets/proof/reviews-picked.json` (Carrie Ford first), originally from live Judge.me on the Dad split-test PDP.

## Amazon — attempted live fetch
### Product pages (succeeded — rating counts only)
| Book | ASIN | URL | Avg (as listed) | Count (as listed) |
|---|---|---|---|---|
| You Will Rock As a Dad! | B0BNGRZC4Z | https://www.amazon.com/dp/B0BNGRZC4Z | **4.6 out of 5** | **1,157 global ratings** |
| You Will Rock As a Mom! | B0FRXQ7CTR | https://www.amazon.com/dp/B0FRXQ7CTR | **4.4 out of 5** | **309 global ratings** |

Fetched via Playwright Chromium against the live product pages. Saved HTML under `amazon-fetch/`.

### Individual review quotes (BLOCKED — none added to the mockup)
Attempted:
- `https://www.amazon.com/product-reviews/B0BNGRZC4Z` → **Sign in** wall
- `https://www.amazon.com/gp/aw/reviews/B0BNGRZC4Z` → **Sign in** wall
- `https://www.amazon.com/hz/reviews-render/ajax/lazy/reviews?...` → empty/error
- Product-page medley AJAX `POST /hz/reviews-render/ajax/medley-reviews/get/` → **404**
- 0 `[data-hook="review"]` nodes after scrolling the product page

**No Amazon review bodies, names, or “Amazon Verified Purchase” tags were invented or pasted.** The case-study wall shows only the exact Amazon rating averages/counts above, plus Judge.me quotes. Raw fetch notes: `amazon-fetch/amazon-ratings-only.json`.

## Live kit prices (sticky + buy tiles)
From live PDP offer tiles: Dad Vol. 1 **$21**, Dad + Mom **$28**, Pregnancy & Beyond **$49**, Bump to Potty **$69**.
Source: https://youwillrockbundles.com/products/show-up-for-her-feel-ready-for-fatherhood-in-under-2-hours-paperback-copy
