# Customer Churn Prediction - Telecom Industry
Predicting customer churn using machine learning techniques and telecom service data.

## Project Objectives
- Analyze patterns and behaviors associated with customer churn
- Build predictive models using classification algorithms
- Evaluate model performance using accuracy, recall, and F1-score
- Provide business recommendations based on insights

Dataset Overview
- Source: [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Records: 7,043 customers
- Target: `Churn` (Yes/No)

## Methodology

1. **Data Preparation**  
   - Handling missing values, encoding categorical variables, scaling numerical features

2. **Exploratory Data Analysis (EDA)**  
   - Examined churn rates by contract type, tenure, payment method, and services

3. **Modeling**  
   - Logistic Regression  
   - Random Forest Classifier  
   - Hyperparameter tuning using GridSearchCV

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion matrix and feature importance analysis

## Results Summary

| Model              | Accuracy | Recall (Churn) | F1 Score |
|-------------------|----------|----------------|----------|
| Logistic Regression | 80.4%   | 57%            | 0.61     |
| Random Forest       | 76.3%   | 75%            | 0.63     |

- Logistic Regression performed better overall based on cross-validated F1 score.
- Random Forest achieved higher recall, useful for identifying churners.

## Key Findings

- Month-to-month contract customers are significantly more likely to churn.
- Lack of online security and tech support services is associated with higher churn.
- Customers using electronic checks show increased churn rates.
- Tenure is inversely related to churn risk.

## Business Recommendations

- Target month-to-month customers with retention incentives.
- Upsell tech support and online security to reduce churn risk.
- Encourage automatic payment options over electronic checks.
- Focus engagement efforts on customers within their first few months.

## Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
- Git & GitHub for version control

## File Structure

- `churn_analysis.ipynb` – Full notebook
- `feature_importance.png` – Top predictors visualization
- `README.md` – Project summary

## Portfolio

View this and other projects at [taniagreen03.github.io](https://taniagreen03.github.io)