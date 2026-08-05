# Webflow SEO Launch Checklist

## Overview

Audits a Webflow site's SEO setup from launch through its first real traffic, covering both static pages and CMS collections.

## The Prompt

```text
Audit this Webflow site's SEO setup from launch through its first real traffic:

Site: [site URL]
Launch Status: [pre-launch / just launched / launched N months ago]
CMS Collections In Use: [list any CMS collections, e.g. blog, products]

Check these Webflow-specific items:
1. SEO SETTINGS PANEL — are title tags, meta descriptions, and OG images set per-page (Page Settings) and per-CMS-item (Collection Settings), not left blank
2. 301 REDIRECTS — confirm Webflow's native redirect manager has entries for any URLs changed since launch
3. SITEMAP & INDEXING — confirm the auto-generated sitemap.xml is submitted to GSC and that CMS collection pages are included
4. CANONICAL TAGS — check for duplicate content across CMS filtering/pagination and whether canonicals are set correctly
5. PERFORMANCE — flag any heavy interactions/animations likely hurting Core Web Vitals on mobile

For each item, report pass/fail and the specific Webflow panel to fix it in.

Finish with the single most important thing to fix before (or right after) launch.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Note your launch status and which CMS collections are in use
2. Paste in your site URL
3. Re-run after any major CMS content addition, since collection-level settings are set per item

## Tips

- CMS collection SEO settings are set per-item, not globally — a blank field on one blog post won't be caught by checking the template alone
- Webflow's native redirect manager only helps if entries are actually added when URLs change
- Heavy Webflow interactions are a common mobile Core Web Vitals drag that's easy to miss on desktop review

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
