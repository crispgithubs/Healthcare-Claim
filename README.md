# Healthcare-Claim
The goal of this project is to analyze healthcare insurance claims. Cost breakdowns, provider payment ratio and top ICD/CPT code trends

# Introduction
This project is an interactive Healthcare Claim Analytics Dashboard built in tableau, designed to transform raw insurance claims data into clear, actionable insights. it brings together claim costs, provider performance, member level trends and diagnosis procedure patterns into a single unified view.

# Project Overview
The database contains healthcare insurance claims data including member details, claim types, CPT and ICD codes, billed and paid amount. SQL was used to clean the raw data by handling null values, removing duplicate, and standerdizing fields, aggregation queries were created to calculate total paid amounts, average paid per claim, and billed vs paid ratios for drownstream analysis and dashboarding.

https://github.com/crispgithubs/Healthcare-Claim/blob/main/Healthcare%20claim.sql
![image alt](https://github.com/crispgithubs/Healthcare-Claim/blob/71746c61e0f18eea4a29fee656701f637e3ad5bc/my%20sql%20Healthcare%20Claim%20screenshot.png)


# Insights Summary
* inpatient claims dominate cost distribution:- compared to emergency and other claim types. indicating they are the primary driver of overall claims expenditure.
*  Paid ratios vary noticeably across provider;- some provider (e.g PRVOOOO8) show notably higher paid ratios than others, highllighting potential gaps in reimbursement consistency that may warrant auditing.
*  A small set of CPT codes:- (e.g 67890, 23456) account for a disproportionably large share of paid amounts, suggesting these procedure are major cost contributors.
*  Diagnosis Code 110 (Essential Hypertension):- leads the top ICD Codes by paid amounts, followed by A12.3 and B20- pointing to chronic condition management as a significant cost center.
*  Member-Level Analysis:- reveals that a handful of member (e.g Member 6, 32) account for the highest paid amounts, useful for identifying high-cost/high-utilization members for care management programs.

# Dashboard
The dashboard can be found in tableau public
https://github.com/crispgithubs/Healthcare-Claim/blob/main/Healthcare%20Claims.twbx


