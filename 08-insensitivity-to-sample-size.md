# 08 – Insensitivity to sample size

**Category:** A – Estimation and forecasting

## Definition

Trusting conclusions drawn from small samples as if they carried the reliability of large ones.

## Impact on decisions

A/B tests get called early, campaigns get killed or scaled on a few days of data, and "winning" variants that were statistical noise become company standards.

## Detection signals

- Test decisions made with fewer than a few hundred conversions per variant
- Results checked daily and stopped as soon as one variant leads
- Percentage differences quoted without absolute numbers behind them

## Countermeasures

- Set required sample size and test duration before launching; do not peek-and-stop
- Report absolute numbers next to percentages
- Repeat important tests before rolling out globally

## Marketing example

Subject line B "wins" with a 22% vs 19% open rate on 400 sends – roughly 88 opens vs 76. The team rewrites the entire nurture program around B's style. At full volume the difference vanishes. A month of rework produced nothing because the original result was noise.

## Related biases

- [04 – Base rate neglect](04-base-rate-neglect.md)
- [09 – Regression-to-the-mean neglect](09-regression-to-the-mean-neglect.md)
- [16 – Illusory correlation](16-illusory-correlation.md)
