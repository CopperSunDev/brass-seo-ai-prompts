# Core Web Vitals Analysis

## Overview

Deep-dive into Core Web Vitals performance with specific optimization recommendations. Get actionable fixes for LCP, INP (replacing FID), and CLS issues.

## The Prompt

```text
Analyze the Core Web Vitals for [website URL] and provide optimization recommendations:

1. LARGEST CONTENTFUL PAINT (LCP)
   Target: < 2.5 seconds

   Analyze:
   - What is the LCP element? (hero image, heading, video)
   - Server response time (TTFB)
   - Render-blocking resources (CSS, JS)
   - Image optimization status
   - Lazy loading implementation

   Provide specific fixes for:
   - Preloading critical resources
   - Optimizing the LCP element
   - Reducing server response time
   - Eliminating render-blocking resources

2. INTERACTION TO NEXT PAINT (INP)
   Target: < 200ms

   Analyze:
   - JavaScript execution time
   - Third-party script impact
   - Event handler efficiency
   - Main thread blocking

   Provide specific fixes for:
   - Code splitting opportunities
   - Deferring non-critical JS
   - Web worker usage
   - Third-party script optimization

3. CUMULATIVE LAYOUT SHIFT (CLS)
   Target: < 0.1

   Analyze:
   - Images without dimensions
   - Ads/embeds without reserved space
   - Dynamically injected content
   - Web fonts causing FOIT/FOUT

   Provide specific fixes for:
   - Adding explicit dimensions
   - Reserving space for dynamic content
   - Font loading optimization
   - Animation best practices

For each metric, provide:
- Current estimated score
- Primary cause of poor performance
- Code examples for fixes
- Expected improvement after optimization

Include implementation priority (Quick Win, Medium Effort, Major Project).

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Replace `[website URL]` with the page you want to analyze
2. For best results, include PageSpeed Insights data in your prompt
3. Specify if you want mobile-only, desktop-only, or both analyses

## Expected Output

- Metric-by-metric analysis
- Root cause identification
- Code snippets for fixes
- Prioritized action plan

## Tips

- Test both mobile and desktop separately
- Focus on the worst-performing metric first
- Use Chrome DevTools Performance panel for detailed timing
- Re-test after each fix to measure improvement

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [Comprehensive Site Audit](./comprehensive-site-audit.md)
