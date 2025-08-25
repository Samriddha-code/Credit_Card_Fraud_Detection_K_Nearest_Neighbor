Credit Card Fraud Detection using K-Nearest Neighbors (KNN)
📌 Project Overview
This project applies the K-Nearest Neighbors (KNN) algorithm to detect fraudulent credit card transactions.
The dataset is highly imbalanced, as fraudulent transactions make up only a small fraction of the total.

The aim is to build a baseline machine learning pipeline for fraud detection while addressing the challenges of working with imbalanced datasets.

📂 Key Steps
Data Loading & Exploration

Load and inspect the dataset.

Understand the class distribution (fraud vs non-fraud).

Data Preprocessing

Apply StandardScaler for feature scaling.

Split dataset into training and testing sets.

Model Training

Train a KNN Classifier on the training dataset.

Experiment with different values of n_neighbors.

Model Evaluation

Evaluate performance using:

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

Focus on precision, recall, and F1-score instead of accuracy due to imbalance.

📊 Why Not Just Accuracy?
In fraud detection, accuracy can be misleading because the dataset is dominated by legitimate transactions.
A model predicting "not fraud" every time could achieve >99% accuracy but fail to detect actual fraud cases.
Therefore, this project emphasizes Precision, Recall, and F1-score as core evaluation metrics.

🛠️ Tools & Libraries Used
Python 3.x

Scikit-learn for KNN and evaluation metrics

Pandas & NumPy for data handling

Matplotlib & Seaborn for visualization
