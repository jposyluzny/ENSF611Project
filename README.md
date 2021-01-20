# Machine learning project

This was an individual project. Each of us students were to find our own datasets that would be suitable for a machine learning exercise, and then treat it as we would treat an assignment. I chose a dataset which was built using survey data on the aspects of the daily life of an individual, and their perceived stress. My goal was to find which aspects had the biggest role in predicting the perceived stress of an individual. I treated it as a regression task, although I conceded in the end that classification would have likely been more appropriate. The models I trained were: 
* Gradient Boosting Regressor 
* Random Forest Regressor
* Bayesian Ridge
* K Nearest Neighbors 
* Support Vector Regressor <br>

In the end, the Support Vector Classifier performed the best, as it yielded the lowest mean squared error on the validation data (0.81). The feature that had the greatest impact on the model was called SOCIAL_NETWORK, and it was a measure of on average how many people the interviewee interacts with on a given day. <br>
I realize that such a dataset and its results need to be taken with a tablespoon of salt, as this data is all completely subjective. 
