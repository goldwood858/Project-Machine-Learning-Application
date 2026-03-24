# Project-Machine-Learning-Application
#Credit Card Fraud Detection Binary classification
# Credit Card Fraud Detection

#This project uses machine learning to detect fraudulent transactions using the Credit Card Fraud Detection dataset from Kaggle.
#please download the dataset from this link 

#https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


## Models used
- Logistic Regression (with class_weight and SMOTE)
- Random Forest (with class_weight and SMOTE)
- XGBoost (with scale_pos_weight)

## Requirements
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, imbalanced-learn, xgboost, matplotlib, seaborn, joblib

## How to run
1. Place `creditcard.csv` in the same folder as the notebook.
2. Run all cells in `524_project.ipynb`.

## Results
The best model (tuned Random Forest + SMOTE) achieved:
- Accuracy: 0.9994
- Precision: 0.8367
- Recall: 0.8367
- F1-score: 0.8367
