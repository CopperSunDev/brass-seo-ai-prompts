# Firewall Bot Allowlisting

## Overview

Get step-by-step instructions to create a firewall rule that allows a specific bot (like an SEO crawler) through your website's WAF or bot protection. Works with any firewall provider.

## The Prompt

```text
I need to allow a specific SEO bot through my website's firewall.

Bot details:
- Name: Brass-SEO
- User-Agent: Brass-SEO/1.0 (+https://brass-seo.com/bot)
- Purpose: SEO analysis tool that I've authorized to crawl my site
- More info: https://brass-seo.com/bot

My website uses [REPLACE WITH YOUR FIREWALL/HOST - e.g., Cloudflare, Vercel, Sucuri, Wordfence, AWS WAF, Azure Front Door].

Please look up the latest documentation for my firewall provider and give me step-by-step instructions to create a rule that allows requests from this bot (matching the User-Agent string above) to bypass bot protection and challenge pages.

Walk me through one step at a time. After each step, wait for me to confirm before moving on — I may have questions or see something different on my screen.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Replace the firewall/host placeholder with your actual provider (e.g., Cloudflare, Vercel, AWS WAF)
2. Paste the prompt into ChatGPT, Claude, or any AI assistant
3. Follow the step-by-step instructions the AI provides

## Expected Output

A walkthrough with:
- Where to find the firewall settings in your dashboard
- Exact values to enter for the rule
- How to test that the rule is working

## Tips

- If you don't know which firewall you have, mention your hosting provider and ask the AI to identify it
- You can add your own bot details by replacing the Bot details section
- Test after creating the rule by checking if the bot can access your site

## Related Resources

- [Brass-SEO Firewall Guide](https://brass-seo.com/allow-bot)
- [About Brass-SEO Bot](https://brass-seo.com/bot)
- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
