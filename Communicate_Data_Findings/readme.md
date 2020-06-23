## Prosper Loan Data Exploration

## Dataset
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, prosper score, and many others.


## Summary of Findings

Out of the features I selected to investigate the factors associated with the Interest Rates and the Loan Status, I found out there is an interesting relationship between the Loan Amount and the Loan Status where the Chargedoff and Defaulted Loans were smaller Amounts. This begs the question of why these small amounts could not be paid off.

The Chargedoff and Defaulted Loans had a higher Interest Rate.

The median Monthly Income of the borrowers was approximately the same for all the Loan Status with Chargedoff and Defaulted loans having a smaller amount.

The Interest Rates reduced as the Loans moved from higher risk (Low Prosper Score values) to lower risk (high Prosper Score values).

Loans taken for 60 or 36 months had the same median Interest Rate but the 36-month loans had a greater number having high-interest rates compared to the 60month Loans.

There was a strong relationship between Interest Rate and BorrowerAPR and this is understandably so because the Interest Rate itself is a component of the BorrowerAPR. A strong relationship was also established between the Interest Rates and the Estimated Loss or Estimated Return.

Most of the Loans were taken for Debt Consolidation. This paints a picture of a people caught in an endless borrowing cycle.

Most of the borrowers were from California.


## Key Insights for Presentation

The distribution of the Interest Rates showed that most the Loans had an Interest Rate between 0.30 and 0.33.
The Chargedoff and Defaulted Loans had the highest interest rates. I combined the Interest Rate, Loan Amount and the Loan Status to understand why smaller Loans ended up being Chargedoff or Defaulted and the clearest explanation suggests that even though the Loans were smaller, the Interest Rates were higher and gives us a hint of the reason why these loans had these statuses.

Defaulted and Chargedoff Loans have high-Interest Rates and lower ProsperScores (high-risk scores). As we move from high risk to low risk along for the Prosper Scores, we observe that the Interest Rates also decrease.