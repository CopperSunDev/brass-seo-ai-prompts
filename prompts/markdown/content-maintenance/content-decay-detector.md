# Content Decay Detector

## Overview

Reads a Google Search Console trend export and flags pages in a slow, silent decline before it's visible in a single monthly snapshot.

## The Prompt

```text
Read my Google Search Console trend data and flag pages in a slow, silent decline before it's visible in a single monthly snapshot:

Site: [site URL]
GSC Data: [paste 12-month trend export by page — clicks/impressions per month]
Pages To Check: [specific URLs, or say "all top 50 by traffic"]

For each page, calculate:
1. TREND DIRECTION — is the page's click trend up, flat, or down over the full period
2. DECAY RATE — if declining, what's the month-over-month percentage drop
3. DECAY STAGE — early (just started, under 10% cumulative loss), mid (10-30% cumulative loss), late (30%+ cumulative loss, someone probably already noticed)
4. LIKELY CAUSE — content aging (stats/dates out of date), algorithm update timing, new competitor, or cannibalization from a newer page on the same site

Rank all declining pages by combined traffic value and decay rate, so the biggest quiet losses surface first, not just the fastest droppers.

Finish with the 5 pages where catching this now, instead of in 6 months, saves the most traffic.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Export a 12-month trend by page from GSC Performance (not just a single-period snapshot)
2. List specific URLs to check, or ask for all top 50 by traffic
3. Paste in

## Tips

- A single month-over-month comparison hides slow decay — always use the full trend, not two snapshots
- Decay stage matters more than raw traffic loss — a big page in early decay is more urgent than a small page in late decay
- Brass-SEO's Declining Pages report tracks this automatically from connected GSC data

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
