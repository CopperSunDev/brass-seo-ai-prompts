# Content Pruning Candidate Finder

## Overview

Finds pages worth pruning without losing the SEO equity they've built, checking backlinks before recommending removal.

## The Prompt

```text
Find pages worth pruning without losing the SEO equity they've built:

Site: [site URL]
GSC Data: [12-month traffic export for all indexed pages]
Site Section Context: [what parts of the site are core vs. peripheral]

Flag pages as PRUNING CANDIDATES if they meet BOTH:
1. Near-zero organic traffic over the full period (define your own threshold, default to under 5 clicks/month)
2. No meaningful internal links pointing to them from higher-traffic pages (orphaned or near-orphaned)

For each candidate, do NOT just recommend deletion. Instead determine:
- Does it have any backlinks? (check before removing — equity worth preserving via redirect)
- Is there a live, related page it should 301 redirect to?
- Is it safe to fully remove with no redirect (truly dead topic, no backlinks, no equity)?

Output a table: URL, traffic, backlinks (yes/no if known), recommended action (redirect-to-X, safe-delete, or keep-and-refresh-instead), and reasoning.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Export 12 months of GSC traffic for all indexed pages
2. Note which sections of the site are core vs. peripheral to the business
3. Paste in

## Tips

- Always check backlinks before deleting — a zero-traffic page can still carry link equity worth redirecting, not losing
- Set your own traffic threshold based on site size; 5 clicks/month is a starting point, not a rule
- Pair with the Redirect Mapping Assistant once candidates are confirmed

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
