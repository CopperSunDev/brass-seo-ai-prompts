# Indexing Status Checker

## Overview

Diagnose why pages are not appearing in Google search results. Provide your URL, CMS details, and any GSC inspection data to get a structured diagnosis covering crawl issues, index issues, content issues, and a prioritized fix plan.

## The Prompt

```text
Diagnose why the following page(s) are not appearing in Google search results and provide specific fixes:

Website: [your website URL]
Problem Page(s): [URL(s) of pages not showing in Google]
CMS/Platform: [e.g., WordPress, Shopify, Next.js, custom]
How Long Ago Published: [e.g., 2 days, 2 weeks, 3 months]

Information I have (include what you know):
- robots.txt URL: [yoursite.com/robots.txt]
- Does the page have a noindex tag? [yes/no/unsure]
- Is the page in your XML sitemap? [yes/no/unsure]
- Does the page have internal links pointing to it? [yes/no/unsure]
- GSC URL Inspection result: [paste result if available, or "not checked"]
- Any recent site changes: [migration, redesign, domain change, etc.]

Please diagnose:

1. CRAWL ISSUES
   - Can Googlebot access the page? (robots.txt, server blocks, IP restrictions)
   - Are there redirect chains or loops?
   - Is the page reachable from internal links and sitemap?

2. INDEX ISSUES
   - Is a noindex tag or header present?
   - Is there a canonical tag pointing elsewhere?
   - Is the content too thin or duplicate of another page?
   - Are there crawl budget concerns for this site size?

3. CONTENT ISSUES
   - Does the page provide unique value?
   - Is the content substantially different from other pages on the site?
   - Does the page target a clear search intent?

4. FIX PLAN
   - For each issue found, provide the specific fix
   - Order fixes by priority (most likely cause first)
   - Include how to verify each fix worked
   - Estimate time for Google to re-index after fixes

If you cannot determine the cause from the information provided, list what additional information would help narrow it down.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Open Google Search Console and run the URL Inspection tool on each problem page
2. Copy the status and any details into the prompt's "GSC URL Inspection result" field
3. Fill in as much additional context as you can -- the more you provide, the better the diagnosis
4. Paste into ChatGPT, Claude, or any AI tool
5. Follow the prioritized fix plan, starting with the most likely cause

## Tips

- If you have multiple problem pages, list them all in a single prompt -- patterns across pages can reveal site-wide issues
- Include your `robots.txt` content if you suspect crawl blocking (visit `yoursite.com/robots.txt` and copy it)
- Mention any recent site changes -- migrations, CMS updates, and domain changes are common culprits
- For pages stuck in "Discovered -- currently not indexed," focus on adding internal links from your most important pages

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [Is This Page Even Indexed? How to Check (and Fix It)](https://brass-seo.com/blog/is-this-page-indexed-how-to-check)
- [Indexing Issue Diagnosis](./indexing-issue-diagnosis.md)
