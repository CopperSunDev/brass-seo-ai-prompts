# Keyword Cannibalization Finder

## Overview

Finds pages on a site competing against each other for the same search query and recommends merge, canonical, or differentiate.

## The Prompt

```text
Find pages on my site competing against each other for the same search query:

Site: [site URL]
GSC Query Data: [paste query-level data showing which pages rank for which queries]

For each query where more than one page on the site receives impressions:
1. List the competing pages and their individual position/clicks/impressions for that query
2. Determine whether this is TRUE cannibalization (both pages target the same intent, splitting authority) or ACCEPTABLE overlap (pages serve genuinely different sub-intents or funnel stages)
3. For true cannibalization, recommend the fix: merge into one page, canonical tag pointing to the stronger page, or differentiate the weaker page's target query entirely

Rank the cannibalization cases by combined lost traffic potential — how much a single unified page might outrank the sum of the two split pages.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Export GSC query data with the pages ranking for each query (Performance report, filter by query, add page dimension)
2. Paste in
3. Review each flagged case before acting — not every overlap is a problem

## Tips

- Two pages ranking for the same query isn't automatically a problem — check for genuinely different intent first
- A merge is usually stronger than a canonical when both pages are thin; canonical is better when one page is already strong
- Re-run after any site restructure, since cannibalization often reappears as new content gets added

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
