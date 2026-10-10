# Employee Attrition & Workplace Analytics

**Author:** Gaurav Kanse  
**Project type:** Exploratory Data Analysis (EDA)  
**Dataset:** IBM HR Analytics Employee Attrition & Performance

## Overview
This project explores employee attrition patterns in a dataset of 1,470 employee records. It compares employees who left with employees who stayed and investigates department, overtime, monthly income, job satisfaction, distance from home, job role, age, and work-life balance.

## Objectives
1. Calculate overall attrition rate.
2. Identify departments with higher attrition.
3. Examine overtime and attrition.
4. Compare income for employees who left and stayed.
5. Analyze job satisfaction and attrition.
6. Examine distance from home and attrition.
7. Identify job roles with higher attrition.
8. Explore age patterns.
9. Analyze work-life balance and retention.
10. Compare employees who left with employees who stayed.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook, and optionally SciPy.

## Dataset
Download from [Kaggle: IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset). Put the CSV next to the notebook and name it `WA_Fn-UseC_-HR-Employee-Attrition.csv`.

## Run
Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```
Launch:
```bash
jupyter notebook
```
Open `Employee_Attrition_Workplace_Analytics.ipynb` and run cells from top to bottom.

## Analysis Included
- Data shape, types, missing values, duplicate checks, descriptive statistics
- Overall attrition and retention rates
- Department, overtime, income, satisfaction, distance, job role, age, and work-life balance comparisons
- Leavers-versus-stayers analysis
- Correlation heatmap and IQR outlier analysis
- Optional chi-square and Mann–Whitney U tests
- Exportable summary tables and visualizations

## Key Findings
For the standard 1,470-row version of this dataset:
- 237 employees left and 1,233 stayed; overall attrition is approximately **16.12%**.
- Department attrition: Sales about **20.63%**, Human Resources about **19.05%**, Research & Development about **13.84%**.
- Overtime attrition: Yes about **30.53%**, No about **10.44%**.
- Mean monthly income: employees who left about **4,787**, employees who stayed about **6,833**.
- Job satisfaction score 1: attrition about **21.45%**; score 4: about **11.55%**.
- Mean distance from home: leavers about **10.63**, stayers about **8.92**.
- Sales Representatives have the highest job-role attrition rate, about **39.76%**.
- Mean age: leavers about **33.61 years**, stayers about **37.56 years**.
- Work-life balance score 1 has attrition about **31.25%**; score 4 about **17.65%**.

**Important:** These are rounded results for the commonly distributed dataset. Run the notebook on the exact CSV you submit and use its output as final, because dataset copies can differ.

## Conclusion
Attrition is associated with multiple characteristics, including overtime, job role, income, age, satisfaction, and work-life balance. These descriptive results can guide further investigation, but they do not prove that any single factor causes employees to leave.

## Limitations
- Observational data may not represent every organization.
- Group averages can hide individual variation.
- Correlation and statistical significance do not establish causation.
- Recommendations should be checked against additional organizational context.

## Project Files
- `Employee_Attrition_Workplace_Analytics.ipynb` — analysis notebook
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` — input dataset
- `employee_attrition_outputs/` — generated charts and summary CSV files
- `Employee_Attrition_Workplace_Analytics_Report.pdf` — written report
