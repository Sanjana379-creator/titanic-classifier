# Titanic Survival Classifier

A machine learning project predicting Titanic passenger survival using Random Forest.

## Results
- Validation Accuracy: 82%
- Cross-validation Mean: 80.8% (+/- 0.035)
- Best Parameters: max_depth=5, n_estimators=100

## Key Findings
- Sex was the strongest predictor (females 50% survival, males 12%)
- Fare and Age were next most important features
- Pclass confirmed wealth correlation with survival

## Tools Used
- Python 3.12, scikit-learn, pandas, numpy, matplotlib, seaborn

## How to Run
1. pip install -r requirements.txt
2. jupyter notebook
3. Open 01_eda.ipynb and run all cells

## Dataset
Official Titanic dataset from Kaggle (kaggle.com/c/titanic)
