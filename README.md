# Cryptocurrency Project Analysis:  Replicating Financial Modeling Skills in Excel

This repository documents a data analysis project performed entirely in Microsoft Excel, aimed at replicating financial modeling techniques using a cryptocurrency dataset. The analysis explores various aspects of the project's performance, user behavior, and financial implications.

## Dataset

The dataset used in this analysis contains information on various key metrics of a cryptocurrency project, including:

* **Token Price (USD):** The price of the token in US dollars.
* **Unique Wallets:** The number of unique wallets interacting with the project.
* **Staking Participants:** The number of users participating in staking.
* **Txn Fees (USD):** Total transaction fees generated in US dollars.
* **Liq Pool Size (USD):** The size of the liquidity pool in US dollars.
* **APY:** Annual Percentage Yield for staking rewards.
* **FV of Rewards (USD):** Future Value of staking rewards.
* **PV of Rewards (USD):** Present Value of staking rewards.
* **Liq Pool Utl Ratio:** Liquidity Pool Utilization Ratio.
The data, provided in an Excel spreadsheet [here]([data.xlsx](https://github.com/JoeAkpan28/Financial-modelling-1/blob/main/Fin.%20model%201.xlsx)), spans a period of time, allowing for analysis of trends and growth rates.


## Analysis Objectives

This project aims to test and demonstrate financial modeling skills in Excel by addressing the following key questions:

* **Transaction Volume and Fees:** Determine the relationship between transaction volume and transaction fees using regression analysis (implemented via Excel's built-in functions or add-ins).
*	**User Adoption, Trading Volume, and Token Price:** Analyze the impact of unique wallets (user adoption) and transaction volume on the token price using multiple regression analysis (Excel's built-in functions or add-ins).
* **Staking Participation Prediction:** Build a predictive model to estimate the likelihood of a user participating in staking based on transaction volume and the number of unique wallets. Logistic regression can be approximated using Excel's functions or add-ins.
* **Present Value of Staking Rewards:** Calculate the present value of future staking rewards for users, assuming a specified discount rate and projected future rewards using Excel's financial functions (e.g., PV).
* **Liquidity Provider Optimization:** Develop an optimization model to determine the optimal allocation strategy for liquidity providers, considering liquidity pool size and other relevant metrics. Solver add-in may be used for this.
* **User Migration Modeling:** Simulate user migration between different DeFi protocols using Excel's capabilities for creating and analyzing state transition matrices.
* **Token Price Fluctuation Probability:** Estimate the probability of token price fluctuations using historical data and potentially time series analysis techniques adapted for Excel.
* **Transaction Success Probability:** Analyze the probability of successful transactions, assuming a given probability of success for each transaction using Excel's probability functions.
* **Failed Transaction Modeling:** Model the number of failed transactions using a binomial distribution, defining success/failure criteria and using Excel's statistical functions.
* **Transaction Size Distribution:** Describe the distribution of transaction sizes by calculating the mean and standard deviation of transaction volume and applying the empirical rule using Excel's statistical functions.



## Methodology

The analysis employs various statistical and modeling techniques implemented within Microsoft Excel, including:
-	Regression analysis (linear, multiple, and logistic approximations)
-	Present value calculations
-	Optimization
-	Custom formulas and functions for specific calculations
-	Descriptive statistics
Specific details of the methodology used for each analysis objective are documented within the Excel workbook itself using comments and worksheet descriptions.

## Excel Workbook

The main analysis is contained within the workbook [here]([analysis.xlsx](https://github.com/JoeAkpan28/Financial-modelling-1/blob/main/Fin.%20model%201.xlsx)). Each sheet corresponds to a specific analysis objective.


## Results and Conclusions

The results of the analysis, including key findings, charts, and interpretations, are presented within the workbook [here](analysis.xlsx).

## Dependencies

This project requires Microsoft Excel with potentially the Solver add-in and the Data analysis Toolpack
