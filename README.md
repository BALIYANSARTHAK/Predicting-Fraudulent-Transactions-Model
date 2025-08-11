# Predicting Fraudulent Transactions Model

## Overview

This project focuses on building a machine learning model to detect fraudulent financial transactions. The dataset contains over 6.36 million rows and 10+ features, with a highly imbalanced distribution between legitimate and fraudulent cases.

## Workflow

1. **Data Cleaning**

   * Verified no missing values.
   * Handled outliers and addressed multicollinearity in balance-related features.

2. **Feature Engineering**

   * Created new features such as actual transferred amounts and transaction path.
   * Encoded categorical variables (`type`, `nameOrig`, `nameDest`).

3. **Modeling**

   * Models used: Decision Tree and Random Forest.
   * Random Forest chosen for better precision in fraud detection.

4. **Evaluation**

   * Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
   * Random Forest achieved \~99.96% accuracy, higher precision than Decision Tree.
   * AUC for both models was equal, indicating strong predictive ability.

5. **Key Factors Predicting Fraud**

   * Transaction type (`TRANSFER`, `CASH_OUT`).
   * Transaction amount.
   * Balance discrepancies between origin and destination accounts.

6. **Prevention Recommendations**

   * Use verified apps and secure internet connections (VPN).
   * Regular software and security updates.
   * Immediate reporting of suspicious activity to banks.

7. **Measuring Effectiveness**

   * Monitor fraud detection rates post-implementation.
   * Track false positives/negatives and customer feedback.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/BALIYANSARTHAK/Predicting-Fraudulent-Transactions-Model.git
   ```
2. Open `Accredian_Fraud_Detection.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure dataset is uploaded/mounted correctly.
4. Run all cells sequentially.


