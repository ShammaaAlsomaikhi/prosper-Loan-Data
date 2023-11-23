# Loan Data From Prosper
## by Shamma'a Alsomaikhi


## Dataset

> Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

The Loan Data from Prosper dataset comprises 113,937 loans, each with 81 variables. These variables include loan amount, borrower rate (interest rate), current loan status, borrower income, and various other attributes.

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. See this data dictionary[https://docs.google.com/spreadsheets/u/0/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing] to understand the dataset's variables.

This dataset was provided in the "Choose Your Dataset" section of the Communicate Data Findings project in the Udacity Data Analysis Nanodegree.

The variables in the dataset follow a relatively normal distribution, showing no notable outliers or unusual points. Through visualizations and calculations of central tendency and spread, no extreme values or data points significantly deviating from the overall distribution were detected. Consequently, no transformations or adjustments were deemed necessary for this analysis.

However, the following actions were undertaken:
- Elimination of attributes deemed unhelpful for the analysis.
- Removal of duplicate entries.
- Renaming the 'ListingCategory (numeric)' column to 'ListingCategory'.
- Conversion of 'LoanOriginationDate' and 'ClosedDate' columns to date types.

## Summary of Findings

- The main features of interest include exploring the correlation between the borrower's income range and the loan amount, investigating the relationship between Borrower Rate and Prosper Score, and analyzing the distribution of loan categories.

- Loan terms are predominantly 36 months (medium-term), followed by 60 months (long-term) and 12 months (short-term).

- Most borrowers are employed, with the majority having lower ratings. Among employed borrowers.

- A strong positive correlation exists between BorrowerAPR and BorrowerRate.

- Stated Monthly Income and Loan Original Amount exhibit a moderately positive correlation.

- The correlation between BorrowerAPR and Loan Original Amount is moderately negative.

- BorrowerAPR and ProsperScore show a moderately negative correlation.

- A negative correlation is observed between Prosper Score and Borrower Rate.

- Individuals with a higher income range tend to secure larger loans with longer terms.


## Key Insights for Presentation

In this exploration, I aim to delve into various aspects of the dataset to understand the relationships and patterns associated with key features. The primary focus is on exploring how the borrower's income range correlates with the loan amount, investigating the interplay between Borrower Rate and Prosper Score, and analyzing the distribution of loan categories and the distribution of loan categories based on LoanOriginalAmount, Term , BorrowerRate.
