# Developing a Predictive Credit Risk Model to make data-driven lending decisions
---
## Overview:
This project is focused on the development of a predictive credit risk model for SVI Bank Limited, aimed at enhancing the bank's ability to make data-driven lending decisions, particularly in the domain of subprime mortgages. The bank faces the challenge of assessing loan applications from individuals with poor or limited credit histories, making traditional credit scoring methods less reliable. Subprime mortgages, which are extended to high-risk borrowers, require a nuanced approach to balance risk and profitability.
To address this, we propose the use of a classification model (logistic regression), to predict the likelihood of a loan's repayment status (good or bad) based on a range of financial variables captured at the time of the loan application. The objective is to build a robust, accurate model capable of identifying profitable loan applicants while minimizing the exposure to potential defaults.
Given that SVI Bank wants the solution to consider both profitability and market expansion as key objectives. Maximizing profits involves accepting loans that have a high probability of repayment while expanding market share requires the bank to take on more risk by approving loans with lower repayment probabilities.

In this project, we have utilized a dataset, which contains historical customer data of SVI Bank. The dataset includes metrics such as:

- __TARGET:-__	Target = 1 (Defaulters), Target = O (Good Loans)
- __ID:-__	Customer ID
- __DerogCnt:-__	Number Public Derogatories
- __CollectCnt:-__	Collections
- __BanruptcyInd:-__	Bankruptcy Indicator
- __InqCnt06:-__	Inquiries 6 Months
- __InqTimeLast:-__	Time Since Last Inquiry
- __InqFinanceCnt24:-__	Finance Inquires 24 Months
- __TLTimeFirst:-__	Time Since First Trade Une
- __TLTimeLast:-__	Time Since Last Trade Line
- __TLCnt03:-__	Number Trade Unes Opened 3 Months
- __TLCnt12:-__	Number Trade Lines Opened 12 Months
- __TLCnt24:-__	Number Trade Unes Opened 24 Months
- __TLCnt:-__	Total Open Trade Unes
- __TLSum:-__	Total Balance All Trade Lines
- __TLMaxSum:-__	Total High Credit All Trade Lines
- __TLSatCnt:-__	Number Trade Lines Currently Satisfactory
- __TLDel60Cnt:-__	Number Trade Unes Currently 60 Days or Worse
- __TLBadCnt24:-__	Number Trade Unes Bad Debt 24 Months
- __TL75UtilCnt:-__	Number Trade I-Ines 75 pct Utilized
- __TL50UtilCnt:-__	Number Trade Lines 50 pct Utilized
- __TLBalHCPct:-__	Percent Trade Line Balance to High Credit
- __TLSatPct:-__	Percent Satisfactory to Total Trade Lines
- __TLDel3060Cnt24:-__	Number Trade Lines 30 or 60 Days 24 Months
- __TLDel90Cnt24:-__	Number Trade Unes 90+ 24 Months
- __TLDel60CntAll:-__	Number Trade Lines 60 Days or Worse Ever
- __TLOpenPct:-__	Percent Trade Lines Open
- __TLBadDerogCnt:-__	Bad Dept plus Public Derogatories
- __TLDel60Cnt24:-__	Number Trade Lines 60 Days or Worse 24 Months
- __TLOpen24Pct:-__	Percent Trade Unes Open 24 Months

Through the use of machine learning techniques, this project aims to deliver actionable insights and a data-driven lending strategy that allows the bank to make informed decisions, enhance operational efficiency, and reduce financial risk. This approach will be implemented through the use of a classification model (logistic regression), followed by a decile-based segmentation to determine the optimal decision boundaries for loan approval. Ultimately, the model will provide a framework for SVI Bank to systematically assess and manage loan risks while aligning with their business goals.

Sciki-Learn python library has been used to train a classification Model (logistic regression) utilizing the dataset. The model will predict customers likelihood of a loan's repayment status (good or bad) which will help the company make critical decisions to systematically assess and manage loan risks.
