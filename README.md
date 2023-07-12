# MachineLearningAssignments
Details and codes for select assignments completed in the Machine Learning Course

1. Understanding Interactions Effects, Fixed Effects in Linear and Logistic Regression
- Trained a Linear Regression model to see interaction between sales in multiple areas and how they affect total_sales
- In this model, it can be concluded that the sales in area 1 interacts with the sales in area 2 to give combined effect on target variable i.e. total sales hence the interaction term needs to be included in the model to make it more accurate
- Trained and Compared multiple Logistic Regression Model to predict whether the customer will purchase the product or not and selected the best model based on i. Accuracy (78.5%) ii. Out of Sample R^2 and iii. Prediction Error
- In Logistic Regression, interaction effects don't seem to make any difference

2. Average Treatment Effects
- Utilized double logistic regression to find ATE
- To overcome confounding effects, I used Regression Discontinuity technique. Keeping Drinking Age of 21 years as threshold, the difference between +-1 year bands (i.e. 20-21 years and 21-22 years) is considered to be the true treatment effect as the selection is randomized and confounding effects have been factored in due to randomization

3. K Nearest Neighbor
- Performed KNN technique on Iris dataset and experimented with the distance measure and no. of k.
- From the results, I get optimal results when k = 7 using Euclidean distance measure. I also checked the performance of different distance measures manhattan, euclidean, minkowski - for Euclidean I got 97% accuracy at k = 7. which is higher than manhatten and equal to higher power minkowski
