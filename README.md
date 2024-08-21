---

# Lending Club Case Study
---
### Project Overview

Lending money involves significant risks, and it’s crucial for companies to make informed decisions to prevent financial losses. This case study aims to identify loan applicants who are more likely to default, which can result in substantial losses for lending institutions. By conducting a detailed analysis, the study seeks to highlight the factors that contribute to the likelihood of default.

## Table of Contents
- [Overview](#overview)
- [Key Findings](#key-findings)
- [Technology Stack](#technology-stack)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Overview

Lending Club, the largest online loan marketplace, facilitates personal loans, business loans, and medical procedure financing. This project's primary business objective is to enhance the company's decision-making process in loan approvals by identifying and mitigating credit risks associated with loan applicants. 

The company can reduce potential financial losses and optimise its loan portfolio by identifying these "risky" applicants who are likely to default. In other words, the company wants to understand the driving factors (or driver variables) behind loan default.

Ultimately, this will strengthen the company's position as the leading online loan marketplace by improving its ability to manage risk and maintain profitability.

Specifically, the goal is to leverage Exploratory Data Analysis (EDA) to uncover patterns and key factors that predict loan defaults.

Loan defaults have a detrimental impact on lenders, causing cash flow issues and financial setbacks. Early identification of high-risk applicants is crucial to reducing credit losses. The dataset used for this analysis is `loan.csv`, which includes various attributes related to borrowers and their loan details.

## Key Findings

- Borrowers with higher interest rates and more than 10 years of employment history are at a higher risk of default.
- Applicants with mortgages and loans exceeding 12,000 are more likely to default.
- Loans for debt consolidation, credit card debt, or small businesses, particularly those above 12,000, are riskier.
- Loans with an average interest rate above 13% show a higher probability of default.
- Loans for housing purposes with an average interest rate over 15% are at increased risk of default.
- A 36-month loan term with an average interest rate of 12.5% and a 60-month term with 16.5% are more prone to default.
- Loans exceeding 15,000 in grades E, F, or G are likely to default.
- Installments between 800 and 12,000 with an average interest rate above 15% are also risky.
- Loans with an average interest rate of 17% and installments over 12,000 indicate a higher risk of default.
- Loss in Verified loan applicants are just marginal above the Non Verified ones. Though its not a key factor, but needs to check the loan  screening sources.


## Technology Stack

- **Python**: v3.10.12
- **NumPy**: v1.26.4
- **Pandas**: v2.1.4
- **Matplotlib**: v3.7.1
- **Seaborn**: v0.13.1

## Acknowledgments

This project was developed as a part of the Executive PG Programme in Machine Learning & AI at IIIT Bangalore.

## Contact

Reach out to the creators:

- **LinkedIn**:
  - [Veda Charitha Bandikallu](https://www.linkedin.com/in/veda-c-7a5662107/)
  - [Viswanadha Venkat Prabhat](https://www.linkedin.com/in/venkat-prabhat-a74148184/)
- **GitHub**:
  - [Veda Charitha Bandikallu](https://github.com/VedaCharithaB)
  - [Viswnadha Venkat Prabhat](https://github.com/venkatprabhat)

---
