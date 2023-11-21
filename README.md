# Tiny-Independent-Functions
This repo includes many independent functions. The purpose here is logging and sharing my tiny but time saving functions. 
Independent functions are categorized according to their phases of a regular data science project.

## Folder & Function Information

### Missing Value

- <font color="green">Advanced Missing Check</font> : Takes 1 input as df. Looks for the placeholders of nan values such as " ", "-", "--" "?" and etc.. There are three versions of the function turning:
  - Data Frame with Missing Values
  - Indexes of Rows Having Missing Value
  - Row Indexes with Column Names
 
- <font color="green">Replace With NAN</font> : Takes 1 input as df. Replace the nan-placeholders with np.nan values and returns the data frame.

- <font color="green">Missing Imputation</font> : Takes 3 inpust as data frame, strategy and features(columns). This function perform 4 missing value imputation strategy, which are "mean", "mode", "bfill", and "ffill", on selected features. 

### Feature Engineering

- <font color="green">One-Hot-Encoder</font> : Takes 2 inputs as data frame and columns list. Apply one hot encoding to the features with prefixed names and deletes the raw features.

- <font color="green">Scaler</font> : Takes 3 inputs as data frame, columns list and scale type indicatior(s,n or rs). Apply the selected scaling method to the selected features. S,n and rs stand for Standardization, Normalization and Robust Scaling respectively.

### Modeling

- <font color="green">Reference Modeling</font> : Takes 4 inputs as a data frame, target column, feature columns (as a list) and the regression type ("lr", "bc" or "mcc" for linear regression, binary classification and multiclass classification respectively. Data frames having no missing value and are encoded for categoric features will be essential to use this function.
