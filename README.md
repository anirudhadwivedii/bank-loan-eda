# Bank Loan Approval – Exploratory Data Analysis

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a bank loan dataset to understand the key factors influencing loan approval decisions.

---

## 📂 Dataset
- The dataset is a publicly available bank loan dataset.
- It contains applicant demographic, financial, and property-related information along with loan approval status.
- The dataset used for analysis is stored in the `loan_dataset.csv` file.

---

## 📁 Repository Structure

- bank_loan_eda.ipynb : Jupyter notebook containing complete exploratory data analysis  
- loan_dataset.csv   : Bank loan approval dataset used for analysis  
- README.md          : Project documentation and overview  


---

## 🧹 Data Cleaning & Preprocessing
- Removed irrelevant identifier column (`Loan_ID`)
- Handled missing values using appropriate statistical methods (median and mode)
- Corrected data types and ensured logical consistency
- Converted `Dependents` into numeric format for analysis

---

## 📊 Exploratory Data Analysis

### Univariate Analysis
- Analyzed distributions of categorical and numerical variables
- Identified right-skewed distributions and outliers in income and loan amount

### Bivariate Analysis
- Examined relationships between `Loan_Status` and other features
- Used visualizations and cross-tabulations to identify influential factors

---

## 🔍 Key Insights
- Credit history is the strongest factor influencing loan approval
- Applicants from Urban and Semiurban areas have higher approval rates
- Graduate applicants show slightly better loan approval rates
- Income and loan amount alone do not guarantee loan approval
- Number of dependents has a weak to moderate influence on approval decisions

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🚀 Conclusion
Exploratory Data Analysis indicates that credit history plays the most significant role in loan approval decisions. The dataset is well-suited for further predictive modeling using machine learning techniques.

---

## 🔮 Next Steps
- Feature engineering
- Building a machine learning classification model
- Model evaluation and performance analysis
