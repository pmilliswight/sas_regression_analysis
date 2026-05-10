# Stock Price Prediction: Multiple Linear Regression in SAS

Built and refined a multiple linear regression model predicting Royal Caribbean 
(RCL) daily stock price from S&P 500 Consumer Discretionary components using SAS.

Full workflow: variable selection (stepwise, R², Cp, PRESS), interaction and 
second-order term testing via nested F-test, multicollinearity detection and 
removal via VIF, residual diagnostics, and studentized residual analysis.

Final model (R² adj = 0.981) identified 10 significant predictors across 
retail, automotive, and travel sectors.

Tools: SAS (PROC REG, PROC GLMSELECT, PROC UNIVARIATE, PROC CORR)
Course: STP 429 — Applied Regression, ASU (Spring 2024)
