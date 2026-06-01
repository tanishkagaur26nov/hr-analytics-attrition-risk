# HR Analytics — Employee Attrition Risk Dashboard

## Project Overview
An HR analytics project focused on identifying employees at risk 
of attrition using a weighted scoring model built entirely in 
Microsoft Excel. The project covers end-to-end data work — from 
cleaning a messy raw dataset to building a structured risk model 
with a fully formatted interactive dashboard.

## Dashboard Highlights
- KPI summary cards showing Total Employees (50), High Risk (2), 
  Medium Risk (42), Low Risk (6), and Average Risk Score (55.1)
- Top 20 at-risk employees ranked by Risk Score with conditional 
  colour formatting
- Star rating visual for Performance Rating column
- Donut chart breaking down at-risk employees by Manager
- Donut chart breaking down at-risk employees by Department
- Built entirely in Microsoft Excel using Pivot Charts, 
  conditional formatting, and linked KPI cards

## Key Highlights
- Cleaned raw HR data containing inconsistent date formats, 
  missing department values, duplicate entries, and mixed 
  gender labels
- Used VLOOKUP to enrich employee records with Manager Names 
  and Department Budget from lookup tables
- Built a weighted Attrition Risk Score model using three factors:
    - Tenure (Weight: 35%)
    - Promotion Gap (Weight: 40%)
    - Performance Rating (Weight: 25%)
- Categorised 50 employees into High, Medium, and Low risk bands
- Used Pivot Tables to summarise risk by Manager and Department

## Key Insight
HR department has the highest average attrition risk score (60.3), 
while Legal department has the lowest (47.6) — suggesting HR 
employees are most at risk of leaving despite being responsible 
for managing retention across the organisation.

## Tools Used
- Microsoft Excel (data cleaning, VLOOKUP, weighted scoring 
  model, Pivot Tables, Pivot Charts, conditional formatting)
- GitHub (portfolio hosting)

## Project Structure
- /data → Cleaned dataset and Risk Score output as CSV
- /screenshots → Excel dashboard screenshot
- hr_attrition_risk_model.xlsx → Full workbook with all sheets
