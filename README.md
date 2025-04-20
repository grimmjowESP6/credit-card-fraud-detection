# Credit Card Fraud Detection

## Objective
Build a machine learning model to detect fraudulent credit card transactions with high accuracy while minimizing false positives.

## Dataset
Dataset used: [Credit Card Fraud Detection - Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Time and Amount
- Anonymized PCA features (V1 to V28)
- Class label (0 = normal, 1 = fraud)

**Note:** The dataset is not included in this repository. To use this project:
1. Download the CSV from Kaggle
2. Place `creditcard.csv` in the `data/` folder of this project.


## Key Steps
- Handle class imbalance using SMOTE
- Feature engineering
- Train classification models: Logistic Regression, Random Forest, XGBoost
- Evaluate models using Accuracy, Precision, Recall, F1 Score, and ROC AUC

## Setup
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
```

## How to Run
Run `notebooks/main.ipynb` for data loading, preprocessing, and to train and evaluate models

## Results

For logistic regression:
- ROC AUC Score: 0.9623115577889447
- Average Precision Score (PR-AUC): 0.021739130434782608

For Random Forest:
- ROC AUC Score: 0.9958123953098827
- Average Precision Score (PR-AUC): 0.14285714285714285

For XGBoost:
- ROC AUC Score: 0.9472361809045227
- Average Precision Score (PR-AUC): 0.015625

## Author
grimmjowESP6
