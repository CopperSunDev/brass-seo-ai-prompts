# Money Pages vs. Traffic Magnets Finder

## Overview

Cross-references Google Search Console clicks against Google Analytics 4 conversions to separate pages that rank from pages that actually make money.

## The Prompt

```text
Analyze my Google Search Console and Google Analytics 4 data together to separate pages that rank from pages that actually make money:

Site: [site URL]
Date Range: [last 90 days / last 12 months]
GSC Data: [paste top pages by clicks/impressions export]
GA4 Data: [paste top pages by conversions/revenue export]
Primary Conversion Event: [e.g., trial signup, purchase, lead form]

For each page in the top 20 by GSC clicks, cross-reference against GA4 and classify into one of four buckets:

1. MONEY PAGES — high clicks AND high conversions/revenue relative to traffic
2. TRAFFIC MAGNETS — high clicks, but conversion rate below site average
3. HIDDEN EARNERS — moderate or low clicks, but conversion rate well above site average
4. DEAD WEIGHT — low clicks and low conversions

For each page, report:
- GSC clicks and average position
- GA4 conversions/revenue and conversion rate
- Bucket assignment and the reasoning
- One specific recommendation (promote, fix landing page, add internal links, leave alone)

Finish with:
- The 3 "Hidden Earners" most worth more traffic
- The 3 "Traffic Magnets" most worth a conversion-path fix

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Export your top 20-50 pages by clicks from GSC (Performance report)
2. Export the same pages' conversions/revenue from GA4 (landing-page or conversions report)
3. Paste both exports in
4. Name your primary conversion event exactly as it appears in GA4

## Tips

- A page can be a "Traffic Magnet" for good reason — some pages exist to support the funnel, not close it
- Rerun quarterly since conversion rates drift as content ages
- Brass-SEO's Valuable Pages report runs this cross-reference automatically from connected GSC + GA4 data

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
