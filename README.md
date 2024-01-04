# DA3-Python-Codes

Coding classes in Python for Data Analysis 3 on MSc in Business Analytics on the Central European University.

The notebooks are slightly modified versions of the [case studies](https://github.com/gabors-data-analysis/da_case_studies) for the [Bekes - Kezdi Data Analysis textbook](https://gabors-data-analysis.com/).

## Contents

1. class 13, used cars  
Basic data manipulation and exploratory data analysis.<br>
Basic visualizations using plotnine (ggplot) and seaborn.<br>
Multiple linear regression using `statsmodels`.<br>
Model selection by goodness-of-fit metrics.<br>
Cross-validation and model comparison.<br>

2. class 14, airbnb<br>
Handling missing data; integrating missing data information in the analytics.<br>
Model setup.<br>
Interactions & dummies.<br>
Train, test & holdout sets.<br>
Cross-validated train & test metrics.<br>
LASSO: optimization and interpretation. Naive cv and cv using `sklearn` gridsearch.<br>
Diagnostics on the holdout sets.<br>
Plotting regression results.

3. class 15, used cars<br>
Basic regression trees.<br>
Plotting trees and regression results as plot functions.<br>
Building more complex regression trees with control parameters.<br>
Pruning.<br>
Comparing tree-based and OLS models.<br>
Variable importance.<br>

4. class 16, airbnb<br>
Random forest.<br>
Feature importances: standalone and grouped.<br>
Partial dependence & RMSE for subsets of data.<br>
Comparing OLS, LASSO, CART, and random forest.<br>
Gradient Boosting Machines: tuning and model run.<br>

5. class 17, bisnode<br>
Modelling probabilities with simple & lasso logit.<br>
CV RMSE & AUC for probability models.<br>
Classification using logit with no loss function.<br>
Calibration plot, confusion matrix, ROC, AUC.<br>
Classification (logit) with user-defined loss function
Classification with CART.<br>
Random forest for probabilities, with and without a loss function.<br>
Classification with random forest.<br>

6. class 18, swimming pool, Case-Shiller<br>
Managing time series data with the tsibble package<br>
Deterministic modelling: OLS, trend, seasonal & other dummies<br>
Introducing `fbProphet`<br>
Stochastic modelling with the fable package<br>
ARIMA, auto-arima<br>
Vector Autoregressions<br>
