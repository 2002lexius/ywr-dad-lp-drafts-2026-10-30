# v8 sources (2026-10-30 America/Los_Angeles)

Built from v7. Draft preview only — never touches live Shopify.

## Lexi feedback (buy-block gallery)
1. Keep ONLY 3 slides, in this order:
   1. `assets/hero-dad-mom-mockup.png` — Dad+Mom mockup (badge overlay)
   2. `assets/og/dad-energy-shared-05-reader-proof.webp` — Dads put it into practice
   3. `assets/og/dad-energy-shared-04-ready-for-birth.webp` — From we're pregnant to it's time
2. Removed all other slides/thumbnails.
3. Removed kit-tile prepend behavior — gallery is always exactly 3 slides. Counter reads `1 / 3`.
4. `#1 Best Seller on Amazon` circular badge shows ONLY on slide 1 (fixed CSS `display:none !important` that was being overridden by `.bestseller-badge{display:block !important}`). Positioned in top-left sky area, clear of book text. No hover enlarge/move.
5. Left/right arrows moved OUT of the image into a `.mars-bar` below the stage (prev · 1/3 · next), above the thumbnails — never overlay slide content on mobile or desktop.
6. Hero hook "TERRIFIED YOU'RE NOT READY?" and other blue TEXT on dark backgrounds (e.g. buy headline `.hi` "fatherhood") use lighter Rock Blue tint `#5B9BE0` for contrast. Buttons / checkmarks stay Rock Blue `#25649F`.

## Palette
Rock Blue `#25649F` (buttons/checks), text-on-dark `#5B9BE0`, white, navy.
