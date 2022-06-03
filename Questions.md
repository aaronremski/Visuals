# Prosper Loan Data - Questions to ask of the data

## Potential Questions to consider in the analysis


1. What are common characteristics of borrowers who have high interest rate, or default, or certain occupation?
2. Are there any indicators in the data showing the 2007-09 crash/correction?
3. Are there any indicators in the data showing signs that 2007-09 was coming? What's the range of dates?
4. What kinds of relationships do you expect to find? </br>
    a. higher creditscores get lower interest rates </br>
    b. high credit scores have higher rate of completion(repayment) </br>
    c. low debt to income ratio correlates to higher IncomeRange </br>
5. Is there a consistent delta between BorrowerAPR & BowwowerRate?


## Variables looking to explore further

1. DebtToIncomeRatio
2. IncomeRange
3. StatedMonthlyIncome
4. ProsperRating (alpha)
5. CreditGrade
6. PastDue (lengths)
7. CreditScoreRangeLower
8. CreditScoreRangeUpper
9. MonthlyLoanPayment
10. LoanOriginalAmount

## Univariate Exploration & Findings
### Numerical & Visual Inspection of:

1. IncomeRange
2. ProsperRating (Alpha)
3. LoanStatus </br>
    a. Past Due</br>
    b. Defaulted/Chargedoff (Failed)</br>
    c. Completed (Successful)
4. LoanAmount
5. BorrowerRate
6. CreditGrade

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
