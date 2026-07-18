# 04 – Base rate neglect

**Category:** A – Estimation and forecasting

## Definition

Ignoring the background probability of an event and focusing only on case-specific information.

## Impact on decisions

Success odds for campaigns, launches, and tools get judged on their own story ("this one is different") while the historical hit rate of similar efforts is ignored. Signal-based systems get trusted without asking how rare the signal's target actually is.

## Detection signals

- No reference class mentioned when forecasting a new initiative
- "This one is different" without stating why the base rate does not apply
- Accuracy percentages quoted without the underlying population rate

## Countermeasures

- Start every forecast with: "What usually happens with efforts like this?"
- For any predictive score, calculate the false-positive volume given the real base rate
- Keep a log of past initiative outcomes to use as reference classes

## Marketing example

A lead-scoring model flags "high intent" visitors with 90% claimed accuracy. Only 2% of site visitors are actually in-market. Even at 90% accuracy, most flagged leads are false positives. Sales burns weeks calling them, hits a wall, and stops trusting marketing-sourced leads entirely.

## Related biases

- [03 – Representativeness heuristic](03-representativeness-heuristic.md)
- [08 – Insensitivity to sample size](08-insensitivity-to-sample-size.md)
