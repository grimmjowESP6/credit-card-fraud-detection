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
- Exploratory Data Analysis (EDA)
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
Run `notebooks/main.ipynb` for data loading, EDA, preprocessing, and to train and evaluate models

## Results
- Best model: XGBoost
- Accuracy: 99.9%
- Precision: XX.XX%
- Recall: XX.XX%
- F1 Score: XX.XX%

## Author
grimmjowESP6