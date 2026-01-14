# Brass-SEO AI Prompts

**4 Professional AI Prompts for SEO Tasks**

Ready-to-use prompts for technical SEO audits, content optimization, and more. Copy, paste, and customize for your SEO workflow.

## Quick Start

1. Browse prompts in [`/prompts/markdown/`](./prompts/markdown/)
2. Copy the prompt text
3. Paste into ChatGPT, Claude, or your preferred AI
4. Replace `[placeholders]` with your specific information

## Prompt Categories

### Technical SEO (2 prompts)

Audit site performance, crawlability, and technical issues.

- **[Comprehensive Site Audit](./prompts/markdown/technical-seo/comprehensive-site-audit.md)** - Full technical SEO analysis with prioritized recommendations
- **[Core Web Vitals Analysis](./prompts/markdown/technical-seo/core-web-vitals-analysis.md)** - LCP, FID/INP, and CLS optimization guidance

### Content Optimization (2 prompts)

Improve on-page SEO and content quality.

- **[Title & Meta Description Generator](./prompts/markdown/content-optimization/title-meta-description-generator.md)** - Create SEO-optimized titles and descriptions
- **[Content Gap Analysis](./prompts/markdown/content-optimization/content-gap-analysis.md)** - Identify missing content opportunities

## Dual Format Support

Every prompt is available in two formats:

- **Markdown** (`/prompts/markdown/`) - Human-readable with full documentation
- **YAML** (`/prompts/yaml/`) - Machine-readable for automation and API integration

## Usage Examples

### With ChatGPT/Claude

```
1. Open the markdown file for your desired prompt
2. Copy the entire prompt text
3. Paste into your AI chat
4. Replace [website URL], [keyword], etc. with your specifics
5. Review and refine the AI's output
```

### Programmatic Access

```python
import yaml

with open('prompts/yaml/technical-seo/comprehensive-site-audit.yml') as f:
    prompt = yaml.safe_load(f)

print(prompt['prompt_text'])
```

## About Brass-SEO

[Brass-SEO](https://brass-seo.com) provides AI-powered SEO analysis tools. Connect your Google Search Console and GA4 to get actionable insights about your website's performance.

## License

MIT License - Use these prompts freely in your projects.

## Contributing

We welcome contributions! See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

---

**Created by [Brass-SEO](https://brass-seo.com)** | [Full Prompt Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
