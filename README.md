# Lending Club Case Study
This project aims to perform Exploratory Data Analysis (EDA) to understand the patterns and factors influencing loan defaults. The analysis will help in identifying high-risk applicants and making informed lending decisions.

## Table of Contents
* [General Info](#general-information)
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Team](#team)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

  This project focuses on a consumer finance company that provides loans to urban customers. The company needs to decide whether to approve loan applications based on the applicant’s profile. The challenge is to avoid *business loss by denying loans to reliable payers* and *to prevent financial loss by approving loans to those who might default*. The goal is to minimize financial losses by identifying risky applicants early on.

  The dataset used contains historical data on past loan applicants and their repayment statuses, including those who fully repaid, are still repaying, or defaulted on their loans. By analyzing this data, the project aims to identify patterns and key factors that indicate the likelihood of default. This information will help the company make better decisions on loan approvals, rejections, and adjustments to loan terms.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Problem Statement

  Lending Club is a consumer finance marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. It specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
	
 * Identify key factors influencing loan defaults.
 * Provide actionable insights to minimize risk and improve the lending process.

## Objectives

  The core objective of the excercise is to help the company minimise the credit loss. There are two potential sources of credit loss are:

* Applicant likely to repay the loan, such an applicant will bring in profit to the company with interest rates. Rejecting such applicants will result in loss of business.
* Applicant not likely to repay the loan, i.e. and will potentially default, then approving the loan may lead to a financial loss for the company

## Dataset
  The dataset is a csv file with the loan data for the Lending Club. Also an excel file having data_dictionary.

	
## Approach

### Step-by-Step Analysis:
* Data Sourcing: Load the provided csv file data.
* Data Inspection: Understanding the given data.
* Data Cleaning: Address missing values, outliers, and data inconsistencies.
* Data Visualization and Analysis: Perform univariate, segmented univariate and bivariate analysis.
* Insights and observations : Derive insights and suggest actionable recommendations.	

## Conclusions
- Major Driver variables which are strong indicators of default are:
    - **int_rate** (Intrest rate)
    - **purpose** (loan purpose)
    - **dti** (Debt-to-Income Ratio)
    - **grade** (loan grade)
    - **Pub_rec_bankruptcies** (public record bankruptcies)
    - **emp_length** (Employment length)
   
    
- Details on the above variables and other aspects:
    - Borrowers with 60 month term loan has higher chance of defaulting.
    - Borrowers with loan Grade F,D,G have higher chance of defaulting with G the highest.
    - Borrowers who take small_business loan have higher chance of defaulting.
    - Borrowers with Public Recorded Bankruptcy has higher chance of defaulting.
    - Borrowers with experience of 10+ years are more likely to default.
    - Borrowers with High interest specifically above 17.5 are more likely to default.
    - Borrowers loan in dti range of 19-25 have higher chance of defaulting.
    - Borrowers who are on RENT has higher chance of defaulting compared to Mortgage or own house.
    - Borrowers with working experience 10+ years has higher chance of defaulting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Anaconda Navigator - version 2.5.2
- Jupyter Notebook - Version 7.0.8
- Jupyter Lab - Version 4.0.11
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- seaborn - version 0.12.2
- plotly - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is developed as part of the Group Study for Lending Club Case Study module required for Executive PG Programme in Machine Learning & AI - IIIT, Bangalore


## Team
* [Raghavendra Siddappa](#https://github.com/coolhead)
* [Rajesh Sinha](#https://github.com/Sinhakrrajesh)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
