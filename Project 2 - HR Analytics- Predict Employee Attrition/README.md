# Project 2-HR Analytics-Predict Employee Attrition

## Objective
The objective of this project is to analyze employee data to understand the primary causes of attrition and build a machine learning model that predicts whether an employee is likely to leave. The goal is to help HR departments take proactive steps to improve retention and make data-driven decisions.

---

## Tools Used
- *Python* (Pandas, Seaborn, Scikit-learn, SHAP)
- *Jupyter Notebook*
- *Power BI*

---

## Project Workflow

### 1. Data Cleaning & Exploration
- Loaded HR data and removed null values
- Performed exploratory data analysis (EDA) to uncover patterns such as:
  - Attrition by department
  - Effect of overtime, income, and job roles

### 2. Data Preprocessing
- Encoded categorical variables using LabelEncoder
- Split the dataset into training and testing sets

### 3. Model Building
- Trained a *Logistic Regression* model to classify whether an employee will leave
- Evaluated using accuracy, confusion matrix, and classification report

### 4. SHAP Value Analysis
- Used SHAP to interpret model predictions and determine the most influential features
- OverTime, MonthlyIncome, JobRole, and YearsAtCompany were top factors

### 5. Dashboard Design (Power BI)
- Created an interactive dashboard with:
- KPI cards (Total Employees, Attrition Rate, Avg. Income, etc.)
- Charts showing attrition by department, gender, salary, overtime
- Slicers for department, gender, and job role

### 6. Final Suggestions
- Developed key recommendations to help reduce attrition, based on data and SHAP insights

---

## Deliverables

| File                            | Description                                        |
|---------------------------------|----------------------------------------------------|
| HR_Analytics_Dashboard.pbix     | Power BI interactive dashboard                     |
| HR_Analytics_Dashboard.pdf      | PDF export of the dashboard                        |
| HR_Attrition_Model.ipynb        | Jupyter Notebook with full analysis and model      |
| model_report.txt                | Accuracy, confusion matrix, classification report  |
| shap_summary.txt                | Explanation of model predictions using SHAP        |
| attrition_suggestions.pdf       | Final recommendations to reduce attrition          |
| HR_Analytics_Project_Report.pdf | Project Report                                     |

