# Summary of 38_RandomForest_GoldenFeatures_Stacked

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: squared_error
- **max_features**: 0.8
- **min_samples_split**: 40
- **max_depth**: 3
- **eval_metric_name**: rmse
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 4
 - **shuffle**: False

## Optimized metric
rmse

## Training time

11.0 seconds

### Metric details:
| Metric   |       Score |
|:---------|------------:|
| MAE      | 0.000804646 |
| MSE      | 2.39529e-05 |
| RMSE     | 0.00489417  |
| R2       | 0.312704    |
| MAPE     | 2.25806e+11 |



## Learning curves
![Learning curves](learning_curves.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



[<< Go back](../README.md)
