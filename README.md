# Credit Risk Analysis with Machine Learning

This project builds a machine learning pipeline to assess the creditworthiness of customers based on historical financial behavior. It identifies high-risk customers and helps financial institutions reduce default rates.

---

##  Objective

- Predict the likelihood of a customer defaulting on their loan within the next 2 years
- Use financial and behavioral features to build a reliable classification model
- Handle class imbalance using SMOTE
- Evaluate performance using ROC-AUC, classification report, and confusion matrix
- Identify the most important features influencing credit risk

---

## Dataset

- **Name:** Give Me Some Credit Dataset
- **Source:** Kaggle (https://www.kaggle.com/c/GiveMeSomeCredit)
- **Features:**
  - RevolvingUtilizationOfUnsecuredLines
  - DebtRatio
  - MonthlyIncome
  - NumberOfOpenCreditLinesAndLoans
  - NumberOfTimes90DaysLate
  - …and more

---

##  Workflow

1. **Data Preprocessing**
   - Handling missing values (MonthlyIncome, NumberOfDependents)
   - Feature scaling
   - Label extraction

2. **Imbalance Handling**
   - Applied SMOTE to balance default vs. non-default classes

3. **Modeling**
   - Random Forest Classifier
   - Hyperparameter tuning using GridSearchCV

4. **Evaluation**
   - ROC-AUC Score
   - Classification Report (Precision, Recall, F1)
   - Confusion Matrix
