# Refresh / Merge / Prune / Delete Verdict

## Overview

Runs one page through a decision tree and returns a single verdict, not a menu of options, so cleanup decisions stop stalling.

## The Prompt

```text
Run this one page through a decision tree and give me a single verdict — refresh, merge, prune, or delete:

Page URL: [URL]
Current Performance: [GSC clicks/impressions trend, GA4 engagement]
Page Age: [publish date or approximate age]
Content Topic: [what the page covers]
Similar Pages On Site: [any other URLs covering an overlapping topic, if known]

Walk the decision tree in this order:
1. Is another page on the site targeting the same primary query? If yes, lean MERGE.
2. Is the page still getting meaningful traffic but the information is outdated (stats, screenshots, pricing, dates)? If yes, lean REFRESH.
3. Is the page getting near-zero traffic and covering a topic with no ongoing relevance? If yes, lean DELETE (with redirect).
4. Is the page getting near-zero traffic but the topic still matters to the business? If yes, lean PRUNE FROM NAV but keep indexed, or REFRESH once.

Give ONE verdict, not a menu, with the specific reasoning that ruled out the other three.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Pull the page's GSC and GA4 performance
2. Note the page's approximate publish date
3. List any other pages on the site covering an overlapping topic, if you know of any
4. Paste in

## Tips

- A verdict that hedges between two options isn't a verdict — push for one answer per page
- Run this on your lowest-traffic 20 pages first; that's where cleanup decisions matter most
- Feed the output straight into the Redirect Mapping Assistant if the verdict is merge or delete

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
