# Traffic-to-Sales Leak Diagnostic

## Overview

Walks the funnel from impression to conversion to find exactly where SEO traffic stops turning into sales.

## The Prompt

```text
Diagnose where my SEO traffic is failing to turn into sales, walking the funnel from impression to conversion:

Site: [site URL]
Date Range: [last 90 days]
GSC Data: [impressions, clicks, CTR, average position for top queries/pages]
GA4 Data: [sessions, engagement/bounce rate, conversion rate by landing page]
Primary Conversion Event: [e.g., trial signup]
Known Baseline: [conversion rate you'd consider healthy, if known]

Walk through the funnel in order and flag where the leak most likely sits:

1. IMPRESSION-TO-CLICK LEAK — high impressions, low CTR (title/meta problem, or wrong-intent query)
2. CLICK-TO-ENGAGEMENT LEAK — healthy CTR, high bounce/exit rate (landing page mismatch)
3. ENGAGEMENT-TO-CONVERSION LEAK — people stay, but don't convert (weak or missing CTA, broken conversion path, or wrong-intent traffic that engages but never intended to buy)
4. TRACKING LEAK — check whether the conversion event is actually firing correctly before blaming the funnel

For each leak point found, cite the specific pages/queries showing the pattern and rank the leaks by estimated lost conversions.

Finish with the single highest-leverage fix to try first.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Pull the GSC Performance export for your top 20-30 queries/pages
2. Pull the GA4 landing-page report with engagement rate and conversions
3. Note your target conversion rate if you have one
4. Paste both into the prompt

## Tips

- Rule out tracking issues first — a "leak" that's actually a broken GA4 event wastes fix effort elsewhere
- Compare pages against each other, not a single global average — different intent tiers convert at different natural rates
- Re-run after implementing a fix to confirm the signal actually moved

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
