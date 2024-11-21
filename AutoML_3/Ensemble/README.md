# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                   |   Weight |
|:------------------------|---------:|
| 3_Linear                |        1 |
| 4_Default_Xgboost       |        4 |
| 5_Default_NeuralNetwork |        1 |

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.51086  | nan         |
| auc       | 0.745772 | nan         |
| f1        | 0.551351 |   0.140216  |
| accuracy  | 0.632979 |   0.261665  |
| precision | 0.409091 |   0.261665  |
| recall    | 1        |   0.0148627 |
| mcc       | 0.356409 |   0.140216  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.51086  |  nan        |
| auc       | 0.745772 |  nan        |
| f1        | 0.510638 |    0.261665 |
| accuracy  | 0.632979 |    0.261665 |
| precision | 0.409091 |    0.261665 |
| recall    | 0.679245 |    0.261665 |
| mcc       | 0.265155 |    0.261665 |


## Confusion matrix (at threshold=0.261665)
|                |   Predicted as no |   Predicted as yes |
|:---------------|------------------:|-------------------:|
| Labeled as no  |                83 |                 52 |
| Labeled as yes |                17 |                 36 |

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
