# Fraud Loan Detection

The goal of this project is to predict the loan risk of applicants using three datasets:

- **loan.csv** – loan details and applicant information  
- **payment.csv** – historical payment behaviors  
- **clarityUnderwriting.csv** – underwriting clarity and verification data  

The project is divided into two parts for better clarity and workflow separation.

---

## Part 1 : Data Preprocessing & Feature Engineering  
**File:** `1_preprocessing.ipynb` / `1_preprocessing.html`

This notebook covers:
- Dataset loading and initial exploration  
- Data cleaning and handling missing values  
- Feature transformation and encoding  
- Merging datasets  
- Features Enginering  
- Feature selection  

All preprocessing steps are explained in the notebook.

---

## Part 2 : Model Building & Evaluation  
**File:** `2_model_building.ipynb` / `2_model_building.html`

This notebook covers:
- 5 different models
- Train/validation/test split strategy  
- Model selection and baseline models  
- Training and hyperparameter tuning  
- Evaluation metrics and interpretation  
- Final model performance    

Explanations for modeling are included throughout the notebook.

---

## Final model
**File:** `best_xgb_model.pkl`

This is the final XGBoost model to predict the loan fraud risk, and perform classification.

## Merge dataset
**File:** `data\combined_df.csv`


This is the processed and merged dataset from the datasets given by this assessment.
