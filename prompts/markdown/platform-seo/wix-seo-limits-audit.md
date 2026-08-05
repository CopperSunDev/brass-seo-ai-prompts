# Wix SEO Limits Audit

## Overview

Audits a Wix site for the platform limits that most affect SEO, and separates what Wix's own tools can fix from what's a genuine ceiling.

## The Prompt

```text
Audit this Wix site for the platform limits that most affect SEO, and what Wix's own tools can and can't fix:

Site: [site URL]
Wix Plan: [plan tier, if known]
Current SEO Setup: [describe what's configured, e.g. Wix SEO Wiz, manual settings]

Check these Wix-specific constraints:
1. URL STRUCTURE — check for Wix's historical URL pattern issues (e.g., dynamic pages, app-generated URLs) and whether clean URLs are enabled
2. SEO SETTINGS PANEL — confirm title tags, meta descriptions, and structured data are set through Wix's SEO panel per page, not left on defaults
3. SITE SPEED — Wix's editor can add render-heavy elements; flag anything obviously slowing the site (video backgrounds, excessive animations)
4. MOBILE VERSION DRIFT — check whether the separate mobile-optimized view has content or settings that differ from desktop in a way that could confuse indexing
5. THIRD-PARTY APP BLOAT — flag installed Wix apps likely adding unnecessary scripts

For each item, report pass/fail and whether it's fixable in Wix's own tools or a genuine platform ceiling.

Finish with what's worth fixing now versus what to accept as a Wix trade-off.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Note your Wix plan tier and current SEO setup
2. Paste in your site URL
3. Check the separate mobile editor view specifically if mobile traffic underperforms desktop

## Tips

- Wix's mobile editor is a genuinely separate view from desktop — content or settings can silently drift between them
- Wix SEO Wiz covers the basics but doesn't catch everything on this list; treat it as a starting point, not a finish line
- Some URL structure limits are real platform ceilings — know which before spending time trying to force a fix

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
