# WordPress SEO Audit (No Plugin)

## Overview

Audits a WordPress site's core SEO settings using only native WordPress and theme-level features, without assuming Yoast or Rank Math.

## The Prompt

```text
Audit this WordPress site's core SEO settings without relying on Yoast, Rank Math, or any other SEO plugin:

Site: [site URL]
Current Plugins Installed: [list any SEO-related plugins, or say "none"]
Theme: [theme name, if known]

Check these WordPress-native and theme-level settings:
1. PERMALINK STRUCTURE — is it set to a clean, keyword-friendly format (Settings > Permalinks), not the default query-string format
2. TITLE TAGS & META DESCRIPTIONS — does the theme support editing these natively, or is a plugin genuinely required
3. XML SITEMAP — does WordPress's built-in sitemap (wp-sitemap.xml, native since WP 5.5) cover all published content
4. IMAGE ALT TEXT — spot-check whether uploaded media has alt text set
5. ROBOTS.TXT — is WordPress's default robots.txt blocking anything it shouldn't (check Settings > Reading > Search Engine Visibility)
6. CORE WEB VITALS RISK — flag any obviously heavy theme features (sliders, page builders, unoptimized images) likely to hurt page speed

For each check, report pass/fail/unclear and the specific setting or file to change if it fails.

Finish with: which of these genuinely requires a plugin to fix, versus what's a native WordPress setting most guides skip.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. List any SEO-related plugins currently installed, or say "none"
2. Note the active theme
3. Paste in your site URL

## Tips

- WordPress has shipped a native XML sitemap since version 5.5 — check that before assuming a plugin is required
- Permalink structure is a one-time setting most sites never revisit after initial setup
- Pair with a manual pass through Settings > Reading to confirm search engine visibility isn't accidentally disabled

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
