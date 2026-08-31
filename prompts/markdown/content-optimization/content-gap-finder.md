# Content Gap Finder

## Overview

Analyze your GSC query export to find keywords you rank for but have no dedicated page about. Get content gaps, striking-distance opportunities, and underperforming pages -- all sorted by impressions with content briefs for the top gaps.

## The Prompt

```text
Analyze this Google Search Console performance data to find content gaps on my site.

Here is my GSC query export (last 3 months). Each row has: query, clicks, impressions, CTR, average position.

[PASTE YOUR GSC QUERY EXPORT HERE]

Here is a list of my site's main pages and their primary topics:

[PASTE YOUR PAGE LIST HERE — format: URL | Primary Topic/Keyword]

Analyze the data and find:

1. CONTENT GAPS (no dedicated page exists)
   - Queries with 100+ impressions where no page in my list targets this topic
   - Group related queries into topic clusters (e.g., "emergency plumber cost" and "emergency plumbing rates" are the same topic)
   - For each gap, show: the query cluster, total impressions, average position, and a suggested page title

2. STRIKING-DISTANCE OPPORTUNITIES (positions 8-20)
   - Queries ranking 8-20 with high impressions relative to my site's average
   - Whether a dedicated page exists or if an existing page covers it weakly
   - Specific recommendation: create new page, expand existing page, or improve existing page

3. UNDERPERFORMING PAGES (page exists but CTR is low)
   - Queries where position is 1-5 but CTR is below 3%
   - These pages rank well but fail to earn clicks — likely a title tag or meta description issue, not a content gap

Sort all results by impressions (highest first). For the top 10 content gaps, write a one-sentence content brief describing what the new page should cover.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Export your GSC query data: Performance > set date range (last 3 months) > Export > choose CSV or Google Sheets
2. Create a simple list of your main pages and their primary topics (your homepage, service pages, and top blog posts are usually enough)
3. Paste both into the prompt and run it in ChatGPT, Claude, Gemini, or any AI chat tool
4. Review the suggested content gaps and cross-check them against your keyword targeting strategy

## Tips

- Use 3 months of data instead of 1 month to smooth out seasonal fluctuations
- Focus on queries with 100+ impressions -- below that, the search volume may not justify a new page
- Group related queries before creating pages (you do not need separate pages for "emergency plumber cost" and "how much does an emergency plumber cost")
- Run this analysis quarterly to catch new gaps as your search landscape evolves
- If a gap query has a position of 40+, you may need to build topical authority first before a dedicated page will rank

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [Finding Content Gaps Without a $200/Month Tool](https://brass-seo.com/blog/finding-content-gaps-without-expensive-tool)
- [Keyword Opportunity Finder](./keyword-opportunity-finder.md)
