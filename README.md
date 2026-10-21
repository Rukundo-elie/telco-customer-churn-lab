# Telco Customer Churn — Lab 1

Exploratory data analysis of the Telco Customer Churn dataset
(https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Dataset
`data/Telco-Customer-Churn.csv` — 7043 customers, 21 features.

## Task Progress
- [x] i. Introduction
- [x] ii. Load the dataset — (7043 rows, 21 columns)
- [x] iii. Display head & tail
- [x] iv. Data preprocessing — Encoded Churn, fixed dtypes, dropped 11 null rows.
- [x] v. Data exploration
  - [x] a. Demographic Analysis
  - [x] b. Service Analysis
  - [x] c. Payments Analysis

## Key Findings
1. **Contract Type**: Month-to-month customers churn at ~43%, compared to just ~3% for two-year contracts.
2. **Payment Method**: Electronic check users churn at ~45%, while those on autopay (credit card/bank transfer) churn at ~15-17%.
3. **Internet Service**: Fiber optic users churn at ~42%, significantly higher than DSL (~19%).
4. **Demographics**: Senior citizens, customers without partners, and those without dependents are at a higher risk of churning.
5. **Gender**: Has virtually no impact on churn.

## Conclusion
Churn is primarily driven by the type of contract, the payment method, and the internet service type. To reduce churn, the telecom company should incentivize customers to upgrade to longer contracts, switch to automatic payments, and investigate why fiber optic service is causing dissatisfaction.

## Notebook
`notebooks/Lab1_Churn_Analysis.ipynb`