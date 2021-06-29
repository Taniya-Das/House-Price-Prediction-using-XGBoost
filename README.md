# House_Price_Prediction_using_XGBoost


The project predicts house price using dataset based on Melbourne Houses.   
XGBoost is used for making predictions. XGBoost stands for extreme gradient boosting, where gradient boosting is implemented with several additional features focusing on performance and speed. With careful parameter tuning, it is capable of training highly accurate models.   
Pipeline method is used to bundle data cleaning and modelling steps.


## Data

The dataset consists details about [Melbourne Housing](https://www.kaggle.com/dansbecker/melbourne-housing-snapshot). It has 13580 entries and each entry has 21 features.   
Features include Address, Type of Real estate, Suburb, Method of Selling, Rooms, Price, Real Estate Agent, Date of Sale and distance from C.B.D.
Target Variable 'Price': Price in dollars 

## Conclusions

Predictions XGBoost yielded better accuracy than Random Forest Regression model. The predictions on test data are submitted to the [Housing Prices Competition on Kaggle](https://www.kaggle.com/c/home-data-for-ml-course). The Mean Absolute Error on predictions of test data is reported as 14951.28888.

## Reference

Thanks to Kaggle for putting out a wonderful [tutorial](https://www.kaggle.com/alexisbcook/xgboost) on XGBoost. 
