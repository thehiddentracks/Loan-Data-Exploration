# Loan Data Exploration

## by Robert Weber


## Dataset

This exploration is based on a dataset from online loan marketplace "Prosper",
containing 113,937 loans associated with 81 variables on each loan.

The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)
Additional explanation on the various features can be found [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000)


## Summary of Findings

The exploration showed that there is a relationship between the Borrower APR and the 
Loan amount, as well the APR and the Trades never delinquent feature. Other features 
influencing the Borrower APR are the Prosper scoring, the Term for a loan, the Employment 
status as well as the home ownership.
A higher loan amount is associated with a lower APR, while a low percentage in Trades 
never delinquent is associated with a higher APR.
The scoring provides a clear demarcation between different borrower rates and shows that 
the rates go up with wosening scores, while being in the lowest rates with better 
scoring (AA).
I discovered a lightly better APR if owning a house and being employed or retired. 
The previous finding about the lower APR with rising loan amount was added the employment 
status and I discovered that the rates are getting lower for employed and retired borrowers 
the higher the loan amount, but the rates are getting higher for larger loans for unemployed 
borrowers. 
Additionally unemployed borrowers only could get better APR conditions with longer loan 
runtimes, while still paying higher APR than employed or retired borrowers.


## Key Insights for Presentation

I first start by introducing the Borrower APR as feature of interest and will then continue 
with introducing the influencing features. I hereby start with the distribution of the loan 
amount, followed by the employment status, that will be cleaned in terms of merging values 
and removing values.
Additionally I will plot the distribution of the Prosper rating as a boxplot, as this feature 
shows most prominently its influence on the Borrower APR. 

Then I will continue in adding the employment status to a comparison between the loan amount 
and Borrower APR within a scatterplot. I will end with a boxplot showing the correlation 
between the employment status, the loan term and their influence in the Borrower APR.
