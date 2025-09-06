# 💳 decision_tree_svm_creditcard_fraud

## 📖 Overview
Compare **Decision Tree** and **SVM** models for detecting credit card fraud. Includes data preprocessing, model training, evaluation, and visualizations.

## 📊 Dataset
Credit card transactions labeled as fraudulent or non-fraudulent. Features are anonymized via PCA.  

**Source:** [Credit Card Fraud Detection Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%203/data/creditcard.csv)

## 🎓 Credit
Inspired by **IBM Machine Learning Professional Certificate** on Coursera:  
[IBM Developer Skills Network](https://www.coursera.org/learn/machine-learning-with-python)

## 🛠 Steps
1. Load dataset & visualize class distribution.
2. Feature correlation analysis.
3. Standardize & normalize features.
4. Train-test split & sample weighting.
5. Train models: Decision Tree (max_depth=4) & Linear SVM.
6. Evaluate with ROC-AUC, ROC curve, and Precision-Recall curve.

## 📈 Results
| Model        | ROC-AUC |
|--------------|---------|
| Decision Tree | 0.939  |
| SVM           | 0.986  |

## 🚀 How to Run
```bash
git clone https://github.com/<your-username>/decision_tree_svm_creditcard_fraud.git
cd decision_tree_svm_creditcard_fraud
pip install -r requirements.txt
# Open notebook or run script
