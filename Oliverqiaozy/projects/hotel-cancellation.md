# Hotel Cancellation & Revenue Risk

[← Profile](../README.md)

## Business question

How can booking-level cancellation risk support hotel revenue-management decisions while controlling unnecessary interventions?

## Team project

The group connects booking-data preparation and exploratory analysis with cancellation prediction, model comparison, revenue-risk interpretation and an illustrative capacity analysis. The goal is to turn booking-level probabilities into management decisions.

## Model comparison

The project compares Logistic Regression, Random Forest and XGBoost. It connects model evaluation with cancellation-related revenue exposure and false-alarm bookings, so the choice of model reflects an operating trade-off as well as predictive performance.

The recorded R results are:

| Model | Accuracy | Precision | Recall | AUC | False alarms |
| :--- | ---: | ---: | ---: | ---: | ---: |
| Logistic Regression | 81.04% | 80.84% | 64.02% | 0.8897 | 2,012 |
| XGBoost | 87.41% | 85.39% | 79.67% | 0.9464 | 1,807 |
| Random Forest | 87.39% | 86.76% | 77.86% | 0.9441 | 1,575 |

The project record identifies a test set of 35,761 bookings. Values above are transcribed from the saved R evaluation, rather than rerun for this portfolio.

## Decision insight

Random Forest produced **232 fewer false alarms** than XGBoost, with a lower recall and slightly lower AUC. XGBoost flagged 78.9% of the recorded cancellation-related revenue exposure; Random Forest flagged 75.9%. The preferred model depends on the relative costs of missed cancellations and unnecessary interventions.

Flagged exposure is a retrospective analysis metric. It is not demonstrated recovered revenue. The capacity work in the wider project is assumption-based; it does not establish an optimal overselling policy or a deployed hotel system.

## Evidence

- [Model comparison CSV](../evidence/hotel-model-comparison.csv)
- [Business impact CSV](../evidence/hotel-business-impact.csv)
- Underlying materials: hotel cancellation analysis notebooks, R evaluation outputs, group report and presentation.

**My contribution:** Section 3 — model overview, model comparison and interpretation of operational trade-offs.

*Group coursework.*
