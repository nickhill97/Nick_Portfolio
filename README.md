# Nick Hill Portfolio

# [Football Result Prediction Project Overview](https://github.com/nickhill97/football_predictions)

The purpose of this project was to use machine learning to predict premier league results. This could have many uses, for example, betting or management of a premier league team. The best model that I trained to solve this problem was a logistic regression model that predicted whether a team would win or not, this had an accuracy of 0.69.

- Collected the premier league fixtures data from the last 10 years from an API endpoint using a Python script.
- Calculated statistics that were correct at the time the games were played.
- Used a custom function to create interaction terms and relative statistics between the two teams.
- Used a weighted F1 statistic and GridSearchCV to find the best model and optimise the parameters.

# [Titanic Project Overview](https://github.com/nickhill97/titanic)

In this project I attempted the titanic competition on kaggle.com, the data was collected from the kaggle website in CSV form. The final model had an accuracy of 0.78947 on the test set.

The data was already split into a training and test set, where the test set did not disclose the target variable. The data had 11 predictor variables. The goal of the competition is to produce the best model to predict whether a passenger on the titanic survived or died based on the features. Some of the key parts of this project:

- Filled missing age values using a linear lasso regression model.
- Created title feature from the name using python regular expressions.
- Performed recursive feature elimination to find an optimal subset of features to train the model on.
- Used K fold cross validation to estimate the accuracy of the models.
- The best model was a SVC with mean accuracy of 0.834 from the K fold cross validation models.


