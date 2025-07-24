# 🧠 HR Management System: Strategic Workforce & Asset Insights Dashboard - Health Canada

A comprehensive and interactive Power BI solution built on synthetic data, designed to provide deep insights into workforce trends, recruitment activities, asset conditions, and forecasted HR metrics—supporting strategic planning and informed decision-making across HR and finance functions.

---

## 📌 Short Description / Purpose

The **HR Management System Dashboard** is a multi-tab Power BI report offering a holistic view of human resources, finance, and asset management across a fictional organization. It empowers decision-makers to monitor headcount, analyze turnover, optimize recruitment spend, track asset performance, and forecast key HR metrics.

This project uses **hypothetical HR, finance, and asset data** that was **generated and preprocessed using Python**. We applied **machine learning techniques** to clean the data—handling missing values, smoothing trends, and ensuring data quality for reliable insights.

---

## 🛠 Tech Stack

This project was developed using:

- **📊 Power BI Desktop** – For dashboard creation and visual analytics  
- **📂 Power Query** – For data transformation and shaping  
- **🧠 DAX (Data Analysis Expressions)** – For KPIs and dynamic measures  
- **🤖 Python (Pandas, NumPy, Faker, Scikit-learn)** – For:
  - Data generation (employee, asset, finance data)
  - ML-based cleaning (outlier detection, imputation, encoding)  
- **🧱 Relational Modeling** – Simulated relationships between employees, assets, and financial metrics  
- **📁 File Formats** – `.pbix`, `.csv`, `.ipynb`, `.png`

---

## 📊 Data Source

This dashboard uses **simulated data** that was fully generated using Python. The dataset was designed to mimic a real-world HR environment and includes:

- Employee data: Roles, salaries, gender, join/leave dates, notice periods  
- Financial data: Recruitment budget, training costs, time-to-hire metrics  
- Asset data: Asset types, conditions (New/Good/Fair/Poor), cost and maintenance  
- Forecasting data: Projected departure rates, budget trends, maintenance projections  

### Data Preparation Highlights:

- Used `Faker` and `NumPy` to generate plausible fake data  
- Handled missing values with ML-based imputation (e.g., KNN, regression)  
- Removed outliers using isolation forest and z-score methods  
- Applied label encoding and normalization for BI readiness

---

## 🔍 Features / Highlights

### 🧍‍♀️ HR Dashboard
- Count of Employees by Role  
- Average Salary Distribution  
- Current Employees vs. Leavers  
- Gender Breakdown  
- KPIs: Turnover Rate, Notice Periods, Hiring Rate  

### 💰 Finance Dashboard
- Open Vacancies & Budget Tracking  
- Total Recruitment Cost by Role  
- Time to Hire Analysis  
- Hire Source Effectiveness  

### 🧾 Assets Dashboard
- Asset Condition Overview (New, Good, Fair, Poor)  
- Maintenance Cost Analysis  
- Initial vs. Current Asset Value  
- Asset Inventory Count  

### 🔮 Forecasting Dashboard
- Departure Rate Forecast (2015–2030)  
- Recruitment Expenditure Projection  
- Maintenance Cost Forecast  

---

## 📈 Business Impact & Use Case Simulation

- 🚀 Simulate workforce turnover and plan retention strategies  
- 💸 Align fictional recruitment costs with hypothetical budgeting goals  
- 🛠 Understand asset lifecycle and simulate cost-saving maintenance planning  
- 📊 Practice DEI monitoring and HR analytics  
- 📅 Use forecasting to simulate future HR and financial scenarios  
- 🤖 Explore ML for cleaning and preparing organizational data for BI tools  

---

## 🧪 Ideal For:

- Business Intelligence Students  
- HR Analysts Learning Power BI  
- Data Analysts Practicing Dashboard Design  
- Anyone wanting to showcase end-to-end BI capabilities from **data generation to dashboard storytelling**

