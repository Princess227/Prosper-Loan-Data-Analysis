# Prosper Loan Data

## by Princess Obazee


## Dataset

>This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


## Summary of Findings

>Stated Monthly Income and Monthly Loan Payment were transformed using a log scale to interprete the distribution because they were right skewed. The transformation showed that most borrowers monthly income was within the range of \\$4000 to \\$6000. Most borrowers tend to pay between \\$100 and \\$400 as monthly loan payments for their loans.

>DelinquentBucket is a categorical variable created using the LoanCurrentDaysDelinquent to get the frequency of the Loans that have passed the due day. This revealed that majority of the borrowers fall within the Past Due (>180 Days) delinquency.

>There is a negative correlation between the BorrowerRate and LoanOriginalAmount, which means the higher the loan amount, the lower the BorrowerRate. Borrowers with the best Prosper ratings have the lowest BorrowerRate. This indicates Prosper rating has a strong effect on BorrowerRate. Borrowers with better rating also have higher monthly income and loan amount.

>The LoanOriginalAmount is positively correlated with the StatedMonthlyIncome. This is reasonable because the higher your income the higher the loan amount you can borrow. There is a relation between Term and ProsperRating (Alpha). Borrowers with C rating have the highest number in 36 and 60 month loans while borrowers with AA rating have the least number in 36 and 60 month loans. Borrowers with the least credit rating, HR do not take 60 month tenured loan. AA rated borrowers have the least count in Past Due(>180 Days) DelinquencyBucket.


## Key Insights for Presentation

> For the explanatory analysis, the main focus was the features that could affect the BorrowerRate, which are LoanOriginalAmount, ProsperRating (Alpha), Term, and StatedMonthlyIncome. I started by showing the distribution of BorrowerRate and LoanOriginalAmount. Then, I explored the relationship between BorrowerRate and LoanOriginalAmount, BorrowerRate and ProsperRating (Alpha), the relationship between BorrowerRate and LoanOriginalAmount by ProsperRating (Alpha) as well as BorrowerRate and ProsperRating (Alpha) by Term.
