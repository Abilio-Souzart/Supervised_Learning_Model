# Credit Risk Prediction Model

## Project Overview

This project develops a **machine learning model for credit risk classification**, aiming to predict whether a loan application will be **approved (1)** or **rejected (0)** based on applicant characteristics.

The motivation stems from the importance of accurate credit evaluation in financial institutions, where misclassification can lead to:

* Financial losses due to default
* Increased portfolio risk
* Inefficient credit allocation

---

## Economic Context

Credit approval decisions are closely related to fundamental concepts in financial economics:

* **Asymmetric Information**
* **Adverse Selection**
* **Credit Risk Management**

The model attempts to approximate how financial institutions evaluate borrower profiles using observable characteristics.

---

## Dataset

* Source: Kaggle (Loan Approval Dataset)
* Type: Synthetic dataset
* Observations: ~1,000 loan applicants

### Features include:

* Credit score
* Annual income
* Employment status
* Number of dependents

Each row represents a single loan application.

---

## Methodology

The project follows a standard machine learning pipeline:

1. **Data Inspection**

   * Structure, missing values, data types

2. **Data Cleaning**

   * Duplicate checks
   * Validation of identifiers

3. **Exploratory Data Analysis (EDA)**

   * Distribution analysis
   * Relationship between variables and target

4. **Modeling**

   * Decision Tree Classifier (Scikit-learn)

5. **Evaluation**

   * Accuracy
   * ROC-AUC Score
   * Confusion Matrix

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn / Matplotlib
* Graphviz

---

## Author

**Abilio Trindade Souzart**
Fundação Getulio Vargas (FGV)
Economics & Data Science

---

## Final Remark

This project combines **machine learning techniques with economic reasoning**, aiming to bridge predictive modeling and financial decision-making.
