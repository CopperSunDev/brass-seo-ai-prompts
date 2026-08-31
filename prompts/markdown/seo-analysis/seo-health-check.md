# SEO Health Check

## Overview

Analyze your GSC and GA4 data to determine whether your SEO is working. Checks four signals — organic traffic trend, keyword positions, click-through rate, and landing page engagement — and delivers a verdict with prioritized action items.

## The Prompt

```text
Analyze my SEO performance data and tell me whether my SEO is working.

GSC Performance Data (last 28 days vs previous 28 days):
[Paste your GSC Performance export — queries, pages, clicks, impressions, CTR, position for both periods]

GA4 Traffic Data:
- Organic sessions this period: [number]
- Organic sessions previous period: [number]
- Top organic landing pages with engagement rates: [paste from GA4 Landing Page report, filtered to Organic Search]

Analyze these four signals:

1. **Organic Traffic Trend**: Are organic sessions growing, stable, or declining? By what percentage?
2. **Keyword Positions**: Which target keywords moved significantly (3+ positions)? Which direction?
3. **Click-Through Rate**: Are any pages with 500+ impressions showing CTR below expected for their position? (Position 1: 20-35%, Position 2: 10-18%, Position 3: 7-12%, Position 4-5: 4-8%)
4. **Landing Page Engagement**: Are any high-traffic organic pages showing engagement rates significantly below the site average?

Provide:
- An overall verdict: Improving, Stable, or Declining
- The strongest signal (best-performing area)
- The biggest concern (area needing attention)
- Three specific actions to take this month, prioritized by expected impact

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Export your GSC Performance report for the last 28 days (compare to previous 28 days)
2. Open GA4 > Traffic Acquisition, note organic sessions for both periods
3. Open GA4 > Landing Page with an Organic Search filter, copy the top 10-15 pages with engagement rates
4. Paste everything into the prompt and run in ChatGPT, Claude, or any AI tool
5. Review the verdict and action items

## Tips

- Run this check monthly on the same day for consistent comparisons
- Export GSC data by both Queries and Pages — the prompt uses both views
- If a keyword dropped 5+ positions, check whether a competitor published new content or Google changed the SERP layout
- Seasonal businesses should compare to the same month last year instead of the previous month

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [How to Tell If Your SEO Is Working](https://brass-seo.com/blog/how-to-tell-if-your-seo-is-working)
- [Declining Pages Analyzer](./declining-pages-analyzer.md)
