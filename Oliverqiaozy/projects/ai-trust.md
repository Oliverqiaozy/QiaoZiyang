# Human–AI Trust Analysis

[← Profile](../README.md)

## Research question

How are confidence, response cues, decision stakes and interaction history associated with trust in AI outputs?

## Team analysis

The group examines how confidence, presentation cues, task context and interaction history relate to appropriate reliance on AI. It combines data cleaning, descriptive analysis, regression and predictive model comparisons, then translates the evidence into communication and interface-design implications.

## Two separate evidence streams

The project analyzes AI Trust Insights (1,000 records) and Human–AI Interaction, a synthetic dataset. In the latter, removing duplicate rows and records with missing targets leaves 9,800 observations. Invalid error-rate values are treated as missing.

The notebook keeps their targets and interpretations separate. It uses descriptive comparisons and regression for the first stream, and a common 80/20 train–test split with five-fold training cross-validation for predictive comparisons in the synthetic stream. Imputation and encoding are fitted within the training folds.

## Selected model comparison

On the synthetic target, the all-feature linear model has test RMSE **4.96** and R² **0.694**, compared with RMSE **5.30** and R² **0.650** for the specified random forest. This comparison describes the simulation and selected model specifications; it does not establish performance for real users.

## Decision insight

Higher trust alone is an incomplete product objective. The analysis examines whether confidence and presentation cues align with recorded accuracy and whether the decision context changes how reliance should be supported.

## Evidence

- [Saved model comparison CSV](../evidence/ai-trust-model-comparison.csv)
- Existing executed notebook, result tables, charts and report.
- Dataset provenance recorded in the project: [AI Trust Insights](https://www.kaggle.com/datasets/emanfatima2/ai-trust-insights) and [Human–AI Interaction](https://www.kaggle.com/datasets/eshaalnmalik/human-ai-interaction).

Dataset sampling and accuracy assessment are incompletely documented; rescaled trust ratings are not calibrated correctness probabilities.

**My contribution:** Act 1 — trust formation, including the analysis of confidence, response cues and decision context, with report and poster materials.

*Group coursework.*
