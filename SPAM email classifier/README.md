# SPAM email classifier

This project classifies emails as spam or not spam using a Logistic Regression model.

### Dataset

The dataset used is `email_data.csv`. It contains a collection of emails labeled as spam or ham (not spam).

### Features

The primary feature used is the email's message content. This text data is converted into numerical features using the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer.

### Libraries Used

- `numpy`
- `pandas`
- `scikit-learn`
