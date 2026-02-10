# Brass-SEO AI Prompts

🎯 **10 Professional AI Prompts for SEO Tasks**

Ready-to-use prompts for technical SEO audits, content optimization, and more. Copy, paste, and customize for your SEO workflow.

## 🚀 Quick Start

1. **Choose Your Format**: Use `prompts/markdown/` for reading or `prompts/yaml/` for automation
2. **Select a Prompt**: Browse categories below or see the [complete guide](https://brass-seo.com/ai-prompts-guide-for-seo)
3. **Copy & Customize**: Replace `[placeholders]` with your specific information
4. **Run in Any AI**: Works with ChatGPT, Claude, Gemini, and all AI chat systems

## 📋 Prompt Categories

### 🔧 Technical SEO (2 prompts)

Audit site performance, crawlability, and technical issues.

- **[Comprehensive Site Audit](./prompts/markdown/technical-seo/comprehensive-site-audit.md)** - Full technical SEO analysis covering crawlability, indexation, speed, mobile, security, and structured data
- **[Core Web Vitals Analysis](./prompts/markdown/technical-seo/core-web-vitals-analysis.md)** - Deep-dive into LCP, INP, and CLS with specific optimization recommendations

[📖 View Details](https://brass-seo.com/blog/technical-seo-ai-prompts) | [📁 Browse Files](./prompts/markdown/technical-seo/)

### 📝 Content Optimization (3 prompts)

Improve on-page SEO and content quality.

- **[Title & Meta Description Generator](./prompts/markdown/content-optimization/title-meta-description-generator.md)** - Create SEO-optimized titles and descriptions with multiple variations and character counts
- **[Content Gap Analysis](./prompts/markdown/content-optimization/content-gap-analysis.md)** - Identify missing content opportunities by analyzing competitor coverage
- **[Keyword Opportunity Finder](./prompts/markdown/content-optimization/keyword-opportunity-finder.md)** - Find quick wins and strategic keyword targets from your GSC data

[📖 View Details](https://brass-seo.com/blog/content-optimization-ai-prompts) | [📁 Browse Files](./prompts/markdown/content-optimization/)

### 🤖 AI Tools (2 prompts)

Evaluate and optimize AI model usage for production applications.

- **[Model Evaluation Framework](./prompts/markdown/ai-tools/model-evaluation-framework.md)** - Design rigorous testing frameworks for selecting AI models with test queries, scoring rubrics, and comparison frameworks
- **[AI Cost Calculator](./prompts/markdown/ai-tools/ai-cost-calculator.md)** - Calculate and compare AI model costs with break-even analysis and optimization recommendations

[📖 View Details](https://brass-seo.com/blog/ai-model-evaluation-production-apps) | [📁 Browse Files](./prompts/markdown/ai-tools/)

### 📊 SEO Analysis (1 prompt)

Analyze your traffic data and turn numbers into actionable insights.

- **[GA4 Traffic Analysis](./prompts/markdown/seo-analysis/ga4-traffic-analysis.md)** - Analyze GA4 data for traffic health, engagement quality, and opportunities

[📖 View Details](https://brass-seo.com/blog/how-to-read-your-ga4-traffic-report) | [📁 Browse Files](./prompts/markdown/seo-analysis/)

### 🛡️ Troubleshooting (2 prompts)

Solve common setup and configuration issues.

- **[Firewall Bot Allowlisting](./prompts/markdown/troubleshooting/firewall-bot-allowlisting.md)** - Get step-by-step instructions to allow an SEO bot through your firewall or WAF
- **[Indexing Issue Diagnosis](./prompts/markdown/troubleshooting/indexing-issue-diagnosis.md)** - Diagnose and fix pages not appearing in Google search results

[📖 View Details](https://brass-seo.com/allow-bot) | [📁 Browse Files](./prompts/markdown/troubleshooting/)

## 🔧 Using YAML Formats

For automation and integration, each prompt is available in structured YAML format:

```yaml
# Example usage
metadata:
  title: "Comprehensive Site Audit"
  category: "technical-seo"
  version: "1.0"

prompt_text: |
  Analyze [website URL] for technical SEO issues...

resources:
  detailed_guide: "https://brass-seo.com/blog/technical-seo-ai-prompts"
```

```python
import yaml

with open('prompts/yaml/technical-seo/comprehensive-site-audit.yml') as f:
    prompt = yaml.safe_load(f)

print(prompt['prompt_text'])
```

## 🎯 Best Practices

### For Best Results:
1. **Provide context** - Include PageSpeed Insights data, GSC reports, or competitor URLs when relevant
2. **Be specific** - Replace all placeholders with actual values, not generic examples
3. **Combine prompts** - Use multiple prompts for comprehensive analysis (audit first, then deep-dive into specific issues)
4. **Iterate and refine** - Adjust prompts based on your specific industry and site type

### Recommended Workflow:
1. **Run Site Audit** first to identify major issues
2. **Deep-dive** into specific problems (Core Web Vitals, content gaps, etc.)
3. **Generate optimizations** (titles, meta descriptions) based on findings
4. **Prioritize fixes** by impact and effort
5. **Re-audit** after implementing changes

## 🔗 Resources

- **🎯 Complete Guide**: [Brass-SEO AI Prompts Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- **📊 SEO Analysis**: [Brass-SEO Dashboard](https://brass-seo.com/dashboard)
- **📚 Blog Posts**: Detailed guides for each prompt category

## 📄 License

MIT License - Feel free to use, modify, and distribute these prompts for any purpose.

---

**Created by [Brass-SEO](https://brass-seo.com)** - AI-powered SEO analysis for small businesses.
