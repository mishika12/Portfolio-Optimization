## Portfolio-Optimization

### <ins> Introduction
In modern finance, optimizing a portfolio is essential for minimizing risk while meeting expected return targets. This process involves allocating investments among various assets to achieve a desired return with the least risk. This project focuses on solving portfolio optimization problems using quadratic programming techniques to determine optimal asset allocations under different constraints and scenarios.

### <ins> Problem Statement
The objective of this project is to construct minimum-variance portfolios under different constraints and investment scenarios. Specifically, it involves three models:

1. Model 1: Optimizing a portfolio consisting of only four specific stocks to achieve a minimum variance with an expected monthly return of at least 0.5%  
2. Model 2: Extending the optimization to a broader set of 390 stocks, aiming for a minimum variance portfolio with the same return constraint  
3. Model 3: Incorporating transaction fees by limiting the number of stocks in the portfolio to a maximum of four, while still achieving a minimum variance and an expected monthly return of at least 0.5%  

### <ins> Methodology
Data Preparation: Calculate monthly returns and the covariance matrix for the stocks using historical price data provided in the Prices.csv file

Model Formulation

Comparison of Risks
