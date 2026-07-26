# My Business — Claude Context
> Fill in every [bracket]. Claude reads this file at the start of EVERY session — this is how it knows your business instead of starting cold. Update it whenever something changes. This file is what makes Claude YOURS.


## Who I Am
- Name: [your name]
- Business: Amazon FBA seller — [arbitrage / wholesale / both]
- Experience: [new to selling / plateaued at $X/mo / scaling]
- Time I can put in: [hours per week]

## My Capital & Buy Criteria (Claude: enforce these on every sourcing task)
- Deployment capital: $[amount] deployed · $[amount] held as buffer
- Max single buy: $[amount]
- Minimum ROI after ALL fees: [30]%
- Minimum profit per unit: $[amount]
- Sell-price band: $[15]–$[50]
- Demand bar: [e.g., BSR proves it sells 10+/month]
- Never buy: gated-for-me items, hazmat, meltables, [your additions]

## My Amazon Account
- Account age/health: [new / established, any flags]
- Ungated in: [categories/brands]
- Currently gated in (working on): [categories/brands]
- Fulfillment: [FBA / FBM / both] · Prep: [self / prep center name]

## My Niche & Watchlist
- Categories I know: [e.g., toys, kitchen, pet]
- Brands I follow: [list]
- Sellers I monitor: [storefront names/IDs]
- Suppliers I use: [list — and any I've vetted or rejected]

## The 3-Layer System (how I want you to work)
- Directives (SOPs) live in `directives/` — check there FIRST on any task
- Scripts live in `execution/` — check for an existing tool before building
- You orchestrate: read the SOP, run the tools, handle errors, bring me decisions
- Full framework: `.claude/skills/doe.md`

## Hard Rules (never cross these)
1. Never call anything a BUY without all five fields: Amazon link, ASIN, verified buy link, ROI, profit.
2. Never send anything to a real person (customer, supplier, Amazon) without my explicit OK on that send.
3. Never spend money, credits, or paid tokens without asking first.
4. Money math uses MY fee assumptions above — conservative, all fees included.
5. If you don't know something about my account or a product — check the data, don't guess.

## Learned Rules (append here — one line each time we fix a mistake)
1. [Example: Never trust a title's "pack of N" without verifying pack count in images + reviews.]
2.
3.
