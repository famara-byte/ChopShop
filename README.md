# ChopShop — Website (Demo)

Demo website for **ChopShop**, The Gambia's fast-food chain — famous for its sweet-bun burgers, grilled chicken and shawarma, trading since 2014.

## What's here

- `index.html` — the complete single-page website in one file (Google Fonts is the only external resource), with all photography as local files under `assets/`:
  - **Hero — "The burger builds itself":** a scroll-driven sequence where a photorealistic burger — seven AI-generated food-photography layers (bottom bun, patty, cheese, onion, tomato, lettuce, sesame top bun), cut out to transparent WebP in `assets/layers/` — first pulls apart layer by layer, then drops back into the stack one layer at a time, and finally crossfades to the burger served in a takeaway box with fries (`assets/photos/burger-box.webp`). Vanilla JS + `requestAnimationFrame` on scroll; no libraries. Without JS — or with reduced-motion settings — the assembled burger and call-to-action simply show as a static hero.
  - **Build Your Own:** an interactive stacker using the same photo layers — toggle extras (extra patty, cheese, lettuce & tomato, grilled onions) and watch the stack, layer count and dalasi total update live.
  - **Menu:** card-grid menu in seven categories (Burgers, Combos & Buckets, Grilled Chicken, Fish & Seafood, Shawarma & Wraps, Sides, Shakes & Juices) with sample dalasi prices; each category carries a food photo from `assets/photos/`.
  - **Find Us:** both branches, opening hours, phone, and the Google rating line.
- `space.json` / `AGENTS.md` — original build metadata and notes.

## Status

Concept demo. Menu items and prices are sample estimates in the ranges the business is known to charge, to be replaced with ChopShop's real menu card before the site is promoted as final. The only order channel shown is the published phone number — ChopShop publishes no WhatsApp number or email, so none is shown.

## The business

- ChopShop — "The Gambia's biggest indigenous food brand" · Est. 2014
- Flagship: Kairaba Avenue, next to the QCell headquarters, Serrekunda
- Second branch: Tropic Shopping Center, Senegambia
- Phone: +220 240 0777 · Open daily 8:30 AM – 11:00 PM · Rated 4.3 stars on Google
