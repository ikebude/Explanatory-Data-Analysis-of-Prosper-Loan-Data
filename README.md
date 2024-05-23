# In-depth Study of Prosper Company’s Loan Data
 ****

## Background Information about the Task and the Dataset
This project involves an exploratory analysis of loan data from Prosper, a San Francisco, California-based company in the peer-to-peer lending industry. Prosper provides unsecured loans and has facilitated over 21 billion dollars in loans to over 1.3M people. The dataset contains information on 81 variables, representing about 113,937 loans collected from the company, It slao provides information about various loan attributes such as borrower information, loan amounts, interest rates, loan statuses, and more.

## Project Objectives

The main objective of this project is to analyze the dataset, focusing on the Lender yield as a tool for investors to select the best loan types for investment1. The project aims to provide insights into the factors that influence the lender yield and how it can be optimized.

The primary objectives of this project are:

- To gain insights into the characteristics of loans facilitated by Prosper.
- To identify patterns and trends within the loan data.
- To explore relationships between different variables in the dataset.
- To uncover any interesting or unexpected findings that could inform decision-making processes.

## Dataset Columns
The dataset contains 81 columns. Some of the key columns analyzed in this project include:
- LoanStatus: The current status of the loan (e.g., Completed, Chargedoff, Defaulted, etc.).
- BorrowerRate: The interest rate assigned to the loan.
- LoanOriginalAmount: The original loan amount requested by the borrower.
- Term: The term length of the loan (e.g., 36 months, 60 months).
- EmploymentStatus: The employment status of the borrower.
- BorrowerState: The state of residence of the borrower.
- ListingCategory: The category of the listing.
- BorrowerAPR: The annual percentage rate (APR) assigned to the loan.
- CreditScoreRangeLower: The lower range of the borrower's credit score.
- CreditScoreRangeUpper: The upper range of the borrower's credit score.

## Deliverables
The deliverables for this project include:

- Jupyter Notebook containing the exploratory analysis code.
- Visualization/pitch deck of key insights and findings.
- A designated report containing Useful Findings on Churn Dataset.

## Summary of Findings


- The highest possible yield on any loan is 0.492500% on the loaned amount. 0.3% has been most earned by investors, followed closely by 0.15%.
- On some loans, investors earned -0.010%. This means that as an investor, one could end up with losses. 
- The higher an individual's income, the higher the loan amount that can be possibly accessed.
- An investor is likely to have a lower percentage yield as the monthly income of the client increases.
- Home owners are observed to collect significantly higher loan amounts on average, compared to non home owners, however, getting a high loan amount is still possible, without owning a home.
- High risk rated(1.0) individuals were given significantly lower loan amounts compared to higher scored individuals.
- The 36 month loan duration is prefered by individuals across all income ranges.
- The loans of individuals with prosper rating 6 and 7 are the best for loan investment opportunities.
- For both upper and lower credit score, owning a home and having a high credit score range was associated with a better lender yield, compared to individuals who do not own homes and have a lower credit range score.



## Key Insights for Presentation

For the presentation, i will focus on the lender yield and its relationship with other metrics such as credit score, prosper rating, income level and employment status. The lender yield as a single metric may not inform an investor about the best prosper loan to invest in. Combining the lender yield with other known characteristics will help an investor make better choices on what loan to invest in and help the prosper company fund low risk loans.
Prosper Company generates more gains than losses for its investors, making it a viable income source. Its previously generated output will prove this true.