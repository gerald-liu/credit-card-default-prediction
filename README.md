# Default Payments of Credit Card Clients
Course project of ISOM 3360, 2020 Spring, HKUST

## Business Problem

Nowadays, the use of credit card becomes an integral part of modern economies. Still, default on credit card payment is considered to be a crucial problem globally. Default on credit card payment is failure to make debt payment by the due date. This may happen due to a sudden change in a person&#39;s income source such as sudden job loss, inability to work, or some health issues. It may also be deliberate, when people intentionally use the credit card, knowing they could not afford to repay loans later, until the bank stopped their cards.

Card issuers have great troubles dealing with the default account. They have to urge people to repay or even take legal action to enforce payment. If people are not solvent, banks will bear the losses itself. According to figures from the Bank of England, the default rate, which is calculated by the central bank based on a balance of responses from lenders, is 22.9%, and caused huge losses to banks.

## Project Goal

Our project aims to help credit card companies in Taiwan to detect the potential default account earlier based on the features data we have, so they can take preventive actions to minimize the losses. In addition, based on the prediction, credit card companies can also issue credit card smarter to people with accounts with lower default risk and also help the customers by providing necessary suggestions to avoid default.

## Possible Data Features

1. LIMIT\_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit)
2. SEX: (1=male, 2=female)
3. EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5,6 =unknown)
4. MARRIAGE: Marital status (1=married, 2=single, 3=others)
5. AGE: Age in years
6. PAY\_0 – PAY\_6: Repayment status in September - April, 2005 (-1=pay in advance for one month, 0=pay on time, 1=payment delay for one month, 2=payment delay for two months, … 8=payment delay for eight months, 9=payment delay for nine months and above)
7. BILL\_AMT1 - BILL\_AMT6: Amount of bill statement in September - April, 2005 (NT$)
8. PAY\_AMT1 - PAY\_AMT6: Amount of previous payments in September - April, 2005 (NT$)

## Data Source

UCI Machine Learning Repository ([https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)):

This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

## Timetable

| Week | Task | Remarks |
| --- | --- | --- |
| 1 (3.27 - 4.2) | Data cleaning, missing values handling | 3.31 Status meeting 1 |
| 2 (4.3 - 4.9) | Feature selection and engineering |   |
| 3 (4.10 - 4.16) | Preliminary model and evaluation | 4.16 Progress report |
| 4 (4.17 - 4.23) | Preliminary parameter tuning | 4.21/23 Status meeting 2 |
| 5 (4.24 - 4.30) | Alternative model |   |
| 6 (5.1 - 5.7) | Model selection and parameter tuning |   |
| 7 (5.8 - 5.14) | Report drafting | 5.14 Final report |
