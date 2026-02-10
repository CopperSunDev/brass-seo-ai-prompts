# Indexing Issue Diagnosis

## Overview

Diagnose why specific pages are not appearing in Google search results. Covers crawl issues, index issues, content problems, and provides a prioritized fix plan with verification steps.

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

1. Replace the placeholders with your specific page details
2. Include as much information as you have (GSC data is especially helpful)
3. If you have multiple problem pages, list them all
4. Paste into ChatGPT, Claude, or any AI tool

## Expected Output

- Diagnosis of crawl, index, and content issues
- Prioritized list of likely causes
- Specific fixes for each issue found
- Verification steps and re-indexing timeline estimates

## Tips

- Check GSC URL Inspection first and paste the result for the most accurate diagnosis
- Include your robots.txt content if you suspect crawl blocking
- Mention any recent site changes (migrations are a common cause)
- For new sites, give Google at least 1-2 weeks before investigating

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [Pages Not Showing on Google? Here's Why](https://brass-seo.com/blog/pages-not-showing-on-google-fixes)
- [Firewall Bot Allowlisting](./firewall-bot-allowlisting.md)
