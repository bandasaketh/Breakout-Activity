# Breakout-Activity
Problem: We have to develop a model, which should predict weight by a person's height and gender. This is a regression problem, because our target variable of prediction, weight, will be continuous, and the data that we're supposed to base our prediction on consists of two features: height and gender encoded as binary.

After numerical encoding of gender-0 for male and 1 for female-the dataset has been split into train and test sets. This problem seems quite simple and can be handled using a linear regression model since the relation between height, gender, and weight may happen to be linear or close to linear.

Solution:

The procedure consists of the following:

Data Loading and Exploration: The dataset is loaded, and the structure of the data is determined. Descriptive statistics, such as means, standard deviation, and ranges, are computed showing quite a disparate set of heights and weights.

Data preprocessing: Numerical encoding in the gender column facilitates ease for the regression model to handle the categorical variable. Split the dataset into feature variables, X- height and gender, and a target variable, y - weight.

Training the Model: The Linear Regression model is trained on 80% of data using the function train_test_split. This splits the dataset into the training set and test set to make sure the model generalizes well on unseen data.

Evaluation: After predictions on the test set have been made, the model performance, in terms of Mean Squared Error (MSE), was evaluated. Accordingly, the MSE of the model was calculated to be approximately 101.24, which can give an idea about the performance of the model in predicting weight.

Reflection: It is a simple solution, therefore, it uses one of the most well-recognized linear regression algorithms. The simplicity of the model, further combined with the small number of features, makes the model interpretable. Moreover, using Mean Squared Error for the evaluation metric is proper in regression problems.

The error of 101.24.
