# O-Zed's Essentials

Affordable AliExpress finds curated for you — Home Decor, Beauty, Kitchen, Fashion & Lifestyle.

## Site Structure

```
index.html          → Homepage (shows preview of all categories)
home-decor.html     → Full Home Decor category
kitchen.html        → Full Kitchen category
beauty.html         → Full Beauty & Wellness category
fashion.html        → Full Fashion category
lifestyle.html      → Full Lifestyle category
vercel.json         → Vercel deployment config
```

## How to Update Products

1. Open the relevant HTML file
2. Find the product card you want to update
3. Change the emoji, name, price, badge or affiliate link
4. To add a new product — copy any card block and paste it inside the grid div
5. To add a real image — replace `<div class="ph">emoji</div>` with `<img src="IMAGE_URL" alt="name">`
6. Commit and push to GitHub — Vercel auto-deploys instantly

## Badge Types
- `class="bdg hot"` → Red — popular products
- `class="bdg new"` → Green — newly added
- `class="bdg sale"` → Gold — trending/discounted

## Affiliate Disclosure
All pages include the required affiliate disclosure footer. Always add #ad to Pinterest pin descriptions linking to this site.
