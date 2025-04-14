# Dynamic Asset Allocation with Macroeconomic-Informed Neural Networks
### Max Cernosia, Armaan Pruthi

#### Background:

In this project we explore a machine learning approach to dynamic asset allocation between two risky assets, a market stock and bond index. Using a MLP the model learns to predict the optimal stock allocation proportion based on a range of relevant macroeconomic indicators and recent index return statistics. The target allocation is derived from maximizing the sharpe ratio over a rolling historical window, simulating an investor's goal of achieving the best risk-adjusted return month over month.

In addition to using observed macroeconomic indicators as inputs, this project incorporated time series models to forecast future economic conditions. Autoregressive (AR) and moving average (MA) models were fit to several key indicators including inflation, interest rates, and unemployment, using rolling historical windows. These forecasted features are then used as inputs into our MLP model to predict the optimal asset allocation over a longer horizon to accomodate investors who are interested in less frequent portfolio rebalancing. 

