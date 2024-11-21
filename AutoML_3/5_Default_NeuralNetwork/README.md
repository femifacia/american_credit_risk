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

2.1 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.654245 | nan           |
| auc       | 0.686513 | nan           |
| f1        | 0.540881 |   0.149536    |
| accuracy  | 0.62766  |   0.214545    |
| precision | 0.408602 |   0.214545    |
| recall    | 1        |   0.000998424 |
| mcc       | 0.3127   |   0.149536    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.654245 |  nan        |
| auc       | 0.686513 |  nan        |
| f1        | 0.520548 |    0.214545 |
| accuracy  | 0.62766  |    0.214545 |
| precision | 0.408602 |    0.214545 |
| recall    | 0.716981 |    0.214545 |
| mcc       | 0.27859  |    0.214545 |


## Confusion matrix (at threshold=0.214545)
|                |   Predicted as no |   Predicted as yes |
|:---------------|------------------:|-------------------:|
| Labeled as no  |                80 |                 55 |
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
