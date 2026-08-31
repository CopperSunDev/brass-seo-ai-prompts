# Title Tag Writer

## Overview

Generate optimized title tags for your website pages using actual GSC search data. Instead of guessing which keywords matter, this prompt uses the keywords that already drive impressions to each page.

## The Prompt

```text
Write optimized title tags for my website pages using my actual search data.

Pages to optimize (from GSC Performance > Pages report):
[Paste your top pages with: URL, current title tag, clicks, impressions, CTR, average position]

Top queries per page (from GSC Performance > Queries, filtered by page):
[For each page above, paste the top 5 queries with impressions and position]

Business name: [your business name]
Business type: [what you do]
Location (if local): [city/state, or skip if not local]

For each page, generate 3 title tag options that:
- Stay under 60 characters (count each one)
- Lead with the highest-impression keyword from that page's actual GSC query data
- Include a benefit, hook, or specificity that differentiates from competitors
- Place the brand name at the end after a separator (| or -)
- Match the page's search intent (informational, commercial, navigational)

For each option, provide:
1. The title tag text
2. Exact character count
3. Which GSC query it targets and why
4. Expected CTR impact (based on whether the current title misses the top query)

Then recommend which option is best for each page and explain why.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Open GSC > Performance > Pages. Export your top 10-20 pages by impressions
2. For each page, click through to see which queries drive impressions to it
3. Check each page's current title tag (view source or use the site: search method)
4. Paste everything into the prompt and run in ChatGPT, Claude, or any AI tool
5. Review the suggestions and update your title tags in your CMS or HTML

## Tips

- Focus on pages with high impressions but low CTR first — those are the biggest opportunities
- If a page's top query does not appear in its current title tag, that is almost always worth fixing
- Do not change titles on pages that are already performing well (high CTR, good position)
- After changing a title, wait 2-4 weeks before judging results

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [How to Write Title Tags That Get Clicks](https://brass-seo.com/blog/title-tags-that-get-clicks)
- [Meta Description Writer](./meta-description-writer.md)
