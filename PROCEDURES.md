# Market Brief AI — operating procedures

Use these procedures as task-oriented reference. They describe public capabilities and verification steps, not private implementation. UI labels can vary by version.

## Procedure 1: Record a reproducible historical run

### Before you begin

Choose public data and an explicit study period.

### Steps

1. Record asset, interval, date range and data freshness.

2. Record model, settings and enabled context sources.

3. Run the baseline and retain the result.

4. Change only one setting for the comparison.

5. Inspect losses, assumptions and logs as well as final return.

### Expected result

Another run can be compared without hidden changes in inputs.

### If the result differs

Tuning and evaluation on the same period is not independent validation. No future return is established.

## Procedure 2: Inspect a model decision

### Before you begin

Choose a specific marked event in the historical chart.

### Steps

1. Locate the corresponding log entry where available.

2. Identify the information available before that decision.

3. Check the stated trigger and relevant prior bars.

4. Review costs and execution assumptions represented in the replay.

5. Record uncertainty or missing data alongside the interpretation.

### Expected result

The decision has an inspectable explanation rather than only an attractive equity curve.

### If the result differs

Do not infer causality from an overlay or treat a model state as a certain forecast. This is a software-research procedure, not investment advice.

## Report a repeatable problem

Record app/version, device/OS, selected mode, input conditions and the smallest failing step. Distinguish expected behavior from the observed result. Use synthetic examples and omit credentials or private records.

[Documentation index](README.md) · [Capabilities and limits](FEATURES_AND_LIMITS.md) · [Support and sources](PRIVACY_AND_SUPPORT.md)
