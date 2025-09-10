# Lending Club Case Study - Exploratory Data Analysis  

## 📌 Problem Statement  
You work for a **consumer finance company** that specializes in lending various types of loans to urban customers.  
When the company receives a loan application, it must decide whether to approve the loan based on the applicant’s profile.  

Two major risks are associated with this decision:  
1. **Business Loss Risk**: If a creditworthy applicant is denied a loan, the company loses potential business.  
2. **Financial Loss Risk**: If a high-risk applicant is approved, the applicant may default, leading to monetary loss.  

The dataset contains historical loan application data, including whether applicants have defaulted in the past.  
The objective of this project is to perform **Exploratory Data Analysis (EDA)** to identify patterns that indicate whether an applicant is likely to default.  
These insights can help the company take actions such as:  
- Denying the loan,  
- Reducing the loan amount, or  
- Lending to risky applicants at a higher interest rate.  

## 🎯 Objectives  
- Clean and preprocess the dataset.  
- Perform univariate, bivariate, and multivariate analysis.  
- Derive new features to improve interpretability.  
- Identify key factors influencing loan default.  
- Provide data-driven recommendations to minimize credit risk.  

## 📂 Dataset  
The dataset consists of past loan applicants with details such as:  
- **Loan details**: amount, term, interest rate, grade, purpose  
- **Borrower details**: income, employment length, home ownership  
- **Loan status**: fully paid, charged off, defaulted  

## 🔎 EDA Workflow  

### 1. Data Cleaning  
- Removed redundant columns  
- Treated missing values and outliers  
- Standardized categorical variables  

### 2. Feature Engineering  
- Derived financial risk metrics such as loan-to-income ratio, debt-to-income flags, etc.  
- Created binary target variable for loan default vs fully paid  

### 3. Univariate Analysis  
- Distribution of loan amount, income, interest rate  
- Frequency of loan grades, purposes, and terms  

### 4. Bivariate Analysis  
- Default rate by grade, loan purpose, and home ownership  
- Relationship of DTI, interest rate, and loan amount with default probability  

### 5. Multivariate Analysis  
- Pairplots to analyze combined feature effects  
- Correlation heatmap of numerical variables  

## 📊 Key Insights  
- **Higher interest rates** and **lower loan grades** strongly correlate with default.  
- Borrowers with **high debt-to-income ratios** show increased risk.  
- **Longer loan terms (60 months)** are riskier compared to shorter terms.  
- Low-income borrowers opting for **large loan amounts** default more often.  
- Loan purposes such as **small business** and **debt consolidation** are linked with higher default rates.  

## 🛠 Tech Stack  
- **Python**  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn  
- **Environment**: Jupyter Notebook  

## 📌 Deliverables  
- Cleaned and structured dataset  
- Detailed EDA report with visualizations  
- Actionable recommendations for credit risk assessment  
