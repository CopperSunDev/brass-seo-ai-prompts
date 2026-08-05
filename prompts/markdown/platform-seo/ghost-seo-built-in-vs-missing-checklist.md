# Ghost SEO Built-In vs. Missing Checklist

## Overview

Audits a Ghost blog against what Ghost handles natively for SEO versus what's genuinely missing and needs a workaround.

## The Prompt

```text
Audit this Ghost blog against what Ghost handles natively for SEO versus what's genuinely missing:

Site: [site URL]
Ghost Theme: [theme name, default Casper or custom]
Current Setup: [describe any SEO-related settings changed from default]

Check these items, noting which are Ghost-native and which require a workaround:
1. META TITLE & DESCRIPTION — Ghost supports per-post SEO fields natively; confirm they're actually being filled in, not left blank
2. STRUCTURED DATA — Ghost includes JSON-LD Article schema by default; confirm it's rendering correctly for this theme
3. XML SITEMAP — Ghost auto-generates sitemap.xml; confirm it's submitted to GSC
4. CANONICAL URLS — Ghost sets canonical tags automatically; check for any custom domain or subdirectory setup that could break this
5. TAG PAGE SEO — Ghost's tag archive pages can be thin content; check whether they're indexable and worth it, or should be noindexed

For each item, state clearly: built-in and already working, built-in but not configured, or genuinely missing and needing a workaround.

Finish with the one setting most solo bloggers on Ghost forget to check.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Note your theme (default Casper or custom) and any SEO settings already changed
2. Paste in your site URL
3. Flag any custom domain or subdirectory setup so canonical tags can be checked correctly

## Tips

- Ghost handles more SEO natively than most platforms — most gaps are settings left blank, not missing features
- Tag archive pages are the most commonly overlooked thin-content risk on a Ghost blog
- Custom domain or subdirectory setups are the most likely place for canonical tags to break silently

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
