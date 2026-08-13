# 👋 Hi, I'm a Data Science Student & Former Data Analyst

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-SQLite%20%7C%20PostgreSQL-4169E1?logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?logo=python&logoColor=white)](https://seaborn.pydata.org/)

> **B.S. in Data Science / Analytics Candidate (Senior Year)**  
> Former **Data Analyst intern** with hands-on experience in SQL data extraction, exploratory data analysis, and reporting (PowerBI and SSRS).

---

## 🎯 About Me

I am a senior undergraduate data science student passionate about leveraging data to solve real business problems. Having worked as a Data Analyst, I combine strong SQL and data wrangling skills with rigorous statistical evaluation and machine learning modeling.

My core areas of focus include:
- **Data Acquisition & SQL ETL**: Parsing messy datasets, string cleaning, schema creation, and database querying in MS SQL Server (SSMS).
- **Exploratory Analytics & Machine Learning**: Building leakage-free feature pipelines, conducting thorough EDA, and benchmarking baseline vs. ensemble classification models (Logistic Regression, Random Forest, Gradient Boosting).
- **Statistical Hypothesis Testing & A/B Analysis**: Evaluating experimental data using Welch's t-tests, Chi-Square tests, power calculations, and confidence intervals to provide actionable business recommendations.

---

## 🚀 Portfolio Projects

### 📊 1. [Tech Job Market & Skill Trends Pipeline](./project-1-job-market-sql-etl)
*Data Cleaning, String Parsing, SQLite Database Integration & Skill Analytics*

- **The Problem**: Job seekers and academic advisors often struggle to track which specific technical skills (Python, SQL, Tableau, AWS) are most in-demand for entry-level roles across different tech regions.
- **The Solution**: Built a modular Python pipeline that ingests raw job posting data, parses text descriptions to extract technical skill tags, cleans messy salary ranges, and populates a relational SQLite database for SQL querying.
- **Key Outcome**: Processed job postings to produce an interactive skill demand report highlighting **SQL (68%)** and **Python (62%)** as top requirements for entry-level analytics positions.
- **Tech Stack**: `Python`, `pandas`, `sqlite3`, `matplotlib`, `seaborn`.

---

### 🤖 2. [E-Commerce Customer Repeat Purchase Predictor](./project-2-customer-churn-ml)
*Exploratory Data Analysis, Feature Engineering, Baseline vs. Ensemble ML Benchmarking*

- **The Problem**: Online retailers need to identify customers at risk of not making a repeat purchase within 90 days to target re-engagement marketing effectively.
- **The Solution**: Conducted end-to-end EDA and built a machine learning pipeline comparing a Baseline Logistic Regression against Random Forest and Gradient Boosting classifiers. Applied `StandardScaler` and `OneHotEncoder` preprocessing to prevent data leakage.
- **Key Outcome**: The Random Forest model achieved **0.86 AUC-ROC** and **0.81 Recall**, successfully identifying key drivers of customer repeat purchases (purchase frequency, average order value, support interaction count).
- **Tech Stack**: `Python`, `pandas`, `scikit-learn`, `seaborn`, `matplotlib`.

---

### 📈 3. [E-Commerce Checkout Redesign A/B Test](./project-3-checkout-ab-test)
*Experimental Design, Inferential Statistics, Welch's t-Test & Business Analytics*

- **The Problem**: An e-commerce company launched a streamlined checkout redesign (Variant B) to reduce cart abandonment, but needed statistical verification before rolling out the change company-wide.
- **The Solution**: Designed and executed an inferential statistical analysis evaluating conversion rate (Chi-Square test) and average revenue per user (Welch's t-test), including normality checks and 95% confidence intervals.
- **Key Outcome**: Demonstrated a statistically significant conversion lift of **+3.4 percentage points** ($p = 0.0023$, 95% CI [$1.2\%, 5.6\%$]), leading to a projected **+$125,000** annual revenue increase.
- **Tech Stack**: `Python`, `scipy.stats`, `statsmodels`, `pandas`, `seaborn`, `matplotlib`.

---

## 🛠️ Skills & Technologies

| Category | Skills & Tools |
| :--- | :--- |
| **Languages** | Python 3, SQL, R, (a little) C++ |
| **Data Manipulation** | Pandas, NumPy, Data Cleaning, Regular Expressions, String Processing |
| **Machine Learning** | Scikit-Learn (Classification, Regression, Preprocessing, Cross-Validation, Feature Importances) |
| **Statistical Analysis** | A/B Testing, Hypothesis Testing (t-tests, Chi-Square), Confidence Intervals, Summary Stats |
| **Databases** | MSSqlServer, Relational Schema Design, SQL Queries, Views, and Sprocs (JOINs, GROUP BY, Window Functions) |
| **Visualization** | PowerBI, Seaborn, Matplotlib, Data Storytelling |

### 4. Intent-Driven UI State Controller ([`project-4-intent-ui-controller`](file:///c:/Users/brode/OneDrive/Desktop/Projects/Antigravity/GitHub%20Portfolio/project-4-intent-ui-controller))
**Role Simulated:** AI Solutions Architect (UX Team)
- **Concept**: A multimodal interface system where natural language commands (e.g., "switch to dark mode", "show me Q3 sales") are mapped directly to strict JSON frontend state changes.
- **Tools Used**: `scikit-learn` (TF-IDF, Logistic Regression), Regex Entity Extraction, Application State Management.
- **Highlights**: Demonstrates the ability to use lightweight, low-latency machine learning models to solve complex UI navigation friction, bridging the gap between backend AI and frontend user experience.

---

## 📬 Contact & Connect

- **GitHub**: [@13roden](https://github.com/13roden)
- **LinkedIn**: [[linkedin.com/in/](https://linkedin.com/)](https://www.linkedin.com/in/broden-nestler/)
- **Email**: `broden.nestler@gmail.com`

---
*All project repositories include clean Python scripts, sample data, and unit tests designed for straightforward execution.*
