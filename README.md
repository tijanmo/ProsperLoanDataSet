# PROSPER LOAN DATA EXPLORATION.
## by (TIJANI MOHAMMED)


## Dataset

There are 68943 records with 19  variables of interest to be used in this exploration a after initial data wrangling and cleaning.

Some wrangling acts include merging duplicated credit gradings(Alpha), removed outliers, renamed some data types.

The variables are in two categories numerical and categotical:


num_vars = ['LoanOriginalAmount', 'Term','BorrowerRate', 'LenderYield', 'InterestandFees','TotalProsperLoans', 'ProsperScore', 'Investors', 'StatedMonthlyIncome','AvailableBankcardCredit', 'DebtToIncomeRatio', 'AvgCreditScore']


cat_vars = ['ListingCategory', 'LoanStatus',  'CreditGrade', 'Occupation', 'IsBorrowerHomeowner', 'BorrowerState']

CreditGrading is ordered with the order from highest to lowest being : AA, A, B, C, D, E, HR, NC.

Prosper Score is also ordered from 1 to 10 with 10 being highest.


##  Summary of Findings

Borrower Rate and Lender Yield are highly correlated.

Both BorrowerRate and LenderYield are inversely correlated with Prosper Score.

Income has a correlation with Loan amount but not very strong. 

No relation between term vs  interest rate/yield. Only correlation for Term is LoanOrginal amount.

There is a negative relation betwwen loan amount and lender yield. Bigger loans translates to bigger yields.

There is a positive but weak relation between loan amount and number of investors.

There is a negative but weak correlation but loan amount and number of total number of previous loans.

There is also a negative correlation between yield and loan amount given and so with interest rate. 

Prosper Score has a postive correlation with Investors, BankCredit, Avg Credit and inverse relation to debt 

Most defaulted Loans have higher interest rates. 

Most defaulted Loans were mostly by Borrowers with lower stated Monthly income.

Positive correlation between credit grading and prosper score and both with an inverse relationship with interest rate.

Amongst the few deafulting loans, people from CA default the most.

Occupation with highest income are Executive, Sales Commission, proffesors.

Homeowners averagely have a good credit rating than no homeowners and also lesser interest rates.

Homeowners also get higher loan amounts than no home owners.


## Key Insights for Presentation

For the presentation, I focus on ::

1. Relationship between credit ratings and interest  rates. 

2. Relationship between loans  amounts and  yields. 

3. Credit Grading and Prosper Score.

4. Loan Term doesnt affect interest rates.

5. Most defaulted Loans were mostly by Borrowers with lower stated Monthly income, poor credit ratings and  hence higher interest rates.
 
