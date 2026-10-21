# Telco Customer Churn — Lab 1

Exploratory data analysis of the Telco Customer Churn dataset
(https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Dataset
`data/Telco-Customer-Churn.csv` — 7043 customers, 21 features.

## Task Progress
- [x] i. Introduction — notebook opens with the goal and scope of the analysis.
- [x] ii. Load the dataset — loaded successfully as `df` (7043 rows, 21 columns).
- [x] iii. Display head & tail — data structure inspected.
- [x] iv. Data preprocessing — 
  - Encoded `Churn` to binary (1/0).
  - Converted `TotalCharges` from object to float64.
  - Removed 11 rows with null values (new shape: 7032 rows).
- [ ] v. Data exploration
  - [x] a. Demographic Analysis (Gender, Senior Citizen, Partner, Dependents)
  - [ ] b. Service Analysis (Phone Service)
  - [ ] c. Payments Analysis (Contract, Paperless Billing, Payment Method)

## Notebook
`notebooks/Lab1_Churn_Analysis.ipynb`