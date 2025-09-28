## Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using a Logistic Regression model.

### Dataset

The dataset used is `creditcard.csv`. It contains credit card transactions made by European cardholders in September 2013. The dataset is highly unbalanced, with fraud cases accounting for a small fraction of all transactions.

### Features

The features in the dataset are:
- `Time`: Number of seconds elapsed between this transaction and the first transaction in the dataset.
- `Amount`: Transaction amount.
- `V1` to `V28`: Anonymized features obtained through PCA transformation.
- `Class`: The target variable, where `1` represents a fraudulent transaction and `0` otherwise.

### Libraries Used

- `numpy`
- `pandas`
- `scikit-learn`
