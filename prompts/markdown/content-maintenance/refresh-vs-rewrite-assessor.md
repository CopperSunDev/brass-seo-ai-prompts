# Refresh vs. Rewrite Assessor

## Overview

Decides whether a page needs a light data refresh or a full rewrite, based on structural soundness and factual drift, not just traffic decline.

## The Prompt

```text
Decide whether this page needs a light data refresh or a full rewrite:

Page URL: [URL]
Page Content: [paste the current content, or a summary of it]
Current Performance: [GSC clicks/impressions trend]
What's Changed Since Publish: [any known product, pricing, or industry changes relevant to this topic]

Assess against these criteria:
1. STRUCTURAL SOUNDNESS — is the heading structure, argument, and format still the right shape for the topic, or has the format itself aged out
2. FACTUAL DRIFT — how much of the content is now inaccurate (stats, pricing, screenshots, dates, product features)
3. COMPETITIVE GAP — does the page still cover the topic as thoroughly as what currently ranks above it
4. TRAFFIC SIGNAL — is the decline (if any) severe enough to suggest the page needs more than a data update

Give a single verdict: QUICK REFRESH (update stats/dates/screenshots only, structure is fine) or FULL REWRITE (structure or depth no longer serves the topic), with the specific reasoning.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Paste the page's current content or a close summary
2. Pull its GSC performance trend
3. Note anything specific that's changed since publish (pricing, product features, industry shifts)

## Tips

- A page with a sound structure rarely needs a full rewrite even if every stat is stale — swap the facts, keep the shape
- A page that's structurally thin will keep decaying no matter how many stats get updated
- Check what currently outranks the page before deciding — competitive depth is often the real gap, not the dates

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
