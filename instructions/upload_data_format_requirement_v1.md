# Upload data format for this APP

- All files you uploaded are in the form of `csv` files.

- The variable names and quantities in `xx_training.csv` and `xx_external_validation.csv` need to be exactly the same, while the sample sizes can be different. When there is no external validation set, the training set can be used as the external validation set. The `xx_prediction.csv` file should include all predictors used in the modeling process.

- `variable_type.csv` provides information on all variables uploaded in the training set. The variable names in this file must exactly match those in the example file. `factor_variable` column refers to categorical variables, while `numeric_variable` column refers to continuous variables. The APP will automatically convert the uploaded data types according `factor_variable` and `numeric_variable` . `covariates` are the independent variables that one wants to include in the model, and `dependent_variable` is the outcome variable of the model.
