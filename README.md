# Predict-the-Click-Through-Rate-for-Keywords-Using-Machine-Learning-Methodologies

# Problem Description:
An advertising company sells a service of buying keywords in search engines on behalf of their customers. They're trying to optimize their keyword and funds allocation. The first towards the optimal solution is to predict performance by keyword and fund. 

# Goal: 
Predicting for any keyword (not necessarily the ones in the dataset file), CPC, and market (US/UK) the traffic a website would receive (I.e., the clicks). 

# Data set Description: 

![image](https://user-images.githubusercontent.com/41851165/67200400-4168dc00-f421-11e9-816d-23bf5e1a39ca.png)

# Data visualization:

![image](https://user-images.githubusercontent.com/41851165/67200471-7d9c3c80-f421-11e9-9f01-e1b5734fb7d2.png)
![image](https://user-images.githubusercontent.com/41851165/67200493-8987fe80-f421-11e9-996a-c587c2d77991.png)


# Results:

# Random forest Regression:
Coefficient of determination R^2 of the prediction:  0.914177804049537
Mean squared error: 297606.09
Test Variance score: 0.80
mean_absolute_error: 74.95

# XGboost Regression:
Coefficient of determination R^2 of the prediction.  0.5800091699348091
Mean squared error: 393330.94
Test Variance score: 0.74
mean_absolute_error: 213.09


# 1-DCNN:
Mean squared error: 183220.71
Test Variance score: 0.88
mean_absolute_error: 61.83

# GRU:
Mean squared error: 125502.27
R2 score: 0.92
mean_absolute_error: 70.50
