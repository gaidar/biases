# 17 – Automation bias

**Category:** B – Information processing

## Definition

Over-trusting outputs from tools, dashboards, models, and AI systems, and under-checking them relative to human sources.

## Impact on decisions

Wrong numbers travel far because "the dashboard says so." AI-generated content ships unverified. Model recommendations override ground truth from the field.

## Detection signals

- "The model says" or "the tool shows" ends the discussion
- No manual spot checks on automated outputs
- Nobody can explain how the number is calculated

## Countermeasures

- Spot-check automated outputs against source data on a fixed schedule
- Require human review for anything high-stakes or externally published
- Document each tool's known failure modes and share them with users
- Treat AI output as a draft from a fast junior colleague, not a verdict

## Marketing example

An AI content tool produces a competitor comparison including a pricing table. Nobody verifies it; the data is eight months stale. The page ships, the competitor publicly corrects it on LinkedIn, and the correction post outperforms the original page.

## Related biases

- [18 – Information bias](18-information-bias.md)
- [33 – Authority bias](33-authority-bias.md)
