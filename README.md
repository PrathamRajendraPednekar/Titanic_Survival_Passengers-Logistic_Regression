# Titanic_Survival_Passengers-Logistic_Regression

# Problem Statement:
The problem at hand is to predict whether a passenger on the Titanic survived or not based on various attributes such as age, gender, ticket class, etc.

- Approach:To tackle this problem, you employed logistic regression, a popular statistical method for binary classification. Logistic regression works well for this 
           task as it estimates the probability of a certain outcome (survival in this case) based on one or more predictor variables.

- Preprocessing Steps:

- Data Cleaning: You began by cleaning the dataset, addressing missing values and outliers. For instance, you may have imputed missing age values using the mean or 
                median age of passengers.
- Feature Engineering: Next, you engineered features to improve the predictive power of the model. This could involve creating new features such as family size based 
                      on the number of siblings/spouses and parents/children aboard.
- Encoding Categorical Variables: Since logistic regression requires numerical input, you encoded categorical variables such as gender and embarked port using 
                                 techniques like one-hot encoding.
- Feature Scaling: You might have scaled numerical features to ensure they have similar ranges, preventing certain features from dominating others during model 
                  training.
- Model Performance:After preprocessing the data, you split it into training and testing sets for model evaluation. Upon training the logistic regression model, you 
                    evaluated its performance using metrics such as accuracy, precision, recall, and F1-score. Additionally, you may have visualized the model's 
                    performance using techniques like ROC curves.

Based on the evaluation metrics, you assessed the model's effectiveness in predicting Titanic survival. The performance metrics served as indicators of how well the logistic regression model generalized to unseen data, providing valuable insights into the factors influencing survival rates on the Titanic.
