# Shopziexpress — design prototype

**Open it here: https://dkwafo.github.io/Shopzi-prototype/**

That link always points at the current version. Nothing else in this repo needs opening.

## What's in here

| Folder | What it is |
|---|---|
| `prototype/` | **The current prototype.** Five linked pages plus `assets/` (the hero video and its poster frame) |
| `archive/` | Superseded versions. [Browse them here](https://dkwafo.github.io/Shopzi-prototype/archive/) |
| `index.html` | A redirect at the root, so the short link above keeps working |

## The current prototype

| Page | File | What it shows |
|---|---|---|
| Landing | `prototype/index.html` | Full-screen video hero, three seasonal campaigns, flash sale, categories, services, the seller pitch, impact band |
| Shop | `prototype/shop.html` | Product listing with filters, sorting and an empty state |
| Services | `prototype/services.html` | Service listing with location, availability and packages |
| Product | `prototype/product.html` | Product detail: gallery, buy box, reviews, delivery terms |
| Start selling | `prototype/sell.html` | The seller side: fees, payouts, approval, what you need to apply |

Everything is linked. The top bar, the burger menu and the logo work from every page; product cards on the landing page and in the shop grid open the product page.

Two switches sit at the bottom-left of the landing page, for the prototype only: **Viewing as** flips between the signed-out and signed-in header, and **Campaigns** between one seasonal banner and three.

## Before you review

**All content is placeholder.** Prices, seller names, ratings, availability and product counts are invented so the pages feel real. Product images are coloured placeholders standing in for seller photography.

**The hero video is a placeholder too.** It is a licensed clip from Pexels showing someone browsing a shopping app — free for commercial use, but it is not our footage and it does not show fabric, food or a tailor. It is there to settle the layout, not the story.

**This is a design prototype, not the website.** It exists to settle the visual language and layout. The product will be built in React and TypeScript — engineering will receive design tokens and component specifications, not this HTML.

**Give feedback on:** layout, hierarchy, colour, wording, what is missing from a page, and anything that reads as a promise we cannot keep.

**Ignore:** the specific products, prices, names and photographs.

## Three things worth knowing

**The delivery and returns wording on the product page comes from the PRD**, not from the current live site. Returns are the seller's own window of 7 to 30 days, the buyer pays return postage unless the item was wrong, postage is calculated at checkout, and money is released 14 days after tracking shows delivery. The live site currently promises free shipping and 90-day returns, which the PRD says will not exist. If the PRD is out of date, now is the time to say so.

**The landing page leads with a flash sale and seasonal campaigns.** The PRD contains no discount mechanism at all — no sales, no coupons, no campaigns. That is a deliberate override, and it needs confirming before launch: can a seller set a discount, and who controls a campaign?

**Every colour was measured against WCAG 2.1 AA before use**, and the European Accessibility Act has applied to EU e-commerce since June 2025. The pages pass, with one known exception recorded in the design notes: the copy over the hero video falls below the contrast floor where the letters land on the bright parts of the clip. That is a deliberate, documented decision and it should be raised at the accessibility review.

Try the pages with the keyboard: Tab reaches a skip link first, the burger menu closes on Escape and returns focus, every control has a visible focus ring, and the hero video has a real pause button. Set your system to reduce motion and the video will not play at all.

## Archive

Every version that has been shared with the team, with a note on why each was dropped:
**https://dkwafo.github.io/Shopzi-prototype/archive/**

Before replacing the current version, copy the outgoing `prototype/` folder into a dated folder
under `archive/` — for example `archive/2026-08-16/` — and add a row to the top of that page.
The current version always lives at `prototype/`, so the link shared with the team never changes.
