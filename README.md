# Risk Analysis and Monthly Trends Case Study

This repository contains the analysis and findings of a case study on risk analysis and monthly trends in the telecommunications industry. The case study focuses on analyzing applications for business postpaid mobile accounts and identifying monthly trends, risks, and opportunities for driving incremental revenue while managing overall risk.

![Screenshot 2023-06-21 235133](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/152ddf73-87bc-442e-aa85-8f75514c3a95)

📊 Visit the Tableau Public to discover more:

https://public.tableau.com/app/profile/nicktimosh/viz/telecom_16867623548950/ActivationTrendandRiskAnalysis

📄 Please find more insights described in final presentation:
[Presentation](https://github.com/NickTimosh/telecom_risk_analysis/blob/main/230614_Case_study_final_draft.pdf)

## Problem Description

The case study involves analyzing data from applications for business postpaid mobile accounts between 2020 and 2021 years (24 months). The goal is to perform a risk analysis with monthly trends and identify areas of opportunity to drive incremental revenue while effectively managing overall risk. The dataset includes information such as application creation and start months, account types, lines requested, age groups, risk indicators, provinces, and channel types.

Below diagram, explains the process where a client applies for a mobile phone from a store:

![Screenshot 2023-06-21 235343](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/2ce6c6ce-90d2-471d-ac2b-25262fe406b9)

![Screenshot 2023-06-21 235409](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/90b79f19-7821-42a7-9cc5-67491d1d8465)

## Data Definition
The application data is stored in the following two tables and column BAN is the unique key (Primary key) on both the tables.

•	Table  1 – CREDIT_APPLICATIONS

![Screenshot 2023-06-21 235548](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/dee2f1be-bfd4-4877-83e0-a61d2f33c70d)

•	Table 2 – CREDIT_RISK

![image](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/b9734ac0-36d0-4c04-84e9-3e1ebc3e7a52)

•	Table 3 – Target
Targets for activation rate by month

• 1 Year Bad debt Rate by Credit Class:
Bad debt rate is defined as the number of clients those will be delinquent (do not pay their bills) and end up as bad debt (WRITE OFF) with in the first year of activation.

![Screenshot 2023-06-21 235654](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/b50debaa-1d77-49ee-9bce-1910cfe20ddd)

## Analysis Steps

1. Data Exploration: Explore the dataset, check for data inconsistencies, missing values, and outliers. Filter out records flagged as potential duplicates or data mismatches for further analysis.

2. Activation Trend Analysis: Analyze monthly trends in application creation and activation. Calculate the total number of applications created and approved for each month. Calculate the activation rate for each month and compare it with the average activation rate for the entire dataset. Compare the activation rates with the target activation rates provided. Explore the distribution of activations by province and channel types.

3. Risk Assessment: Assess the credit risk associated with the applications. Analyze credit scores, credit classes, and risk indicators to understand the risk profile of the applicants. Identify any patterns or trends related to risk levels and activation outcomes.

4. Conclusions and Recommendations: Draw conclusions based on the analysis performed. Provide recommendations for targeted marketing strategies, risk mitigation measures, and improving activation rates.
