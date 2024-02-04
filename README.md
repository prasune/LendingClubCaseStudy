# Lending Club - Loan Data Analysis
Lending Club - Loan Data Analysis is aimed to enhance revenue of Lending Club by reducing loan to risky applicants while making sure that non-risky applicants are not missed out.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


## General Information
### Background
Lending Club is the largest online loan marketplace. AtLending Club, Borrowers can easily access lower interest rate loans through a fast online interface.
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

We need to reduce loan to risky applicants to avoid financial loss to the company.

### Problem Statement
Enhance revenue by reducing loan to risky applicants while making sure that non-risky applicants are not missed out.
* Identify Risky loan applicants using Exploratory Data Analysis
* Identify driving factors behind loan default
* Identify patterns which indicates that a person is likely to default

### Dataset used
* Data of past loan applicants can be used for Data Analysis

## Conclusions
#### Conclusion from the analysis of loan status
Around 14.4% of the customers have defaulted
#### Conclusion from the analysis of interest rates and loan status
There is a high ratio of defaulters among those who took loan at high interest rates. <br>
Recommendation - There should be more investigation on repaying capability of applicants who is ready to take loan at a higher interest rate.
#### Conclusion from the analysis of loan tenure and loan status
High percentage of defaulters were seen for the loans taken for longer tenure  <br>
Recommendation - More strict verification of the repaymentg capability of applicants who is opting for longer tenure.
#### Conclusion from the analysis of loan amount range and loan status
Ratio of defaulters are increasing with higher loan amount range  <br>
Recommendation - Investigate repayment capacity while providing higher loan amount
#### Conclusion from the analysis of loan purpose and loan status
loans taken for small business, debt consolidation and other purpose are showing high percentage of defaulters. <br>
Recommendations - Verification of repayment capacity should be done while providing loans for small business.
Verification of credit history must be done while providing loan for Debt consolidation.
Loans marked for other purpose needs more transparency on purpose
#### Conclusion from the analysis of loan verification status
Recommendation - Revisit verification strategy - very high number of loan applicants are provided loan without any verification
#### Conclusion from the analysis of loan verification status and loan status
Verification has not made much difference in preventing defaulters. <br>
Recommendation - Revisit the verification process and address the gaps as it is failing to prevent defaulters.

## Technologies Used
- Python - Anaconda version
- numpy
- pandas
- matlibplot
- seaborn


## Contact
Created by [@prasune] - feel free to contact me!


