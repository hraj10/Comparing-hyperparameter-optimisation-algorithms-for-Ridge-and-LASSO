# Comparing hyperparameter optimisation algorithms for Ridge and LASSO

For a project, we compared different hyperparameter selection algorithms for the well-reknown regularisation techniques Ridge and LASSO regression. The objective was to find the model that generalises the best in terms of the RMSE. The original training data `data.csv` contains 500 observations with 26 variables, but was cleaned and upscaled to shape $493\times 377$. We considered the following models with associated hyperparameter optimisation techniques:

- Linear regression
- Ridge regression (k-fold CV)
- Ridge regression (one standard error rule)
- Ridge regression (forward feature selection approach)
- Ridge regression (backward feature selection approach)
- LASSO regression (k-fold CV)
- LASSO regression (one standard error rule)
- LASSO regression (forward feature selection approach)
- LASSO regression (backward feature selection approach)
- PCA

