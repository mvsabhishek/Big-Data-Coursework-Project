Human Activity Recognition with Smartphones using Multinomial Logistic Regression 

Name: Venkata Siva Abhishek Munukutla

Summary

In this project, I attempted to test the accuracy of a cell/mobile phone prediction of human activity with the help of Multinomial Logistic Regression. The dataset contains 561 columns and over 10000 records. The columns describe features like acceleration and angular velocity contain numeric values between -1 to +1. The columns have been scaled for the ease of use. The columns of the dataset describe the position of the phone in 3 dimensions based on its default calibration.  With the help of these values, human activities like sitting, standing, walking, etc. were classified.

Initially, I used Binomial Logistic Regression to classify the activity into either STANDING or NOT STANDING. I was able to achieve 81% accuracy. The model was based on the following equation.
ln (P) = 3.30796 * X1 – 2.7903 * X2 + …… ….. + 0.09259 * X560 – 1.49684

Later, I attempted to classify the activity into six categories. However, I ran into nearly 62 % inaccuracy. This made me think that the model could not fit the given data. I will have to use a different Classification Models to achieve the objective.

If I am successful at maximizing the accuracy, I can classify the activity of a person based on the various parameters. This makes the cell/mobile phone equipped with the functionality of predicting the person’s activity and thereby helping the person track his/her daily activity efficiently. 

