# WebTrafficTimeSeries
Data Analytics Project

To run the code download the dataset(https://www.kaggle.com/c/web-traffic-time-series-forecasting/data) and upload in the folder named Dataset.
All the codes are available in the folder Code.
Source Codes are available in folder Test.
Kaggle Submission Link:https://www.kaggle.com/kashish2801/web-traffic-time-series-forecasting

#Introduction
Web Traffic is defined as the amount of data sent and received by visitors to a website. The analysis of Web Traffic provides many applications. For example, website owners can use the web traffic analysis to determine the popularity of the website or web pages and glean insights on the trend or pattern of traffic. This helps in identifying customer preferences, increasing corresponding utility and hence increasing the revenue of the website.

Time-Series analysis refers to estimating the value of a variable at a given instance based on the values observed previously. This is done using models. Time-Series has many components like trend, seasonality and regularity. A time series where the variance (or amount of variability) is time-invariant (i.e. don’t change from day to day) is called stationary. Forecasting becomes easier and more accurate on stationary time series. There are many models that can be used for Time-Series analysis. When two or more models are stacked, one above the other, an ensemble model is created. This stacking helps increase the overall performance even if the weaker models are used in the ensemble. The performance of a model can be measured using different methods. We have used Root Mean Squared Error (RMSE)

We have implemented 5 models for time series prediction:
1. SARIMAX 
2. RNN and LSTM based model
3. Adaboost Regressor
4. Gradient Descent Regressor
5. Random Forest Regressor
