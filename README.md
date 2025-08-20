# Credit Card Fraud Detection with K-Nearest Neighbors

This project uses the K-Nearest Neighbors (KNN) algorithm to detect fraudulent credit card transactions. The dataset contains anonymized features, and the target variable indicates whether a transaction is fraud or not. The dataset is highly imbalanced, with few fraud cases.

## Key Steps

- Data loading and exploration
- Feature scaling using StandardScaler
- Train-test splitting
- Training a KNN classifier
- Model evaluation with confusion matrix and classification report

## Important Notes

- Due to class imbalance, precision, recall, and F1-score are better indicators of model performance than accuracy.
- This is a basic project demonstrating core machine learning workflow with Python.

## Possible Improvements

- Use oversampling methods like SMOTE to handle imbalance
- Hyperparameter tuning for KNN
- Evaluate other classifiers and perform cross-validation
- Visualize ROC and Precision-Recall curves

