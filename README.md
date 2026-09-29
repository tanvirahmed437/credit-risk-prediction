# Credit Risk Prediction

## Project Overview

This project uses machine learning to predict whether a customer is likely to default on a loan.

The project uses the Home Credit dataset and includes:

- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Data preprocessing
- Machine learning model training
- Model evaluation
- Feature importance analysis
 ## Dataset

The project uses the Home Credit Default Risk dataset.

The target variable is `TARGET`:

- `0` = No loan default
- `1` = Loan default
  ## Models

Three machine learning models were trained and compared:

1. Logistic Regression
2. Random Forest
3. XGBoost

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Average Precision
  ## Model Evaluation

The models were evaluated on the validation dataset.

Model |               Average Precision 

Logistic Regression | 0.2273 
Random Forest |       0.2089 
XGBoost |             0.2486 
## Project Workflow

The project follows a complete machine learning workflow:

1. Data Loading
2. Data Understanding
3. Target Variable Analysis
4. Missing Value Analysis
5. Numerical Feature Analysis
6. Categorical Feature Analysis
7. Feature Engineering
8. Feature and Target Preparation
9. Data Preprocessing
10. Logistic Regression
11. Random Forest
12. XGBoost
13. Model Evaluation and Comparison
14. Confusion Matrix, ROC and Precision-Recall Curves
15. Feature Importance and SHAP Analysis
## Key Findings

Three machine learning models were trained and evaluated for credit risk prediction.

Based on Average Precision on the validation dataset:

* Logistic Regression achieved an Average Precision of **0.2273**.
* Random Forest achieved an Average Precision of **0.2089**.
* XGBoost achieved an Average Precision of **0.2486**.

The models were evaluated using multiple classification metrics, including Accuracy, Precision, Recall, F1 Score, ROC-AUC, and Average Precision.

Feature importance and SHAP analysis were also performed to improve the interpretability of the machine learning predictions.
## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* SHAP
* Jupyter Notebook
* Git & GitHub
## Project Structure

credit-risk-prediction/
│
├── credit_risk_analysis.ipynb
├── README.md
└── requirements.txt
## How to Run

### 1. Clone the repository
git clone YOUR_GITHUB_REPOSITORY_URL
cd credit-risk-prediction

### 2. Install the required libraries

pip install -r requirements.txt

### 3. Open the Jupyter Notebook

jupyter notebook

Then open:

credit_risk_analysis.ipynb

Run the notebook cells from top to bottom to reproduce the analysis and model results.
## Limitations
This project is intended for educational and portfolio purposes.
The model predictions depend on the quality and characteristics of the dataset used for training and evaluation. The results may not generalize to every real-world lending environment.
The model should not be used as the sole basis for real-world credit decisions without additional validation, monitoring, and appropriate domain-specific considerations.

## Author

Tanvir Ahmed

Data Science / Machine Learning Project

* GitHub:github.com/tanvirahmed437
* LinkedIn:linkedin.com/in/tanvir-ahmed-4985b9404/



