# CreditWise Loan Approval Prediction

## Overview
CreditWise Loan Approval is a machine learning project that predicts whether a loan application should be approved based on applicant details such as income, credit history, and loan amount.

The goal of this project is to simulate a real-world credit risk assessment system using classification models.

## Tech Stack
- Language: Python  
- Libraries:  
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib / seaborn  

## Dataset
- The dataset (`loan_approval_data.csv`) is not included in this repository.
To run this project:
1. Download the dataset from: <add source link if available>
2. Place it in the root directory of the project
- Contains applicant information such as:
  - Income
  - Loan amount
  - Credit history
  - Gender, education, employment status

### Data Processing Steps
- Handling missing values using `SimpleImputer`
- Encoding categorical variables using `LabelEncoder` / `OneHotEncoder`
- Feature scaling using `StandardScaler`

## Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  

These models were chosen to compare:
- A simple, interpretable baseline (Logistic Regression)
- A distance-based model (KNN)

## Model Evaluation
- Accuracy used as primary metric
- Model performance compared between Logistic Regression and KNN

## Project Structure
creditwise-loan-approval/
│── credit_wise.ipynb
│── loan_approval_data.csv
│── README.md

## How to Run

1. Clone the repository
   - git clone <your-repo-link>
   - cd creditwise-loan-approval
2. Install dependencies
   - pip install pandas numpy scikit-learn matplotlib seaborn    
3. Run the notebook
   - jupyter notebook credit_wise.ipynb
   
