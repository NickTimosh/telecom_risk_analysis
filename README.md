# Risk Analysis and Monthly Trends Case Study

![image](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/5479976b-fa9c-479c-861a-c9376e569336)

This repository contains the analysis and findings of a case study on risk analysis and monthly trends in the telecommunications industry. The case study focuses on analyzing applications for business postpaid mobile accounts and identifying monthly trends, risks, and opportunities for driving incremental revenue while managing overall risk.

## Problem Description

The case study involves analyzing data from applications for business postpaid mobile accounts between 2020 and 2021 years (24 months). The goal is to perform a risk analysis with monthly trends and identify areas of opportunity to drive incremental revenue while effectively managing overall risk. The dataset includes information such as application creation and start months, account types, lines requested, age groups, risk indicators, provinces, and channel types.

Below diagram, explains the process where a client applies for a mobile phone from a store:

![image](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/bb937e8c-0333-4714-958c-65bffb7f2893)

![image](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/53ac9bac-0835-4046-8328-8d3d2fd7a535)

## Data Definition
The application data is stored in the following two tables and column BAN is the unique key (Primary key) on both the tables.

•	Table  1 – CREDIT_APPLICATIONS

![image](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/ff566513-0654-4b95-acc5-fd4c895430b0)


•	Table 2 – CREDIT_RISK

![image](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/78c2f0c4-9487-4d5b-a158-1dee31448708)


•	Table 3 – Target
Targets for activation rate by month

• 1 Year Bad debt Rate by Credit Class:
Bad debt rate is defined as the number of clients those will be delinquent (do not pay their bills) and end up as bad debt (WRITE OFF) with in the first year of activation.

![image](https://github.com/NickTimosh/telecom_risk_analysis/assets/116592259/ba26325d-67b4-40b7-b75d-019fbd103031)

## Analysis Steps

1. Data Exploration: Explore the dataset, check for data inconsistencies, missing values, and outliers. Filter out records flagged as potential duplicates or data mismatches for further analysis.

2. Activation Trend Analysis: Analyze monthly trends in application creation and activation. Calculate the total number of applications created and approved for each month. Calculate the activation rate for each month and compare it with the average activation rate for the entire dataset. Compare the activation rates with the target activation rates provided. Explore the distribution of activations by province and channel types.

3. Risk Assessment: Assess the credit risk associated with the applications. Analyze credit scores, credit classes, and risk indicators to understand the risk profile of the applicants. Identify any patterns or trends related to risk levels and activation outcomes.

4. Conclusions and Recommendations: Draw conclusions based on the analysis performed. Provide recommendations for targeted marketing strategies, risk mitigation measures, and improving activation rates.
