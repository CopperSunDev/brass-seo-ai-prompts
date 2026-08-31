# Declining Pages Analyzer

## Overview

Analyze exported Google Search Console data across two date ranges to find pages losing rankings. Get a prioritized list with severity ratings, likely causes, and suggested fixes.

## The Prompt

```text
Analyze the following Google Search Console data to find pages that are declining in search performance.

DATA FORMAT:
I will provide two sets of GSC Performance data exported at the Page level:
- Period 1 (recent): [Paste your last-28-days export here — columns: Page, Clicks, Impressions, CTR, Position]
- Period 2 (previous): [Paste your previous-28-days export here — same columns]

ANALYSIS INSTRUCTIONS:
1. Match pages across both periods by URL
2. For each page, calculate:
   - Position change (positive = declined, negative = improved)
   - Click change (absolute and percentage)
   - Impression change (absolute and percentage)
   - CTR change

3. Flag pages meeting ANY of these decline criteria:
   - Position worsened by 3+ spots
   - Clicks dropped by 20%+ AND position worsened
   - Impressions dropped by 30%+ (may indicate Google showing the page less)

4. Classify severity:
   - CRITICAL: Position dropped 5+ spots AND clicks dropped 30%+
   - HIGH: Position dropped 3-5 spots AND clicks dropped 20%+
   - MODERATE: Position dropped 3+ spots but clicks stable (early warning)
   - WATCH: Impressions dropping but position stable (Google may be testing alternatives)

5. For each declining page, suggest a likely cause based on the data pattern:
   - Position drop + impression drop = possible algorithm change or new competitor
   - Position drop + stable impressions = competitors overtaking you for same queries
   - Stable position + click drop = your title/description may need updating
   - Impression drop + stable position = seasonal or query volume change

OUTPUT FORMAT:
Create a prioritized table with columns: URL, Severity, Position Change, Click Change (%), Impression Change (%), Likely Cause, Suggested Action

Sort by severity (CRITICAL first), then by absolute click loss.

End with a summary: total pages declining, estimated total clicks lost, and the top 3 pages to fix first with specific recommendations.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Export your GSC Performance data at the **Pages** level for the last 28 days
2. Export the same report for the previous 28 days
3. Paste both data sets into the prompt where indicated
4. Run the prompt in ChatGPT, Claude, or any AI tool
5. Review the prioritized list and start with CRITICAL pages

## Tips

- Run this comparison monthly at minimum to catch declines early
- If a page shows as MODERATE, check it again in two weeks before acting — it may recover on its own
- Pages with impression drops but stable positions may be seasonal — compare against the same period last year if you have the data
- Focus your fixes on pages that drive business outcomes (service pages, product pages) before blog posts

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [Your Pages Are Declining and You Don't Know It](https://brass-seo.com/blog/pages-declining-and-you-dont-know-it)
