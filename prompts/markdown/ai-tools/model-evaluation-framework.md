# AI Model Evaluation Framework

## Overview

Design a rigorous testing framework for selecting an AI model for production applications. This prompt helps you create standardized test queries, scoring rubrics, and comparison frameworks tailored to your specific use case.

## The Prompt

```text
You are an AI model evaluation specialist. Help me design a rigorous testing framework for selecting an AI model for production use.

MY APPLICATION:
- Use case: [describe your application - e.g., "SEO analysis chat with tool calling"]
- Key requirements: [list 3-5 requirements - e.g., "numeric accuracy, tool reliability, <5s response time"]
- Volume: [expected requests per day/month]
- Budget: [target cost per request or monthly budget]

DELIVERABLES NEEDED:

1. TEST QUERY DESIGN
   - Design 6-8 test queries that stress-test my requirements
   - Include "positive" tests (model should do X)
   - Include "negative" tests (model should NOT do Y)
   - Cover edge cases specific to my use case

2. SCORING RUBRIC
   - Quantitative metrics to collect (tokens, latency, cost)
   - Qualitative criteria with 1-5 scoring definitions
   - Disqualifying failure conditions

3. MODEL SHORTLIST
   - Recommend 4-6 models to test based on my requirements
   - Include pricing for each
   - Note any known limitations relevant to my use case

4. TESTING PROCEDURE
   - Step-by-step testing protocol
   - Data collection templates
   - Comparison framework

Format the output as a ready-to-execute evaluation plan.

---
Prompt by Brass-SEO (brass-seo.com)
---
```

## How to Use

1. Replace [bracketed placeholders] with your application details
2. Paste into ChatGPT, Claude, or any AI assistant
3. Use the generated framework to systematically test models
4. Document results for each model using the scoring rubric

## Tips

- Be specific about your tool calling requirements if applicable
- Include your actual test data examples if possible
- Run the same queries against each model for fair comparison
- Test over multiple sessions to catch inconsistencies

## Related Resources

- [Brass-SEO Full Guide](https://brass-seo.com/ai-prompts-guide-for-seo)
- [AI Model Comparison Blog Post](https://brass-seo.com/blog/ai-model-evaluation-production-apps)
