# Keyword to Content Plan

## Overview

Turn a raw keyword list into a prioritized content plan. Get intent grouping, existing coverage checks, striking-distance quick wins, detailed content briefs for the top 10 opportunities, and a "do not write" list.

## The Prompt

```text
You are an SEO content strategist. I will give you a keyword list and information about my website. Your job is to turn this keyword list into a prioritized content plan.

**My Website:**
- Domain: [your domain]
- Business type: [what your business does]
- Existing pages (paste URLs of your main pages):
  [list your key page URLs]

**My Keyword List:**
[Paste your keyword list here. If you have GSC data, include the query, impressions, clicks, and average position columns. If you only have keywords and volume, that is fine too.]

**Your Tasks:**

1. **Group by intent.** Categorize every keyword as informational, commercial, navigational, or transactional. Explain your reasoning for any ambiguous keywords.

2. **Check existing coverage.** Based on the page URLs I provided, flag which keywords likely have existing pages and which are content gaps.

3. **Identify quick wins.** If I provided GSC position data, highlight keywords at positions 8-20 — these are striking-distance opportunities where improving existing content could reach page 1.

4. **Prioritize.** Rank keyword groups by opportunity: business relevance × search volume × current gap. Explain your prioritization.

5. **Create content briefs for the top 10 opportunities.** For each:
   - Recommended content type (blog post, service page, guide, FAQ, etc.)
   - Target keyword group (primary + related keywords)
   - Search intent and what the page should deliver
   - Suggested title (under 60 characters)
   - Suggested H2 structure (3-5 headings)
   - Word count estimate
   - Internal linking suggestions (which of my existing pages should link to/from this content)

6. **Flag content to improve (not create).** If a keyword is covered by an existing page that could rank higher, say "improve [URL]" instead of "create new page" and explain what to change.

Format the output as:
- Executive summary (3-5 sentences: key findings, biggest opportunities)
- Quick wins table (striking-distance keywords)
- Content gaps table (keywords with no existing coverage)
- Full content briefs (detailed plans for top 10)
- "Do not write" list (keywords that are not worth targeting and why)

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Export your keyword list from GSC (Performance > Search Results > Export) or from your keyword research tool
2. Gather the URLs of your main pages -- homepage, service pages, and top blog posts
3. Paste both into the prompt where indicated
4. Run in ChatGPT, Claude, or any AI tool
5. Review the output, especially the "improve vs. create" recommendations -- these save you from writing content you do not need

## Tips

- The more data you provide, the better the output. GSC exports with impressions and position data produce significantly better recommendations than a bare keyword list
- If your keyword list has more than 200 keywords, split it into 2-3 batches by topic area and run the prompt for each batch
- Do not skip the "existing pages" input -- without knowing what content you already have, the AI cannot identify content gaps accurately
- Cross-reference the AI's suggestions with your business priorities. A keyword with high volume but no connection to your services is not worth targeting

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [I Have Keywords but No Content Ideas. Now What?](https://brass-seo.com/blog/keywords-no-content-ideas-now-what)
- [Content Gap Finder](./content-gap-finder.md)
- [Keyword Opportunity Finder](./keyword-opportunity-finder.md)
