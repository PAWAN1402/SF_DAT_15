## Class 8 Exercise: Predicting Survival on the Titanic

This assignment uses data from Kaggle's [Titanic](https://www.kaggle.com/c/titanic/data) competition. `titanic.csv` is in the repo, so there is no need to download the data from the Kaggle website.

**Tasks:**

1. Read `titanic.csv` into a DataFrame.
2. Define Pclass and Parch as the features, and Survived as the response.
3. Split the data into training and testing sets.
4. Fit a logistic regression model and examine the coefficients to confirm that they make intuitive sense.
5. Make predictions on the testing set and calculate the accuracy.
6. **Bonus:** Add Age as a feature, and calculate the testing accuracy. There will be a small issue you'll have to deal with. What is it?
7. Create a confusion matrix and document the model's sensitivity and specificity. (remember you should run metrics on your test classes!)