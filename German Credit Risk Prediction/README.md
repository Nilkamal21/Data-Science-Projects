# German Credit Risk Prediction

## Description
This project focuses on predicting credit risk (good or bad) based on financial and demographic data of customers. The goal is to identify patterns that determine creditworthiness and provide insights for better decision-making.

## Dataset
- **Source:** German Credit Dataset
- **Features:**
  - `Age`: Age of the customer
  - `Sex`: Gender of the customer
  - `Job`: Type of job (encoded as integers)
  - `Housing`: Type of housing (own/free/rent)
  - `Saving accounts`: Savings account balance
  - `Checking account`: Checking account balance
  - `Credit amount`: Loan amount requested
  - `Duration`: Loan duration in months
  - `Purpose`: Purpose of the loan

## Project Steps
1. **Data Cleaning and Preprocessing:**
   - Handled missing values by filling with the mode.
   - Encoded categorical variables using Label Encoding and One-Hot Encoding.
2. **Exploratory Data Analysis (EDA):**
   - Visualized numerical and categorical data distributions.
   - Analyzed correlations between features.
3. **Feature Engineering:**
   - Scaled numerical features using StandardScaler.
   - Defined the target variable (`Risk`) as 1 for bad credit risk and 0 for good credit risk.
4. **Model Building:**
   - Built a Logistic Regression model to predict credit risk.
   - Applied SMOTE to address class imbalance.
5. **Performance Evaluation:**
   - Evaluated the model using Accuracy, Confusion Matrix, and Classification Report.

## Results
- **Accuracy:** 94.5%
- **Confusion Matrix:**
    [[130 6] [ 5 59]]
- **Classification Report:**
          precision    recall  f1-score   support
       0       0.96      0.96      0.96       136
       1       0.91      0.92      0.91        64


## How to Run
1. Clone the repository to your local machine:
 ```bash
 git clone https://github.com/YourUsername/Data-Science-Portfolio.git

2. Navigate to the German Credit Risk Prediction folder:
cd Data-Science-Portfolio/German Credit Risk Prediction

3. Open the Jupyter Notebook:
jupyter notebook "German Credit Risk Prediction.ipynb"

4. Follow the steps in the notebook to reproduce the analysis.

## Tools and Libraries Used
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, scikit-learn

## Acknowledgments
This project is part of the Data Science Portfolio. The dataset used is publicly available and is commonly used for credit risk analysis tasks.