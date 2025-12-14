# Model Evaluation – Metrics Analysis

HEAD
## Metrics Strategy
Due to class imbalance, accuracy is not an appropriate metric.

Priority metrics:
- Recall (minimize false negatives)
- Precision
- Confusion Matrix

Threshold tuning was applied to align model behavior with business risk.
=======
## Objective
Evaluate model performance using metrics aligned with credit risk management.

## Metrics Used
- Recall (primary metric)
- Precision
- F1-score
- Confusion Matrix

## Rationale
In credit risk, false negatives (undetected defaults) have a high financial cost.  
Therefore, recall is prioritized over accuracy.

## Interpretation
Model performance is analyzed in terms of risk reduction and decision impact.

9decbc00fa0ce6c2d2bb5b4dd938b87c7b204cc6
