# 09 – Regression-to-the-mean neglect

**Category:** A – Estimation and forecasting

## Definition

Extreme results tend to be followed by more average ones for statistical reasons alone. This bias reads that natural reversion as the effect of whatever intervention happened in between.

## Impact on decisions

Fixes applied after unusually bad periods get credited for improvement that would have happened anyway. Programs get scaled based on phantom causation. Conversely, changes made after unusually good periods get blamed for the normal decline that follows.

## Detection signals

- Interventions launched immediately after extreme results
- "The fix worked" declared after a single period of improvement
- No control group or holdout behind the causal claim

## Countermeasures

- Use control groups or holdout regions before crediting an intervention
- Judge over multiple periods, not the one right after the change
- Before acting on an extreme result, ask how much is likely noise

## Marketing example

The worst-performing region gets a special recovery campaign after a bad quarter. Next quarter it improves 25%. The improvement matches what untreated regions did coming off bad quarters, but the campaign gets credited and rolled out globally at $500K.

## Related biases

- [08 – Insensitivity to sample size](08-insensitivity-to-sample-size.md)
- [15 – Narrative fallacy](15-narrative-fallacy.md)
- [45 – Outcome bias](45-outcome-bias.md)
