# Tiny-Independent-Functions
This repo includes many independent functions. The purpose here is logging and sharing my tiny but time saving functions. 
Independent functions are categorized according to their phases of a regular data science project.

## Folder & Function Information

### Missing Value

- Advanced Missing Check : Takes 1 input as df. Looks for the placeholders of nan values such as " ", "-", "--" "?" and etc.. There are three versions of the function turning:
  - Data Frame with Missing Values
  - Indexes of Rows Having Missing Value
  - Row Indexes with Column Names
 
- Replace With NAN : Takes 1 input as df. Replace the nan-placeholders with np.nan values and returns the data frame.

- Missing Imputation : Takes 3 inpust as data frame, strategy and features(columns). This function perform 4 missing value imputation strategy, which are "mean", "mode", "bfill", and "ffill", on selected features. 

### Feature Engineering

- One-Hot-Encoder : Takes 2 inputs as data frame and columns list. Apply one hot encoding to the features with prefixed names and deletes the raw features.

- Scaler : Takes 3 inputs as data frame, columns list and scale type indicatior(s,n or rs). Apply the selected scaling method to the selected features. S,n and rs stand for Standardization, Normalization and Robust Scaling respectively.

### Modeling

- Reference Modeling : Takes 4 inputs as a data frame, target column, feature columns (as a list) and the regression type ("lr", "bc" or "mcc" for linear regression, binary classification and multiclass classification respectively. Data frames having no missing value and are encoded for categoric features will be essential to use this function.
