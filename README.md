# Dynamic Asset Allocation using Machine Learning: A Sharpe Maximization Approach
### Max Cernosia, Armaan Pruthi

#### Background:

In this project we explore a machine learning approach to dynamic asset allocation between two risky assets, a market stock and bond index. Using a MLP the model learns to predict the optimal stock allocation proportion based on a range of relevant macroeconomic indicators and recent index return statistics. The target allocation is derived from maximizing the sharpe ratio over a rolling historical window, simulating an investor's goal of achieving the best risk-adjusted return month over month.

In addition to using observed macroeconomic indicators as inputs, this project incorporated time series models to forecast future economic conditions. Autoregressive (AR) and moving average (MA) models were fit to several key indicators including inflation, interest rates, and unemployment, using rolling historical windows.

