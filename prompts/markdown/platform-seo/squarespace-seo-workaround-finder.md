# Squarespace SEO Workaround Finder

## Overview

Finds workarounds for Squarespace's SEO limitations, distinguishing genuine platform limits from fixable settings.

## The Prompt

```text
Find workarounds for Squarespace's SEO limitations on this specific site:

Site: [site URL]
Template: [template name, if known]
Known Pain Point: [describe the specific limitation you're hitting, if any]

Check for these common Squarespace constraints and whether a workaround exists:
1. URL SLUG CONTROL — can collection/page URLs be fully customized, or is Squarespace forcing a structure
2. SCHEMA MARKUP — Squarespace's built-in structured data is limited; identify what's missing that code injection could add
3. SITE SPEED — Squarespace's templates load third-party fonts/scripts by default; flag anything removable via Code Injection
4. BLOG CATEGORY/TAG SEO — check whether category and tag pages are indexable and whether they're causing thin-content issues
5. 301 REDIRECTS — confirm the URL Mappings tool is being used correctly for any changed URLs, not left to 404

For each constraint, state clearly whether it's a genuine platform limit or something fixable through Squarespace's own tools (Code Injection, URL Mappings, Advanced Settings).

Finish with the workarounds worth doing versus the ones not worth fighting the platform for.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Note your template and describe any specific limitation you're already running into
2. Paste in your site URL
3. Ask follow-up questions about any single constraint the audit flags

## Tips

- Code Injection is Squarespace's escape hatch for most missing SEO features — check it before assuming something can't be fixed
- URL Mappings must be set up manually whenever a page's URL changes; Squarespace doesn't do this automatically
- Some limits genuinely aren't worth fighting — know which ones before spending time on them

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
