# 🏦 Banking Loan Risk & Customer Analytics

**A data analytics project focused on understanding customer financial behavior, evaluating loan default risk, and generating actionable business insights using SQL, Python, and Power BI.**

---

## 📌 Project Overview

Banking Loan Risk & Customer Analytics analyzes customer demographics, financial information, loan details, credit history, and repayment behavior to understand lending patterns and identify potential credit risks.

The project combines SQL-based data processing, Python exploratory data analysis, and interactive Power BI dashboards to help visualize loan performance, assess customer risk, and support data-driven banking decisions.

## 🎯 Project Objectives

- Analyze customer demographics and financial behavior.
- Identify customers with higher loan default risk.
- Evaluate default rates and credit score patterns.
- Study the relationship between income, education, and loan approvals.
- Understand loan repayment behavior and lending trends.
- Generate actionable recommendations to improve credit risk management.

## 📂 Dataset Information

The project uses customer, loan, and credit history datasets.

### Customers Table
- Customer ID
- Age
- Gender
- Education
- Income
- Employment Experience
- Home Ownership

### Loans Table
- Loan Amount
- Loan Purpose
- Interest Rate
- Loan Status

### Credit History Table
- Credit Score
- Previous Loan Defaults

## 🛠️ Tools & Technologies

| Category | Technologies |
|---|---|
| Database | PostgreSQL |
| Query Language | SQL |
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Business Intelligence | Power BI, DAX |
| Version Control | Git, GitHub |

## ⚙️ Project Architecture

```text
       Raw Datasets
            |
            ▼
      SQL Data Cleaning
            |
            ▼
    Python Data Analysis
            |
            ▼
     Power BI Dashboard
            |
            ▼
      Business Insights
```

## 🔄 Project Workflow

### 1. SQL – Data Processing
- Imported CSV datasets into PostgreSQL.
- Created database tables.
- Applied SQL joins and transformations.
- Performed data cleaning.
- Prepared the final dataset for analysis.

### 2. Python – Exploratory Data Analysis
- Imported datasets using Pandas and NumPy.
- Performed data cleaning and preprocessing.
- Conducted Exploratory Data Analysis (EDA).
- Identified trends, patterns, and relationships.
- Created visualizations using Matplotlib.

### 3. Power BI – Dashboard Development
- Imported the analyzed dataset.
- Created data relationships.
- Developed DAX measures and KPIs.
- Built interactive dashboards.
- Added slicers and navigation buttons.

## 📊 Dashboard Overview

The Power BI report is organized into the following sections:

### Executive Dashboard
- Total Loan Amount
- Total Customers
- Average Credit Score
- Default Rate

### Risk Dashboard
- High-Risk Customers
- Loan Status Analysis
- Credit Score Analysis
- Risk Segmentation

### Customer Dashboard
- Customer Demographics
- Education Analysis
- Income Analysis
- Home Ownership Analysis

### Data Dictionary
- Column Names
- Data Types
- Column Descriptions
- Business Usage

## 📈 Key Performance Indicators (KPIs)

- Total Customers
- Total Loan Amount
- Average Income
- Average Credit Score
- High-Risk Customers
- Default Rate

## 💡 Key Insights

- Higher credit scores are associated with lower default risk.
- Customers with previous loan defaults may have a higher likelihood of defaulting again.
- Mortgage owners generally show better repayment records in the analyzed data.
- Education loans represent a significant portion of total loans.
- Customer income is an important factor when evaluating repayment ability.

## 🏢 Business Recommendations

- Improve credit risk assessment processes.
- Monitor high-risk customers more closely.
- Apply stricter evaluation criteria to higher-risk loan applications.
- Encourage responsible lending to customers with stronger repayment profiles.
- Strengthen fraud detection and monitoring systems.

## 📁 Project Structure

```text
Banking-Loan-Risk-Customer-Analytics/
│
├── Dataset/
│
├── Python/
│   └── loan_analysis.ipynb
│
├── SQL/
│   └── loan_analysis.sql
│
├── Power BI/
│   └── loan_analysis.pbix
│
├── Dashboard/
│   ├── Executive Dashboard/
│   ├── Risk Dashboard/
│   ├── Customer Dashboard/
│   └── Data Dictionary/
│
└── README.md
```

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/VedikaDherange/banking-loan-risk-customer-analytics.git
```

### 2. Navigate to the Project Directory

```bash
cd Banking-Loan-Risk-Customer-Analytics
```

### 3. Install Required Python Libraries

```bash
pip install pandas numpy matplotlib
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the Python notebook to explore the analysis.

## 🔮 Future Enhancements

- Build a machine learning model for loan default prediction.
- Implement AI-based fraud detection.
- Deploy the solution to a cloud platform.
- Integrate real-time data and dashboard updates.

## 👩‍💻 Author

**Vedika Dherange**

**Technical Skills:** SQL | Python | Power BI | DAX | Data Analysis | Data Visualization

---

⭐ If you find this project useful, consider giving the repository a star!
