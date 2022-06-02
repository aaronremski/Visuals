## What is the structure of your dataset?
There are 53,940 diamonds in the dataset with 10 features (carat, cut, color, clarity, depth, table, price, x, y, and z). Most variables are numeric in nature, but the variables cut, color, and clarity are ordered factor variables with the following levels.

(worst) ——> (best)
cut: Fair, Good, Very Good, Premium, Ideal
color: J, I, H, G, F, E, D
clarity: I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF

## What is/are the main feature(s) of interest in your dataset?
I'm most interested in figuring out what features are best for predicting the price of the diamonds in the dataset.

What features in the dataset do you think will help support your investigation into your feature(s) of interest?
I expect that carat will have the strongest effect on each diamond's price: the larger the diamond, the higher the price. I also think that the other big "C"s of diamonds: cut, color, and clarity, will have effects on the price, though to a much smaller degree than the main effect of carat.

# Univariate Exploration
I'll start by looking at the distribution of the main variable of interest: price.



## Structure of Dataset summarized
* ~114,000 records with 81 characteritics on completed, defaulted, current, & other types of bank loans. The dataset contains numerous types, e.g. dates, numerals, categories, bools, etc.  <br>

### Noteable Features
IncomeRange, Term, LoanStatus, BorowerAPR, BorrowerRate,  LenderYield, EstimatedEffectiveYield, EstimatedLoss, EstimatedReturn, ProsperRating (numeric), ProsperRating (Alpha), ProsperScore, ListingCategory (numeric), BorrowerState, Occupation, ExmploymentStatus, ExmploymentStatusDuration, CloseDate, 

### Assessing Dataset

* Roughly 20 features can be removed to make it easier to manage the data <br>
* 4 (features)variables express dates, e.g. ListingCreationDate, ClosedDate, DateCreditPulled, LoanOriginationDate. Convert to datetime type<br>
* Several (variables)columns types need to be converted, e.g. CreditGrade, ProsperRating (Alpha), IncomeRange to ordered categorical type<br>