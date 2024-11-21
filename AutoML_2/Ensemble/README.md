# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 4_Default_Xgboost |        1 |

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.423275 | nan          |
| auc       | 0.862013 | nan          |
| f1        | 0.671233 |   0.179787   |
| accuracy  | 0.744681 |   0.179787   |
| precision | 0.545455 |   0.190002   |
| recall    | 1        |   0.00791558 |
| mcc       | 0.516689 |   0.179787   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.423275 |  nan        |
| auc       | 0.862013 |  nan        |
| f1        | 0.671233 |    0.179787 |
| accuracy  | 0.744681 |    0.179787 |
| precision | 0.544444 |    0.179787 |
| recall    | 0.875    |    0.179787 |
| mcc       | 0.516689 |    0.179787 |


## Confusion matrix (at threshold=0.179787)
|                |   Predicted as no |   Predicted as yes |
|:---------------|------------------:|-------------------:|
| Labeled as no  |                91 |                 41 |
| Labeled as yes |                 7 |                 49 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)