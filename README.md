# Microsoft-Stock-Prediction-Analysis

## Analysis and Prediction of Stock Return on Microsoft stock prices over the Past 5 Years

1. Summary statistics of the training period we have selected. 
2. We have used the features/factors discovered from sources like e.g. FRED, Fama-French website, ADS, AR, CAPM, momentum factors, volume, price/return lags, etc. to construct a feature database that may have an influence on the stock prices.
3. The target variable Y is the returns of MSFT Stock price. The frequency considered is daily.    
5. Virtualized the feature importance and feature selection using regression-based approaches (Ridge regression, LASSO, Elastic Net or LARS) and decision tree-based approach (random forest, XGBoost). 
6. Proposed and trained 6 models by feeding in the features we have prepared in step 2.
7. Compare the model performance using RMSE between the fitted Y and actual Y in the testing period. 
8. Included one benchmark study that uses Kalman Filter.
6. We have also included trading rules e.g. buy-and-hold, long-short, or day trade. 
7. Generated trading signals using the above 6 models. Compared their PnL.  
