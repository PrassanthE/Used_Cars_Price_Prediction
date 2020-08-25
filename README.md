# Used_Cars_Price_Prediction
### Capstone Project

### Summary:
A car price prediction has been a high interest research area, as it requires noticeable effort and knowledge of the field expert. Considerable number of distinct attributes are examined for the reliable and accurate prediction. To build a model for predicting the price of used cars in Germany, machine learning techniques like multiple linear regression, ridge regression, lasso regression, elastic net regression, decision tree regressor, random forest regressor, KNN regressor, gradient boosting and artificial neural networks were applied. The predictions are based on data scraped from used car listing on Ebay-Kleinanzeigen (German), retrieved from Kaggle (https://www.kaggle.com/orgesleka/used-cars-database#autos.csv). Respective performances of different algorithms were then compared to find one that best suits the available data set.

### Conclusion:

KNN Bagging Regressor proved its capability in generating a good prediction model with a better trade-off between bias and variance error. With hyper parameter tuning using grid search CV, it showed a better accuracy than the standard solution, multiple linear regression. Therefore, KNN Bagging Regressor was chosen as the final model.
