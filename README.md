# Credit-Risk-Model
A machine learning model to estimate the probability of default (PD) for loan applicants. Includes data preprocessing, training (Logistic Regression, XGBoost), and evaluation using metrics like precision and ROC-AUC to support credit risk assessment.

# Credit Risk - Probability of Default Model

This project builds a machine learning model to estimate the **Probability of Default (PD)** for loan applicants. It aims to assist in **credit risk assessment** by using classification models and evaluating their performance using key metrics.

---

## Objective

Predict whether a borrower will default on a loan using historical loan data and classification techniques.

---

## Dataset

The dataset contains loan-related features such as:

- `loan_status` (target)
- Credit history indicators
- Financial ratios
- Other customer attributes

---

## Steps Followed

### 1. Data Loading & Exploration
- Loaded the dataset in a Jupyter Notebook
- Inspected data structure, types, and missing values

### 2. Data Preprocessing
- Handled missing data
- Converted categorical variables (if any)
- Normalized/standardized numerical features

### 3. Feature Engineering
- Selected relevant predictors for classification
- Optionally added new derived features

### 4. Model Training
- Applied **Logistic Regression**
- Applied **XGBoost Classifier**

### 5. Model Evaluation
- Compared models using metrics like:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC
- Calculated both **Precision Positive** and **Precision Negative** values

### 6. Interpretation
- Analyzed the best-performing model
- Assessed feature importance (for XGBoost)

---

## Results

- Achieved a PD prediction model with strong performance metrics
- XGBoost provided better results in terms of ROC-AUC and precision

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn (if visualization was included)

---

## File

- `Credit Risk-Probability of Default Model.ipynb`: Complete analysis notebook

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Model deployment using Flask/Streamlit

---
