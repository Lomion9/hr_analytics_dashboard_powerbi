# HR Analytics Dashboard | Power BI

A multi-page Power BI report built on the IBM HR Analytics 
dataset. The goal is to analyze employee attrition and identify 
high-risk employees using a custom risk scoring model.

📄 [Türkçe README için tıklayın](README_TR.md)

## Pages

### 1. Attrition Overview
Attrition analysis by job role, department, overtime, stock 
option level, and years since last promotion.

![Attrition Overview](HR1.png)

### 2. Employee Demographics
Workforce profile analysis by age group, gender, department, 
and education field.

![Employee Demographics](HR2.png)

### 3. Satisfaction & Risk Factors
Combined risk score model, environment satisfaction, job 
involvement, and estimated attrition cost analysis.

![Satisfaction & Risk Factors](HR3.png)

## Key Features

- **Risk Score Model**: Custom 0-4 risk score per employee 
  (overtime, stock options, promotion history, job satisfaction)
- **Estimated Attrition Cost**: $9.2M annual cost estimate
- **High Risk Employee Table**: Actionable list of 127 employees 
  for immediate HR intervention
- 3-page interactive dashboard with navigation
  
## Key Insights

- Employees working overtime have an attrition rate of **30%**, 
  3x higher than those who don't (**10%**)
- Employees with no stock options show **25%** attrition rate, 
  dropping to **5%** at stock option level 3
- Employees who haven't been promoted in 6-10 years carry the 
  highest attrition risk (**18%**)
- Sales Representatives have the highest attrition rate of any 
  job role (**40%**)
- **60%** of employees with a risk score of 4 have left the 
  company — validating the predictive power of the model
- A total of **127 employees** fall into the high-risk category 
  (score ≥ 3)
  
## Tools Used

- Power BI Desktop
- DAX
- Power Query

## Data Source

IBM HR Analytics Employee Attrition Dataset — Kaggle
