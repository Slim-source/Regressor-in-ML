# Regressor-in-ML
Comparison of a regressor. Linear regression vs voting ensemble


 #linear regressor model comments
Linear Regression model, trains it on diabetes training dataset, predicts the output for your testing dataset, and evaluates the performance


#voting ensemble regressor model comments
Voting Ensemble Regressor. It combines multiple diverse regression models—a Gradient Boosting Regressor, a Random Forest Regressor, and a Ridge Regressor—to produce more robust and accurate predictions.


#output comments
Unexpected Performance Drop: Interestingly, the simpler Linear Regression model outperformed the complex Voting Ensemble on our 20-sample test set (yielding a higher $R^2$$R^2$ of 0.59 versus 0.51).
This was caused by the data scale for test partition as it contains only 20 samples since methods like Gradient Boosting and Random forest used in voting Ensemble regressor model require large amount of data to learn robust patterns
