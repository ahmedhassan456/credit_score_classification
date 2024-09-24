# Credit Score Detection

## Overview

This project aims to build a predictive model to detect the credit score of customers based on various financial and personal features. The dataset contains detailed information about customers' incomes, loans, payment behaviors, and credit utilization, which are used to determine the credit score.

## Dataset

The dataset includes the following features:

1. **ID**: Unique identifier for each entry.
2. **Customer ID**: Unique identifier for each customer.
3. **Month**: The month of the year for the recorded data.
4. **Name**: The name of the customer.
5. **Age**: The age of the customer.
6. **SSN**: Social Security Number of the customer.
7. **Occupation**: Occupation of the customer.
8. **Annual_Income**: Annual income of the customer.
9. **Monthly_Inhand_Salary**: Monthly salary of the customer.
10. **Num_Bank_Accounts**: Number of bank accounts the customer holds.
11. **Num_Credit_Card**: Number of credit cards the customer holds.
12. **Interest_Rate**: Interest rate on the credit card.
13. **Num_of_Loan**: Number of loans the customer has taken.
14. **Type_of_Loan**: Types of loans the customer has taken.
15. **Delay_from_due_date**: Average number of days the payment was delayed.
16. **Num_of_Delayed_Payment**: Number of delayed payments made by the customer.
17. **Changed_Credit_Limit**: Percentage change in the credit limit.
18. **Num_Credit_Inquiries**: Number of inquiries made for credit.
19. **Credit_Mix**: Classification of the mix of credits the customer holds.
20. **Outstanding_Debt**: Outstanding debt amount (in USD).
21. **Credit_Utilization_Ratio**: Utilization ratio of the credit card.
22. **Credit_History_Age**: Age of the customer's credit history.
23. **Payment_of_Min_Amount**: Whether the customer paid only the minimum amount due.
24. **Total_EMI_per_month**: Monthly EMI payments (in USD).
25. **Amount_invested_monthly**: Amount invested by the customer each month (in USD).
26. **Payment_Behaviour**: The general payment behavior of the customer.
27. **Monthly_Balance**: Monthly balance amount after expenses (in USD).


## Project Structure

The project consists of the following files:

- `credit_score_detection.ipynb`: The main notebook where the analysis and model development are performed.
- `README.md`: This file, containing information about the project and instructions for usage.

## Setup

### Prerequisites

To run this project, you need to install the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `imblearn`
- `optuna`

You can install the required libraries by running:

```bash
pip install -r requirements.txt
```

### Dataset

Ensure the dataset is available in the correct format before running the notebook. You can place the dataset file in the same directory as the notebook.

## Usage
1. Open the Jupyter notebook: `credit_score_detection.ipynb`.
2. Run the cells sequentially to load the dataset, perform exploratory data analysis (EDA), and train the model.
3. The notebook will guide you through various stages of data preprocessing, feature engineering, model building, and evaluation.


## Model

The model is built to predict credit scores using various classification algorithms. The current implementation uses the following algorithms:

- XGBoost Classifier
- Optuna

The model's performance is evaluated using accuracy, precision, recall, and F1-score. Feature importance is also visualized to understand the key drivers of credit scores.
