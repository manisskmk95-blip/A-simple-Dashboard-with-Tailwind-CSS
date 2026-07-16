# Influencer Performance Dashboard

A dashboard  showcasing the influencer consolidate performance data from the multiple social media platforms (Instagram, Tiktok, Youtube")

Built as a part of [4geeks academy], the "Dashboard Project with tailwind.css 

## Project goal

The influencer promotes 3 products across the platfroms and earns 1 15% commission on every sale.

| Product | Price |
|---|---|
| Product A | $ 50 |
| Product B | $120 |
| Product C | $ 80 |

>This dashboard answers their core business questions at a glance:
 
- How much money am I generating in commissions?
- Which products are generating the most revenue?
- How well are my ads converting (conversions / reach)?
- Which platforms are generating the best return (revenue / costs)?
- What is the engagement rate by platform and by product?

# Structure

>The dasboard is organized into three blocks, from top to bottom.

1. **KPI** - commission revenue, units sold, average selling price, coversion rate, and best ROI platforms.

2. **Drivers** - Conversion by stage (sales funnel)
- Performance by platform (Instagram, TikTok, YouTube, etc.)
- Quality (qualified lead ratio, attendance rate, pass rate)
-Performance by product (which product generates more commissions and better conversion)
- Activity (posts published, stories, reels, videos by platform)
- Engagement (likes, comments, shares, saves by platform)

3. **Operational Details**
- Products table: price, commissions generated, conversions, ROI per product
- Platforms table: reach, engagement, conversions, best platform by metric
- Campaigns table: dates, products promoted, results, performance
- Alerts: sharp drops in conversion, conversion spikes, performance anomalies
- Lists with filters: "top products", "top platforms", "top campaigns", "improvement opportunities"

# Tech

- Plain HTML5
- Tailwind CSS V4
- Mobile-first responsive

# Running it
- resize hte browser window  to check out different screen size

# Files

- 'index.html' - full markup and tailwind class
# Requirements checklist

 - [x] Layout: 3 blocks (KPIs, drivers, operational) with reusable cards/tables
- [x] Mobile-first, responsive at `sm:` / `lg:` / `xl:`
- [x] Semantic HTML (`header`, `main`, `section`, `table`, `footer`)
- [x] Tailwind utilities only (Tailwind v4 via `@tailwindcss/browser@4`, no `cdn.tailwindcss.com`/v3, no React/Vue)
- [x] Consistent card/table styling throughout
- [ ] Charts (optional, not used)

# update
- after the user get the final result , upload the project to github