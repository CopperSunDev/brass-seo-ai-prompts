# Contributing to Brass-SEO AI Prompts

Thank you for your interest in contributing to Brass-SEO AI Prompts!

## How to Contribute

### Adding New Prompts

1. **Create both formats** - Every prompt needs both Markdown and YAML versions
2. **Follow the structure** - Use existing prompts as templates
3. **Test your prompt** - Verify it works with ChatGPT or Claude before submitting

### File Locations

- Markdown: `/prompts/markdown/[category]/[prompt-name].md`
- YAML: `/prompts/yaml/[category]/[prompt-name].yml`

### Markdown Format

```markdown
# [Prompt Name]

## Overview

Brief description of what this prompt does.

## The Prompt

\`\`\`text
[Your prompt text here]

Replace [placeholders] with your specific information.

---
Prompt by Brass-SEO (brass-seo.com)
---
\`\`\`

## How to Use

1. Step one
2. Step two
3. Step three

## Expected Output

Description of what the AI should return.

## Tips

- Helpful tip 1
- Helpful tip 2
```

### YAML Format

```yaml
metadata:
  id: "prompt-name"
  title: "Prompt Title"
  category: "category-name"
  version: "1.0"
  created: "2026-01-14"

description: "Brief description of what this prompt does."

prompt_text: |
  Your prompt text here.

  Replace [placeholders] with your specific information.

  ---
  Prompt by Brass-SEO (brass-seo.com)
  ---

usage:
  - "Step one"
  - "Step two"

placeholders:
  - name: "[placeholder]"
    description: "What to replace it with"

resources:
  website: "https://brass-seo.com"
  guide: "https://brass-seo.com/ai-prompts-guide-for-seo"
```

## Pull Request Process

1. Fork the repository
2. Create a feature branch (`git checkout -b add-new-prompt`)
3. Add your prompt in both formats
4. Test your prompt with an AI tool
5. Submit a pull request with a clear description

## Questions?

Open an issue or contact us at [brass-seo.com](https://brass-seo.com).
