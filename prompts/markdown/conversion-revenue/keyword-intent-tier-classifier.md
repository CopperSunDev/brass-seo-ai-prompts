# Keyword Intent Tier Classifier

## Overview

Buckets a keyword list into informational, commercial, and transactional tiers so content effort goes where the buyer is.

## The Prompt

```text
Classify the following keyword list into intent tiers so I know where to spend content effort:

Keywords: [paste list, one per line]
Site/Industry Context: [what the site sells or does]

Sort each keyword into one of three tiers:

1. INFORMATIONAL — the searcher wants to learn, not buy (e.g., "what is X")
2. COMMERCIAL INVESTIGATION — the searcher is comparing options before deciding (e.g., "best X for Y", "X vs Y")
3. TRANSACTIONAL — the searcher is ready to act (e.g., "buy X", "X pricing", "X near me")

For each keyword, report:
- Tier assignment
- The specific words/patterns that signal that tier
- Whether existing content on the site likely already serves this intent, or if it's a gap
- Suggested content format for the tier (guide, comparison, landing page)

Finish with a ranked list: which 5 keywords are worth a dedicated commercial or transactional page first, based on estimated buyer proximity.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Pull a keyword list from GSC queries, a keyword tool, or your own brainstorm
2. Add brief context about what the site sells
3. Paste in

## Tips

- Informational content earns traffic; transactional content earns revenue — most sites over-invest in the former
- Re-run this classification whenever you plan a content calendar, not just once
- Watch for keywords that look informational but carry commercial intent underneath (e.g., "how to choose an SEO tool")

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
