# Shopify SEO Settings Checklist

## Overview

Audits a Shopify store against the platform-specific settings that actually move rankings, beyond generic SEO advice.

## The Prompt

```text
Audit this Shopify store against the settings that actually move rankings, beyond generic SEO advice:

Store: [store URL]
Theme: [theme name]
Current Setup: [describe what's configured, or say "default theme settings"]

Check these Shopify-specific settings:
1. URL STRUCTURE — are product/collection URLs clean, or do they carry unnecessary Shopify-default segments
2. DUPLICATE CONTENT — check for the classic Shopify collection/product duplicate-URL issue and whether canonical tags are handling it
3. TITLE TAGS & META DESCRIPTIONS — are these set per-product/collection, or left on Shopify's auto-generated defaults
4. IMAGE FILENAMES & ALT TEXT — spot-check product images for descriptive filenames and alt text, not "IMG_1234"
5. APP BLOAT — flag installed apps likely adding unnecessary JavaScript/CSS that could slow the storefront
6. BLOG/XML SITEMAP — confirm sitemap.xml is being generated and submitted, and that the blog isn't orphaned from main navigation

For each item, report pass/fail and the exact admin panel location to fix it.

Finish with the 3 highest-impact fixes for a store this size.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Note your theme and current SEO setup
2. Paste in your store URL
3. Ask specifically about any apps installed if app bloat is a concern

## Tips

- The collection/product duplicate-URL issue is one of the most common Shopify-specific SEO problems and is easy to miss
- Check installed apps periodically — each one is a potential source of unnecessary page weight
- Product images uploaded in bulk often skip alt text entirely; it's worth a manual spot-check

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
