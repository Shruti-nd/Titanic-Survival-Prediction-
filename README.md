# Titanic-Survival-Prediction-
This project predicts Titanic passenger survival using machine learning models like logistic regression.
1. Women had a significantly higher survival rate compared to men.
2. 1st Class passengers had the highest survival rate, followed by 2nd Class, and 3rd Class had the lowest.
3. Children (0-10 years) had a higher survival rate due to priority evacuation.
4. Passengers traveling alone (SibSp=0, Parch=0) had a lower survival rate.

-> The Logistic Regression model provides a reasonable accuracy score, which indicates its ability to classify survivors and non-survivors based on the given features.
-> Features like Sex (male/female), Passenger Class (Pclass), and Embarked location are crucial in determining survival probability.
-> The model achieved an accuracy of 82%, meaning that 82% of the predictions on the test set were correct.
    
-> For Non-survivors (Class 0):
Precision: 83%
Recall: 90%
F1-Score: 86%
For Survivors (Class 1):
Precision: 76%
Recall: 65%
F1-Score: 70%

-> The high recall (90%) for non-survivors suggests the model is very effective at identifying passengers who did not survive.
-> However, a lower recall (65%) for survivors indicates that the model misses some of the actual survivors.
