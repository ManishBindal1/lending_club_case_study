# Lending Club Case Study
The largest online loan marketplace company wants to understand the driver variables which are strong indicators of loan default. They want to utilize this knowledge for their portfolio and risk assessment. 
Data for all the issued loans from 2007 to 2011 is shared for this company. Objective is to analyze this data set using EDA to identify these driver variables.

## Table of Contents
General Info
Conclusions
Technologies Used
Acknowledgements

## General Information
- This is a case study assignment part of a course. 
- Conduct EDA on the largest online loan marketplace company loan dataset from 2007 to 2011.
- Identify driver variables for loan default. 
- Issued loan from 2007 to 2011.

## Conclusions
Five strong indicators of loan default are:
- Grade (lower the grade, higher the chance of defaulting the loan)
- Interest Rate (defaults are more with higher interest rate)
- Debt to Income Ratio (if debt to income ratio is higher than more chances of defaulting the loan)
- Public Record of Bankruptcies (with public record of bankruptcies, there is a higher chance of defaulting the loan)
- Term (high chances of defaulting the loan if payment term is 60 months)

Following are the recommendations from the analysis:
1. Implement business rules based on the observations around following five variables before approval of the loan applications.
- Grade
- Interest Rate
- Debt to Income Ratio
- Public Record of Bankruptcies
- Term
2. Extra level of scrutiny is required if borrowers are from Nebraska or loan is taken for small business.
3. Loan defaults are high if funded amount by investors is high or annual income is low. Further analysis (multi variable) should be conducted to find more insights and design better loan approval process.

## Technologies Used
- Pandas, NumPy, Matplotlib

## Acknowledgements
This project is part of a course on machine learning.