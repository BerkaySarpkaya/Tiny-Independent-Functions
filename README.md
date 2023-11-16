# Tiny-Independent-Functions
This repo includes many independent functions. The purpose here is logging and sharing my tiny but time saving functions. Hope you like it :) 

## Folder Information

### Feature Engineering

- One-Hot-Encoder : Takes 2 inputs as data frame and columns list. Apply one hot encoding to the features with prefixed names and deletes the raw features.

- Scaler : Takes 3 inputs as data frame, columns list and scale type indicatior(s,n or rs). Apply the selected scaling method to the selected features. S,n and rs stand for Standardization, Normalization and Robust Scaling respectively.

### Modeling

- Reference Modeling : Takes 4 inputs as a data frame, target column, feature columns (as a list) and the regression type ("lr", "bc" or "mcc" for linear regression, binary classification and multiclass classification respectively. Data frames having no missing value and are encoded for categoric features will be essential to use this function.
