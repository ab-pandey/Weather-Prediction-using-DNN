# Weather-Prediction-for-Kochi-
This work is to study weather prediction on dataset of "Kochi" - a city in Indian southwest coastal state Kerala.
Two models were trained - 
1. Linear regression with lasso regularization - It seems that weather parameters are not linearly dependent on each other. RMSE for each parameters were very high. During training, there occured convergence issue for some of the parameters.
2. A deep learning non-linear model with LeakyReLU - The results of Deep learning model is quite satisfying with RMSE for each parameter less than one.

Both models were trained on dataset whose source is https://www.visualcrossing.com/ 
