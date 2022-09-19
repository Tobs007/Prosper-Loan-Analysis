# Prosper-Loan-Analysis
This project investigate the major features that determines Borrowers APR and factors that contributes to a loan outcome.

## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be found at this link [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), and features documentation can also be found at this link [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

In the data exploration, I observed a very strong positive correlation between Borrower APR and Borrower Rate, Lender Yield, Estimated Loss, and Estimated Return, there was also a strong positive relationship between Borrower Rate and Lender Yield, Estimated Loss and Estimated Return, while there is a negative correlation between the Borrower APR and Investors, Estimated Loss, and Loan Original Amount

I also observed that ProsperRating (Alpha) appears to be a significant determinant of Borrower's APR, with APR being highest for Borrowers in the HR rating category and lowest in the AA rating category. There is a very strong positive correlation between Borrowers APR, Lender Yield, and Prosper Rating.

I verified the relationship further and found a strong relationship T between Borrowers APR, Lender Yield, and Prosper Rating. Correlation is at the highest when Borrowers APR and Lender Yield are less than 0.15.

It is also worth noting that a lot of the borrowers were from California, and the APR rate for loans received by Students in Technical school was very low suggesting the loan might have been backed by the government. Debt consolidation was rated as the highest reason for borrowing.



## Key Insights for Presentation

For this presentation, My focus is to determine what affects a borrower’s APR or interest rate, and if there was any difference between loans depending on how large the original loan amount was and other factors that could influence loan outcome. 

I focus on finding the relationship and correlation between Borrowers Rate, Employment Status, Income Status, and Prosper Rating on Borrowers APR. 

I start by introducing Borrowers APR, Loan Status, and Listing Category by showing the pattern of the distribution using histograms and bar plots.

Afterward, I introduce some of the categorical variables to show their influence or relationship using box plots and a scatterplot matrix. I focused on showing the relationship between Borrower APR and some of the categorical datasets. I then proceed to show the relationship between Lender Yield vs Borrower APR  vs ProsperRating (Alpha), the relationship between Loan Status Vs Borrower APR in each Employment Status, and lastly the relationship between Loan Status vs Borrower APR vs Income Range.

I've made sure to use different color palettes for each Prosper Score rating,  Employment Status, or Income Range to make sure it is clear that they're different between plots.

