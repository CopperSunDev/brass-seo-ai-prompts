# Redirect Mapping Assistant

## Overview

Maps a page being merged or pruned to the correct consolidation target so SEO equity isn't lost in the process.

## The Prompt

```text
Map a page being merged or pruned to the correct consolidation target so I don't lose SEO equity:

Page Being Removed: [URL]
Reason For Removal: [merge / prune / outdated and no longer relevant]
Candidate Target Pages: [list 2-4 URLs that might be a good redirect destination]
Content Overlap: [briefly describe what the removed page covered vs. what each candidate covers]

For each candidate target, score it on:
1. TOPICAL MATCH — how closely the target actually covers the same query/intent
2. TRAFFIC HEALTH — is the target page itself healthy, or would redirecting into it drag it down
3. USER EXPERIENCE — would a visitor following the old URL land somewhere that still answers their original question

Recommend the single best redirect target, or say clearly if none of the candidates are close enough and a redirect to the homepage/category page is more honest than forcing a bad match.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Confirm the removal decision first (use the Refresh/Merge/Prune/Delete Verdict prompt if unsure)
2. List 2-4 candidate pages that might serve as the redirect target
3. Describe the content overlap between the removed page and each candidate

## Tips

- A forced redirect to a poorly matched page can hurt the target page more than losing the source page helps
- When no candidate is a good match, a category or homepage redirect beats a bad 1:1 match
- Test the final redirect chain — redirects that point to another redirect (chains) lose equity

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
