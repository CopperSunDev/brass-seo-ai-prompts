# GA4 Attribution Sanity-Check

## Overview

Checks a GA4 setup for common attribution issues that can make SEO look worse than it actually is.

## The Prompt

```text
Check my GA4 setup for attribution issues that could make SEO look worse than it is:

Site: [site URL]
GA4 Property Settings: [attribution model in use, if known — e.g., data-driven, last-click]
Conversion Path Example: [describe a typical customer journey, e.g., "finds blog post, leaves, returns via branded search, converts"]
Current Organic Numbers: [organic sessions and conversions from GA4]

Check for these common misattribution patterns:

1. SELF-REFERRAL — the site's own domain showing up as a traffic source, splitting credit that belongs to organic
2. CROSS-DOMAIN TRACKING GAPS — if checkout or booking happens on a different domain/subdomain, is linking configured
3. LAST-CLICK BLIND SPOT — whether a data-driven or first-touch view would credit organic differently than last-click
4. CONSENT MODE GAPS — whether cookie consent settings are silently dropping a portion of sessions before they're ever attributed
5. DIRECT TRAFFIC INFLATION — untagged or app-based traffic incorrectly bucketed as "Direct" that's actually organic-influenced

For each pattern found, explain the fix and roughly how much it likely understates organic's real contribution.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Check GA4 Admin > Attribution settings for the model currently in use
2. Describe one or two typical customer journeys in plain language
3. Note current organic session and conversion counts
4. Paste in

## Tips

- Self-referral and cross-domain gaps are the two most common causes of organic looking artificially weak
- Switching attribution models changes the numbers, not the reality — use it to understand the range, not to pick whichever number looks best
- Re-check after any domain, subdomain, or checkout-platform change

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
