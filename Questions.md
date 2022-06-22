# Prosper Loan Data - Questions to ask of the data

## ------------------------------------------------------------------------------------------------

_Current Analysis Questions in 'Prosper Loan Data Exploration' notebook_

## This analysis will explore:
1. What are some common characteristics of 'successful' (completed) vs 'failed' (defaulted & chargedoff) loans?
2. Are there any surprising characteristics of 'successful' or 'failed' loans?

3. What are common characteristics of borrowers who have high interest rate, or default, or certain occupation?
4. Do some of the expected/obvious relationships check out? 
    a. higher creditscores correlate with lower interest rates
    b. high credit scores have higher rate of completion(repayment)
    c. low debt to income ratio correlates to higher IncomeRange

5. Are there differences between loans made before the subprime crash in 2008?
    a. Dec 22, 2005, yield curve for US Treasurys inverts.
    b. These loans originated at the beginning of the subprime crash in 2008



## Features in the dataset that will help support the investigation
1. LoanStatus 

## ------------------------------------------------------------------------------------------------

Current Notes for going to submittal ASAP while still being creative

## ------------------------------------------------------------------------------------------------

## Potential Questions to consider in the analysis


1. Are there any interesting trends or features of people who share the same occupation?</br>
    A. Occupation vs:
            a. InterestRate
            b. Types of Loans
            c. DebtToIncomeRatio
2. Are there any indicators in the data showing the 2007-09 crash/correction?
3. Are there any indicators in the data showing signs that 2007-09 was coming? 
4.
5. What kinds of relationships do you expect to find? </br>
    A. higher creditscores get lower interest rates </br>
    B. high credit scores have higher rate of completion(repayment) </br>
    C. low debt to income ratio correlates to higher IncomeRange </br>
6. Is there a consistent delta between BorrowerAPR & BowwowerRate?


## Features/Variables required to explore questions?

1. LoanStatus
2. IncomeRange
3. StatedMonthlyIncome
4. IncomeBracket
4. ProsperRating (alpha)
5. CreditGrade
6. PastDue (lengths)
7. CreditScoreRangeLower &bCreditScoreRangeUpper
8. MonthlyLoanPayment
9. LoanOriginalAmount
10. DebtToIncomeRatio

## Univariate Exploration & Findings
### Numerical & Visual Inspection of:

1. IncomeRange
2. ProsperRating (Alpha)

*Bivariate case: Occupation v. LoanStatus*
3. LoanStatus </br>
    a. Past Due</br>
    b. Defaulted/Chargedoff (Failed)</br>
    c. Completed (Successful)
    
4. LoanAmount

*Bivariate case: Occupation v. BorrowerRate*
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
