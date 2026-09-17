# Telecom Customer Churn Analysis

Analyzing telecom customer data to find out why customers churn and predicting churn using machine learning.

**Author:** Narmatha Muralidharan | **Student ID:** 83722937

## About

Customer churn means customers leaving a service. This project explores a telecom dataset to find the main reasons customers churn, confirms those reasons with statistical tests, and builds ML models to predict churn.

#### Dataset

* **Source:** [IBM Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* **File:** `WA\_Fn-UseC\_-Telco-Customer-Churn.csv`
* 7,043 customers, 21 features
* Target column: `Churn` (Yes/No)

#### What's Inside

* Data cleaning \& preprocessing
* Exploratory Data Analysis (EDA)
* Statistical hypothesis testing (Chi-Square, T-Test)
* Machine learning models: Logistic Regression, Decision Tree, Random Forest, XGBoost
* Feature importance \& business recommendations

#### Results

* Overall churn rate: **26.5%**
* Best model: **Logistic Regression** — 80.06% accuracy, 84.03% AUC-ROC
* Top churn drivers: Total Charges, Monthly Charges, Tenure, Contract Type, Payment Method

#### Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn, XGBoost

#### How to Run

1. Clone the repo

```bash
   git clone https://github.com/Narmatha-Muralidharan/DA-120B\_Telecom\_Customer\_Churn\_Analysis.git
   cd DA-120B\_Telecom\_Customer\_Churn\_Analysis
   ```

2. Install dependencies

```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn xgboost jupyter
   ```

3. Download `WA\_Fn-UseC\_-Telco-Customer-Churn.csv` from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and place it in the project folder
4. Open and run the notebook

```bash
   jupyter notebook Telecom\_Customer\_Churn\_Analysis.ipynb
   ```

*(Or simply open the notebook in Google Colab and upload the CSV when prompted.)*

#### Conclusion

Contract type, tenure, monthly charges, and lack of support services are the biggest drivers of churn. Telecom companies can use these insights and the trained model to identify at-risk customers early and take action — such as promoting longer contracts and improving support services — to reduce churn.



