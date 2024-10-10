
# Customer Churn Analysis - MSIS680 Lab 1

## Project Overview

This project is a lab assignment for MSIS680, focusing on analyzing customer churn data using Python. The objective is to apply data analysis and machine learning techniques to predict customer churn. The project is implemented in a Jupyter Notebook and uses the dataset `customer_churn.csv`.

## Files in the Repository

- **Lab1_MSIS680_Jeny Sherchan.ipynb**: The Jupyter Notebook file containing the Python code for data preprocessing, exploratory data analysis (EDA), and model implementation.
- **customer_churn.csv**: The dataset used in the analysis. It contains customer information from a telecommunications company, including features like tenure, contract type, and whether the customer churned or not.

## Dataset Information

The `customer_churn.csv` dataset includes the following columns:

- `customerID`: Unique identifier for each customer.
- `gender`: Customer's gender (Male/Female).
- `SeniorCitizen`: Whether the customer is a senior citizen (1 for Yes, 0 for No).
- `Partner`: Whether the customer has a partner (Yes/No).
- `Dependents`: Whether the customer has dependents (Yes/No).
- `tenure`: Number of months the customer has stayed with the company.
- `PhoneService`: Whether the customer has phone service (Yes/No).
- `MultipleLines`: Whether the customer has multiple lines (Yes/No/No phone service).
- `InternetService`: Type of internet service (DSL, Fiber optic, No).
- `OnlineSecurity`: Whether the customer has online security (Yes/No/No internet service).
- `OnlineBackup`: Whether the customer has online backup (Yes/No/No internet service).
- `DeviceProtection`: Whether the customer has device protection (Yes/No/No internet service).
- `TechSupport`: Whether the customer has technical support (Yes/No/No internet service).
- `StreamingTV`: Whether the customer has streaming TV service (Yes/No/No internet service).
- `StreamingMovies`: Whether the customer has streaming movie service (Yes/No/No internet service).
- `Contract`: The customer’s contract type (Month-to-month, One year, Two year).
- `PaperlessBilling`: Whether the customer has paperless billing (Yes/No).
- `PaymentMethod`: Payment method used by the customer (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
- `MonthlyCharges`: The amount charged to the customer monthly.
- `TotalCharges`: The total amount charged to the customer.
- `Churn`: Whether the customer has churned (Yes/No).

## Key Tasks

1. **Data Preprocessing**: 
   - Handle missing values and incorrect data types.
   - Convert categorical data to numerical form using encoding techniques like one-hot encoding.
   
2. **Exploratory Data Analysis (EDA)**:
   - Analyze key trends and relationships between different features and customer churn.
   - Visualize data using charts such as histograms, bar plots, and correlation matrices.

3. **Feature Engineering**:
   - Extract important features for predicting customer churn.
   - Scale numerical features for machine learning models.

4. **Modeling**:
   - Build and train machine learning models such as logistic regression, decision trees, or random forest to predict customer churn.
   - Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

5. **Conclusion**:
   - Summarize findings from the analysis and modeling.
   - Provide insights into the factors that influence customer churn and possible recommendations for reducing churn.

## How to Run the Project

1. Clone the repository or download the files.
2. Open the Jupyter Notebook (`Lab1_MSIS680_Jeny Sherchan.ipynb`).
3. Ensure all required Python libraries are installed (e.g., `pandas`, `matplotlib`, `seaborn`, `sklearn`).
4. Load the dataset (`customer_churn.csv`) into the notebook.
5. Run the cells in the notebook sequentially to execute the analysis.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

