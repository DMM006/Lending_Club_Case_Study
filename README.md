# Lending Club Case Study
### Introduction
- The consumer finance company which specialises in lending various types of loans to urban customers. 
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
- Two types of risks are associated with the bank’s decision:
    - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
    - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This analysis highlights the Exploratory Data Analysis (EDA) for Loan Data Set
- Various EDA process as been carried for loan dataset such as
    - Data Sourcing
    - Data cleaning
    - Univariate analysis
    - Bivariate analysis
    - Derived metrics
- Various visual graphs such as matplotlib and seaborn are used for Exploratory Data Analysis
- The Problem Statement is as follows
![Case](https://user-images.githubusercontent.com/119028946/205984342-9bc19f4d-8569-473f-8a4b-661e93fa1fe2.png)
- When a person applies for a loan, there are two types of decisions that could be taken by the company:
    - __Loan accepted__: If the company approves the loan, there are 3 possible scenarios described below:
        - __Fully paid__: Applicant has fully paid the loan (the principal and the interest rate) 
        - __Current__: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
        - __Charged-off__: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
     - __Loan rejected__: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
- The above figure illustrate the same

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- Matplotlib
- Seaboarn

## Conclusions
The analysis presented above is related to Loan data Set. 
- The aim of this analysis to reduce the loss percentage of Consumer Finance Company by providing the loan to loan applicants
- This detailed analysis of loan dataset using EDA addresses the two key challeges 
    - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
    - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- The analysis presented above, identifies the number of Good_loan and Bad_loans using various EDA process and, also identify the staticstics to approve Full loan and Defaulted loan based on the loan applications. 
- Hence, by identifing staticstics to Full approved loan and dfaulted loan, reduces the loss percentage for the Finance Company

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by
- [DMM006@githubusername] 
- www.linkedin.com/in/dr-manjunath-m


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
