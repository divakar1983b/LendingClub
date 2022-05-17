# LENDING CLUB CASE STUDY
> Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.
> When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
* If one can identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 
* Identification of such applicant’s using EDA is the aim of this case study.
* 
![Book logo](/lc1.png)

## Table of Contents
* [OBJECTIVE](#OBJECTIVE)
* [LOAN_DATASET](#LOAN_DATASET)
* [FINDINGS](#FINDINGS)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## OBJECTIVE
- Identify the driving factors (or driver variables) behind loan default.

## LOAN_DATASET

![Book logo](/loanstatus.png)

All the loans processed fall into the following category.
- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
- Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

## FINDINGS
- Overall Defaulter %
  * Of the total loan applicant nearly 14.3% of them found to be defaulting
  * Debit consolidation loan constitutes major volume of loan and as well as major % defaulters (>49%)
![Book logo](/overallcoff.PNG)

- Loan Duration
  * Defaulters % in 60 month loan seems to be 300 times more than 36 month loan
![Book logo](/loandur.PNG)

- Loan Purpose
  * Compared to other loans, % of defaulters in Wedding loan, Medical loan, Moving loan, Vacation loan, Housing loan, Education loan and Renewable loan are very less
![Book logo](/loanpur.PNG)

- Loan Defaulting Factor
  * One of the major factor inflencing loan defaults is lesser Net Cash per Month(NCM) availablity with loan applicant to repay the loan compared to "Fully Paid" loan applicant.
  * Net Cash per Month(NCM) is calcualted by, NCM= (monthly_inc-installment-dti (times) monthly_inc/100)*100/monthly_inc
![Book logo](/loanpur.PNG)

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
