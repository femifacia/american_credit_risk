# Summary of 5_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
- **learning_rate**: 0.05
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

2.2 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.545083 | nan          |
| auc       | 0.725227 | nan          |
| f1        | 0.547486 |   0.142372   |
| accuracy  | 0.654255 |   0.314361   |
| precision | 0.431818 |   0.314361   |
| recall    | 1        |   0.00350851 |
| mcc       | 0.338938 |   0.142372   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.545083 |  nan        |
| auc       | 0.725227 |  nan        |
| f1        | 0.539007 |    0.314361 |
| accuracy  | 0.654255 |    0.314361 |
| precision | 0.431818 |    0.314361 |
| recall    | 0.716981 |    0.314361 |
| mcc       | 0.31254  |    0.314361 |


## Confusion matrix (at threshold=0.314361)
|                |   Predicted as no |   Predicted as yes |
|:---------------|------------------:|-------------------:|
| Labeled as no  |                85 |                 50 |
| Labeled as yes |                15 |                 38 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
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
