# Comprehensive Site Audit

## Overview

Analyze any website for technical SEO issues with this comprehensive audit prompt. Get a prioritized list of problems with severity levels and specific recommendations.

## The Prompt

```text
Analyze [website URL] for technical SEO issues. Provide a comprehensive audit covering:

1. CRAWLABILITY
   - robots.txt configuration and potential issues
   - XML sitemap presence, validity, and completeness
   - Internal linking structure and orphan pages
   - JavaScript rendering requirements

2. INDEXATION
   - Meta robots tags usage
   - Canonical tag implementation
   - Duplicate content issues
   - Index bloat from parameter URLs

3. SITE SPEED
   - Core Web Vitals estimates (LCP, FID/INP, CLS)
   - Page load time factors
   - Image optimization opportunities
   - Render-blocking resources

4. MOBILE-FRIENDLINESS
   - Responsive design implementation
   - Mobile usability issues
   - Touch target sizes
   - Viewport configuration

5. HTTPS & SECURITY
   - SSL certificate status
   - Mixed content issues
   - HTTP to HTTPS redirects
   - Security headers

6. STRUCTURED DATA
   - Schema markup presence
   - Implementation errors
   - Missing opportunities

For each issue found, provide:
- Severity level (Critical, High, Medium, Low)
- Specific location/URL affected
- Recommended fix
- Expected impact on rankings

Prioritize issues by potential SEO impact.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Replace `[website URL]` with the site you want to audit
2. Paste the prompt into ChatGPT or Claude
3. For best results, also provide access to:
   - Google Search Console data
   - PageSpeed Insights results
   - Current robots.txt content

## Expected Output

A structured audit report with:
- Executive summary of site health
- Categorized issues by severity
- Specific, actionable recommendations
- Prioritized fix list

## Tips

- Run this audit quarterly for ongoing sites
- Combine with PageSpeed Insights data for more accurate speed analysis
- Use with Google Search Console coverage report for indexation issues
- For large sites, consider auditing section by section

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [Core Web Vitals Analysis Prompt](./core-web-vitals-analysis.md)
