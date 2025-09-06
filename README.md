# 💳 decision_tree_svm_creditcard_fraud

## 🔍 Overview
This project compares **Decision Tree** 🌳 and **Support Vector Machine (SVM)** ⚡ models for detecting credit card fraud using the publicly available credit card dataset. It includes data preprocessing, model training, evaluation, and visualizations of model performance.

## 📊 Dataset
The dataset contains credit card transactions labeled as fraudulent or non-fraudulent. The features are numerical values resulting from a PCA transformation to protect sensitive information.

**Source:** [Credit Card Fraud Detection Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%203/data/creditcard.csv)

## 📝 Steps Performed
1. **Data Loading:** Read the dataset into a pandas DataFrame.
2. **Class Distribution Visualization:** 🥧 Pie chart to show the imbalance in the target variable.
3. **Feature Correlation:** 📊 Bar chart showing correlation of features with the target.
4. **Data Preprocessing:** Standardization and normalization of features.
5. **Train-Test Split:** Split data into training (70%) and testing (30%) sets.
6. **Sample Weighting:** Balanced weights for training to handle class imbalance.
7. **Model Training:**
   - Decision Tree Classifier 🌳 (max depth=4)
   - Linear SVM ⚡ (with balanced class weight)
8. **Evaluation:**
   - ROC-AUC score
   - ROC curve visualization 📈
   - Precision-Recall curve visualization 📉

## 📈 Results
| Model           | ROC-AUC |
|-----------------|---------|
| Decision Tree 🌳 | 0.939   |
| SVM ⚡           | 0.986   |

**Visualizations:**  
- ROC Curve Comparison 📈  
- Precision-Recall Curve Comparison 📉  

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/decision_tree_svm_creditcard_fraud.git
