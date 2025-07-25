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
- 
## Screenshots of Power BI Visualizations

<img width="1396" height="787" alt="Screenshot 10" src="https://github.com/user-attachments/assets/743d8055-e5be-4ccc-ba79-26d80ab8ef7f" />
<img width="1408" height="795" alt="Screenshot 9" src="https://github.com/user-attachments/assets/dc720a70-b4c0-465d-acfc-30d0263f155f" />
<img width="1406" height="789" alt="Screenshot 8" src="https://github.com/user-attachments/assets/b07084a2-d4e5-4a8d-9ac5-a935fed98570" />
<img width="1919" height="976" alt="Screenshot 7" src="https://github.com/user-attachments/assets/4cf90687-fbac-4ef0-9b0a-2c10dfd010d4" />


## Key Insights
- Employees with longer promotion gaps have higher attrition.
- Medium salary bands and certain departments show higher resignation rates.
- SHAP analysis identified `YearsSinceLastPromotion`, `MonthlyIncome`, and `JobRole` as significant factors.

## Files Included
- 'HR_Employee_Attrition.csv'- Dataset for Jupyter Notebook
- `HR_Employee_Attrition.ipynb` - Complete Jupyter Notebook.
- `Clean_HR_Attrition_PowerBI.csv` - Cleaned dataset for Power BI.
- `HR_Employee_Attrition_PowerBI.pbix` - Power BI Dashboard.
- `HR_Employee_Attrition_Report.pdf` - 2-page project report.

## How to Run
1. Clone this repository:
    ```
    git clone <[repo-link](https://github.com/Akhil-Gaddam/HR_Analytics-Predict_Employee_Attrition_Project.git)>
    ```
2. Upload 'HR_Employee_Attrition.csv' file in jupyter Notebook and Load the Dataset.       
3. Open `HR_Employee_Attrition.ipynb` in Jupyter Notebook and run cells in order.
4. Open `HR_Employee_Attrition_PowerBI.pbix` in Power BI to explore the dashboard.
5. Read `HR_Employee_Attrition_Report.pdf` for project summary and insights.


**Prepared by:** Akhil Gaddam
