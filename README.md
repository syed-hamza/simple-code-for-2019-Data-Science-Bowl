# My First Try At 2019 Data Science Bowl 

This repository consists of the codes of my first attept at a kaggle competition at <br/>
https://www.kaggle.com/c/data-science-bowl-2019 \
Thanks to: \
[shippeng](https://www.kaggle.com/shippeng/convert-to-regression-classification) and \
[artgor](https://www.kaggle.com/artgor/quick-and-dirty-regression) for their help.

The model with the highest public score but a lower private score is [here](Overfit.ipynb) most likely due to overfitting of the XGB model(as the max depth was taken as 10) and the parameters were not optimised. This proved that a higher score on the public leaderboard does'nt necessary give a higher score in the private leaderboard, hence it is better to submit a ernel with a lower score as well. \
My highest private score using lightboost and xgboost is [here](Highest_Score_0.ipynb).\
Code with similar private score was using lightboost, xgboost, neural network and convolutional neural network is [here](Highest_Score_1.ipynb).\
Code for finding the best weights is [here](weights_calculation.ipynb).

This was my first attempt at a kaggle competition. Since I joined the competition late, I had no time for analyzing the data thoroughly and hence had to rely on the above kernels for the processed data. All the given models have optimised hyperparameters using byesian optimisation(for LightBoost and Catboost) or hyperopt(for Xgboost).

Thanks for reading!
Hope this repository is helpful.



