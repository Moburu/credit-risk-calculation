# credit-risk-calculation

### Credit Risk Analysis Report

The purpose of this analysis is to use linear regression to predict whether a loan will be healthy or high-risk depending on various features of the loan such as interest rate, borrower income, total debt, and so on.

We ran this model on two features - 0 (healthy) and 1 (high-risk) - and these were the results of the classification report:
- Healthy precision: 1.00
- Healthy recall: 0.99
- Healthy f1-score: 1.00
- High-risk precision: 0.84
- High-risk recall: 0.94
- High-risk f1-score: 0.89

In summary, the results are quite positive across the board, but particularly for healthy loans, which the model can predict with near-perfect accuracy. For high-risk loans, the classification report tells us that 84% of the loans which were predicted to be high-risk ended up being so, and 94% of loans that were high-risk were predicted to have been so by the model. Due to this high success rate, I would recommend this model for use with similar datasets.
