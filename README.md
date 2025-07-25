# HR Analytics - Predict Employee Attrition

## Project Overview
This project analyzes HR employee data to identify key reasons for employee resignation and predict future attrition using machine learning. Python in Jupyter Notebook was used for data cleaning, exploration, and model building, while Power BI was used to create interactive dashboards for visualizing insights to support HR decision-making.

## Tools Used
- Jupyter Notebook (Python: Pandas, Seaborn, Sklearn, SHAP)
- Power BI

## Dataset
The dataset contains employee information including Age, , Employee Id, department, salary, years since last promotion, job role, and attrition status (Yes/No).

## Workflow

### 1️.Data Cleaning & Exploration
- Loaded and cleaned the dataset.
- Explored attrition distribution across departments, salary bands, and promotions.

### 2️.Preprocessing
- Label Encoding for the target variable.
- One-Hot Encoding for categorical features.
- Train-test split with stratification and feature scaling.

### 3️.Model Building
- Built a Logistic Regression model with class balancing.
- Evaluated using accuracy (~76%), confusion matrix, and ROC-AUC.
- Applied SHAP analysis for explainability.

### 4️.Power BI Dashboard
- Created visuals:
  - Cards: Total Employees, Attrition Count, Attrition %.
  - Pie Chart: Attrition Yes vs No.
  - Department-wise and Salary Band-wise attrition analysis.
  - Attrition % vs Years Since Last Promotion (line chart).
  - Slicers for Department, Gender, Marital Status.
- Captured screenshots for reporting.

## Key Insights
- Employees with longer promotion gaps have higher attrition.
- Medium salary bands and certain departments show higher resignation rates.
- SHAP analysis identified `YearsSinceLastPromotion`, `MonthlyIncome`, and `JobRole` as significant factors.

## Files Included
- `HR_Employee_Attrition_Cleaned.ipynb` - Complete Jupyter Notebook.
- `Clean_HR_Attrition.csv` - Cleaned dataset for Power BI.
- `HR_Employee_Attrition.pbix` - Power BI Dashboard.
- `HR_Attrition_Report.pdf` - 2-page project report.

## How to Run
1. Clone this repository:
    ```
    git clone <repo-link>
    ```
2. Open `HR_Employee_Attrition_Cleaned.ipynb` in Jupyter Notebook and run cells in order.
3. Open `Clean_HR_Attrition.csv` in Power BI to explore the dashboard.
4. Read `HR_Attrition_Report.pdf` for project summary and insights.


**Prepared by:** Akhil Gaddam

