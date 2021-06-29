# House Price Prediction using XGBoost


The project predicts house price using dataset based on Melbourne Houses.   
XGBoost is used for making predictions. XGBoost stands for extreme gradient boosting, where gradient boosting is implemented with several additional features focusing on performance and speed. With careful parameter tuning, it is capable of training highly accurate models.   
Pipeline method is used to bundle data cleaning and modelling steps.


## Data

The dataset consists details about [Ames, Iowa Housing](https://www.kaggle.com/c/home-data-for-ml-course/data). Each entry is described using 79 features.   
Target Variable: 'SalePrice' (property's sale price in dollars).

## Conclusions

Predictions XGBoost yielded better accuracy than Random Forest Regression model. The predictions on test data are submitted to the [Housing Prices Competition on Kaggle](https://www.kaggle.com/c/home-data-for-ml-course). The Mean Absolute Error on predictions of test data is reported as 14951.28888.

## Reference

Thanks to Kaggle for putting out a wonderful [tutorial](https://www.kaggle.com/alexisbcook/xgboost) on XGBoost. 
