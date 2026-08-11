# Shopziexpress — design prototype

**Open it here: https://dkwafo.github.io/Shopzi-prototype/**

That link always points at the current version. Nothing else in this repo needs opening.

## What's in here

| Folder | What it is |
|---|---|
| `prototype/` | **The current prototype.** Four linked pages plus the hero image |
| `archive/` | Superseded versions, kept only for reference |
| `index.html` | A redirect at the root, so the short link above keeps working |

## The current prototype

| Page | File | What it shows |
|---|---|---|
| Landing | `prototype/index.html` | Hero, the two doors, categories, flash sale, impact band |
| Shop | `prototype/shop.html` | Product listing with filters, sorting and an empty state |
| Services | `prototype/services.html` | Service listing with location, availability and packages |
| Product | `prototype/product.html` | Product detail: gallery, buy box, reviews, delivery terms |

Everything is linked. The top bar, the burger menu and the logo work from every page; product cards on the landing page and in the shop grid open the product page.

## Before you review

**All content is placeholder.** Prices, seller names, ratings, availability and product counts are invented so the pages feel real. The only genuine photograph is the hero image (Esha Verma, via Unsplash). Everything else is a coloured placeholder standing in for seller photography.

**This is a design prototype, not the website.** It exists to settle the visual language and layout. The product will be built in React and TypeScript — engineering will receive design tokens and component specifications, not this HTML.

**Give feedback on:** layout, hierarchy, colour, wording, what is missing from a page, and anything that reads as a promise we cannot keep.

**Ignore:** the specific products, prices, names and photographs.

## Two things worth knowing

**The delivery and returns wording on the product page comes from the PRD**, not from the current live site. Returns are the seller's own window of 7 to 30 days, the buyer pays return postage unless the item was wrong, postage is calculated at checkout, and money is released 14 days after tracking shows delivery. The live site currently promises free shipping and 90-day returns, which the PRD says will not exist. If the PRD is out of date, now is the time to say so.

**Every colour was measured against WCAG 2.1 AA before use.** The European Accessibility Act has applied to EU e-commerce since June 2025. Try the pages with the keyboard: Tab reaches a skip link first, the burger menu traps focus and closes on Escape, and every control has a visible focus ring.

## Archive

- `archive/v2.html` — warm artisan design version
- `archive/v3.html` — SHOPZI v3, retail marketplace layout
- Lovable prototype: https://ebb-and-glow-ai.lovable.app
