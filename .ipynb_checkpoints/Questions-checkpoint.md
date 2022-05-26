# Prosper Loan Data - Questions to ask of the data

## Communicate Data Finding example questions

1. What factors affect a loan’s outcome status? Must have application info to better arrive at these answers.
2. What are common characteristics of borrowers who have high interest rate, or default, or certain occupation?
3. Are there any indicators in the data showing the 2007-09 crash/correction?
4. Are there any indicators in the data showing signs that 2007-09 was coming? What's the range of dates?
5. What kinds of relationships do you expect to find?
    a. higher creditscores get lower interest rates
    b. high credit scores have higher rate of completion(repayment)
    c. low debt to income ratio correlates to higher IncomeRange
    
## Variables looking to explore further

1. DebtToIncomeRatio
2. IncomeRange
3. ProsperRating (alpha)
4. CreditGrade
5. PastDue (lengths)
6. CreditScoreRangeLower
7. CreditScoreRangeUpper
8. MonthlyLoanPayment
9. LoanOriginalAmount

## Univariate Exploration & Findings
### Numerical & Visual Inspection of:

1. IncomeRange
2. ProsperRating (Alpha)
3. LoanStatus
4. LoanOriginalAmount (2 plots)
5. Credit Grade (all loans)
9. LoanStatus - Loans that are in a "Past Due #days" status

1. Very peculiar - a disproportionate number of loans are made with 31% BorrowerRate & 36% BorrowerAPR

## Bivariate Exploration & Findings
### Numerical & Visual Inspection of:

1. Credit Grades (Loans < 5000) vs. Credit Grades (Loans > 5000)
2. LoanStatus - Defaulted vs. Chargedoff
3. BorrowerRates (Failed Loans) distribution vs. BorrowerRates (Completed Loans) distribution
4. Faceted CreditGrade for LoanOriginalAmount

1. Surprisingly, there was no difference in homeownership between completed loans & defaulted loans.
2. 

## Additional (Original) questions

1. Occupation v InterestRate
2. Occupation v Types of Loans
