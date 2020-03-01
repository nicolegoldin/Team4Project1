# CollaborativeProject1
Project 1 Repository- Team 4

## Team
Roger C. Hahn
Brody Wacker
Nicole Goldin
Evinski Benjamin
Lucas Gowland


## Project

The CAPM model is unable to properly explain the returns on common stock above the risk free rate as it does not account for the effect that outside characteristics not including cash flow/price, boot-to-market, short term returns, etc account for. Utilizing 3 new variables, the Fama French Model is able to account for a large number of the returns not accounted for in a CAPM model. The Fama French Model utilizes premiums, the differences in high and low BE/ME portfolios, and SMB/ HML variables to create a model more representative of returns.
“Previous work shows that average returns on common stocks are related to firm characteristics like size, earnings/price, cash flow/price, boot-to-market-equity, past sales growth, long-term past returns, and short-term past returns. Because these patterns in average returns apparently are not explained by the CAPM, they are called anomalies. We find that, except for the continuation of short-term returns, the anomalies largely disappear in the three-factor model. Our results are consistent with rational ICAPM or APT asset pricing, but we also consider irrational pricing and data problems as possible explanations”.

Modern portfolio theory (MPT) is a theory on how risk-averse investors can construct portfolios to optimize or maximize expected return based on a given level of market risk, emphasizing that risk is an inherent part of higher reward. According to the theory, it's possible to construct an "efficient frontier" of optimal portfolios offering the maximum possible expected return for a given level of risk. This theory was pioneered by Harry Markowitz in his paper "Portfolio Selection," published in 1952 by the Journal of Finance. He was later awarded a Nobel prize for developing the MPT.

Modern portfolio theory argues that an investment's risk and return characteristics should not be viewed alone, but should be evaluated by how the investment affects the overall portfolio's risk and return.

MPT shows that an investor can construct a portfolio of multiple assets that will maximize returns for a given level of risk. Likewise, given a desired level of expected return, an investor can construct a portfolio with the lowest possible risk. Based on statistical measures such as variance and correlation, an individual investment's return is less important than how the investment behaves in the context of the entire portfolio.

Once the expected return is determined through the three-factor model, we will create an optimal efficiency frontier using the Harry Markowitz portfolio efficiency frontier model. 


## Guide

Initial data was obtained from IEXfinance and explored and cleaned in stock_picking.ipnyb. However, to run the analysis, stock_picking.ipnyb is not required as the stocks are hard coded into the subsequent blocks of code as explained below. 

To run the code yourself, first execute selection_criteria_FINAL.ipnyb to obtain universe of 100 stocks selected at random from the SP500. The code will identifies the top ten sharpe ratios and PE ratios and pickles the data. The plots are saved as png files.

Next, execute ffm_regression2_FINAL.ipnyb to obatin more accurate expected returns of the top ten stocks. Data is pickled and plots are saved as png files.

Execute Efficient_Frontier_FINAL.ipnyb to obtain the portfolios. The efficient portfolios are on the curve. 

Finally, execute dashboard_FINAL.ipnyb to see all data in one file.

## Next Steps

A sensitivity analysis and a Monte Carlo showing future returns on each plot can be calculated to determine if our hypothesis is correct. To be continued ...

