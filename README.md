# Project Name
> Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- About Project
    This is a data science project mainly data visualization and understand the trends from the dataset to predict whether loan will be defaulted or not based on the corelation of loan status with other parameters in the dataset
- What is the background of your project?
    This is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

    If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

    If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- What is the business probem that your project is trying to solve?
    Use EDA to understand how consumer attributes and loan attributes cater to loan defaulting and what are the other general issues which influence in loan defaulting
- What is the dataset that is being used?
    Dataset used is a csv file which has loan data and consumer details for the leading consumer Finance company Lending Club

## Conclusions
- Major driving factors to which predicts the loan defaulters:
    1.  DTI ratio
    2.  Loan grades
    3.  Verification status
    4.  Annual income
    5.  Employee tenure of working (Experience in years)
    6.  Bankruptcy

- Other considerations and supporting facts in stats for drawing the conclusion:
    - Borrowers not from metropolitan cities like New York, California, Florida etc.,
    - Borrowers having income 0-100000.
    - Borrowers having grades of E,F,G indicates high chance of defaulting.
    - Borrowers with highest DTI ratio
    - Employee who has working experience who has 1 year and 10+ years.
    - Over the years the defaulting of loans to total loans is decreasing which is a good indication but overall, the defaulted loans are increasing in number as number of     loans getting approved are increasing in number.
    - Source verified has least number of defaulted loans, can consider to source verify if the defaulters have higher DTI ratio and less income to check if the borrower can turn into potential defaulter or not.

## Technologies Used
- Pandas - version 2.1.4
- NumPy - version 1.26.4
- Seaborn - version 0.14.0.dev0
- MatplotLib - version 3.7.3

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad IIITB Program as a case study for Machine Learning and Aritificial Intelligence PGP program.


## Contact
Created by [@sindhuperi93] - feel free to contact me!