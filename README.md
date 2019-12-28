# Weather-Prediction-for-Kochi-
This work is to study weather prediction on dataset of "Kochi" - a city in Indian southwest coastal state Kerala.
Two models were trained - 
1. Linear regression with lasso regularization - It seems that weather parameters are not linearly dependent on each other. RMSE for each parameters were very high. During training, there occured convergence issue for some of the parameters.
2. A deep learning non-linear model with LeakyReLU - The results of Deep learning model is quite satisfying with RMSE for each parameter less than one.

Both models were trained on dataset whose source is https://www.visualcrossing.com/ 

Data set contains 12 quantitative parameters. Dependency of each parameter on rest 11 was studies in this model.

Future Work - 1. Dependency of each parameter can be studied by sequentially removing one by one independent variables. This would help                    was to minimize our efforts in data collection as lesser number of data will have to be collected.
              2. Prediction using time series analysis.
28/12/2019
Time series prediction using LSTM has been carried out and can be seen in file "KochiWeatherPrediction_LSTM". RMSE obtained are at satisfactory level but any improvement will be welcomed. It an attempt for improvement, supervised timeseries analysis would be carried out next.
