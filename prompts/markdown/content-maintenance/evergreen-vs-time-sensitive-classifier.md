# Evergreen vs. Time-Sensitive Classifier

## Overview

Classifies published posts by how much upkeep each one actually needs, flagging which will age and when to recheck them.

## The Prompt

```text
Classify my published posts by how much upkeep each one actually needs:

Posts: [list post titles/URLs, or paste a full post list]
Post Content Summary: [brief note on what each covers, if not obvious from title]

Classify each post into:
1. EVERGREEN — no dates, prices, or version-specific facts; the advice holds regardless of when it's read
2. TIME-SENSITIVE — contains specific stats, prices, product versions, or "as of [year]" framing that will age
3. SEASONAL — tied to a recurring event or period (a year-in-review, a seasonal guide) that needs refreshing on a schedule, not just when it decays

For TIME-SENSITIVE and SEASONAL posts, note the specific element that will go stale first (a stat, a price, a screenshot) and a suggested recheck interval.

Output as a simple table: post, classification, stale-first element (if applicable), recheck interval.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. List your published posts, titles or URLs
2. Add a brief content summary for any where the topic isn't obvious from the title alone
3. Paste in

## Tips

- Most sites underestimate how many "evergreen" posts actually contain a stealth time-sensitive fact (a price, a version number)
- Feed the recheck intervals straight into the 6-Month Re-Optimization Calendar Builder
- Reclassify after any major product or pricing change — posts that were evergreen can become time-sensitive overnight

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
