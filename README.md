# Nick Hill Portfolio

# [Titanic Project Overview](https://github.com/nickhill97/titanic)

In this project I attempted the titanic competition on kaggle.com, the data was collected from the kaggle website in CSV form. The final model had an accuracy of 0.78947 on the test set.

The data was already split into a training and test set, where the test set did not disclose the target variable. The data had 11 predictor variables. The goal of the competition is to produce the best model to predict whether a passenger on the titanic survived or died based on the features. Some of the key parts of this project:

- Filled missing age values using a linear lasso regression model.
- Created title feature from the name using python regular expressions.
- Performed recursive feature elimination to find an optimal subset of features to train the model on.
- Used K fold cross validation to estimate the accuracy of the models.
- The best model was a SVC with mean accuracy of 0.834 from the K fold cross validation models.



