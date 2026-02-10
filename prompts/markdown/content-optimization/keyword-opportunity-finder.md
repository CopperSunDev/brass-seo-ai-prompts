# Keyword Opportunity Finder

## Overview

Analyze your Google Search Console keyword data to find the best SEO opportunities. Identifies quick wins (positions 5-15), strategic targets (positions 15-30), keyword groupings, and provides a prioritized monthly action plan.

## The Prompt

```text
Analyze the following keyword data from Google Search Console and identify the best SEO opportunities:

Website: [your website URL]
Industry: [your industry]
Business Type: [e.g., local service, e-commerce, SaaS, blog]
Primary Goal: [e.g., more leads, more sales, more traffic, brand awareness]

GSC Keyword Data (paste your top 20-50 queries with metrics):
[Paste query, clicks, impressions, CTR, position data from GSC Performance report]

OR describe your situation:
- Top keywords you rank for: [list them]
- Keywords you want to rank for: [list them]
- Current monthly organic traffic: [approximate number]

Please analyze and provide:

1. QUICK WINS (can improve within 2-4 weeks)
   - Keywords ranking positions 5-15 with high impressions
   - Keywords with below-average CTR (title/meta description fixes)
   - Pages ranking for valuable terms that need minor content updates

2. STRATEGIC TARGETS (1-3 month timeline)
   - Keywords ranking positions 15-30 worth pushing to page 1
   - Content gaps: valuable keywords you should target but currently don't
   - Long-tail variations of your best-performing keywords

3. KEYWORD GROUPING
   - Group related keywords into content themes
   - Identify which page should target each keyword group
   - Flag any keyword cannibalization (multiple pages competing for same term)

4. ACTION PLAN
   - Top 5 keywords to focus on this month, with specific actions for each
   - Content to create or update for each target keyword
   - Internal linking recommendations to strengthen target pages
   - Expected timeline for seeing results

For each recommendation, explain why it matters and estimate the effort required (low/medium/high).

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Open Google Search Console and go to **Performance > Search Results**
2. Set the date range to last 3 months for reliable data
3. Export your query data or copy the top 20-50 queries with clicks, impressions, CTR, and position
4. Paste into the prompt along with your business details
5. Run in ChatGPT, Claude, or any AI tool

## Expected Output

- Categorized opportunities (quick wins vs. strategic targets)
- Keyword groupings mapped to specific pages
- Keyword cannibalization warnings
- Monthly action plan with 5 priority keywords and specific steps

## Tips

- Include at least 20 keywords for meaningful analysis (50+ is ideal)
- Add your business goals so the AI can prioritize relevant keywords
- Mention your competitors if you want gap analysis
- Run this quarterly to keep your keyword strategy current

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [What Keywords Should I Target?](https://brass-seo.com/blog/what-keywords-should-i-target)
- [Content Gap Analysis](./content-gap-analysis.md)
- [Title & Meta Description Generator](./title-meta-description-generator.md)
