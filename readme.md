# Prosper loans dataset Investigation
## by (Ahmed Metwalli)


## Dataset

> The data includes peer to peer loans provided by credit company Prosper. Dataset of shape [113937,81] is provided. During the investigation, these features [Term, LoanStatus, BorrowerRate, ProsperRating (Alpha), ListingCategory (numeric), EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans, LoanOriginalAmount, LoanOriginationDate, Recommendations, Investors] are taken into account.


## Summary of Findings

> 'ProsperRating (Alpha)' distribution is taking the normal distribution shape. On the other hand, the distribution of 'StatedMonthlyIncome' has a high variability, containing many outliers, a very large range of values. In addition, most loans are below $15,000 and loans are somehow increments of $5,000. Also, Prosper rating D is the most common rating among 'Defaulted' credits.
> Individuals with lower rating are having more'Defaulted'. Business and home improvement are more riskier than other categories. Most of the times, the borrower rate tends to be higher for 'Defaulted' credits. In terms of months, long term (60 months) credits is not preferable by the most as it is riskier than short or mid term loans. Interestingly, the borrower rate for individuals with low rating is high. Usually, high 'StatedMonthlyIncome' leads to higher rating. In the end, 'EmploymentStatus' of lower rating individuals are biased to be in the 'Not employed', 'Self-employed', 'Retired', 'Part-time' categories of employment status.
> 'Defaulted' credits tend to be larger than 'Completed' for all 'ProsperRating (Alpha)' except the lower ones.


## Key Insights for Presentation

> The high data-to-ink ratio plots are preferred in visualizations. The plots done during the project shows the distribution of the key features [LoanStatus, StatedMonthlyIncome, ProsperRating (Alpha)].
The story told is about what are the major predictors for LoanStatus and ProsperRating (Alpha) features.