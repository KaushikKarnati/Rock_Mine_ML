# Rock_Mine_ML
This code is designed to demonstrate the use of logistic regression for binary classification of sonar data. The code imports several libraries, including numpy, pandas, and scikit-learn, to facilitate data manipulation, modeling, and evaluation.

The data used in this code is read from a CSV file ("Data.csv") containing sonar data with 60 features. The data is split into input and output variables, x and y respectively, and is then further divided into training and testing sets using the train_test_split method from scikit-learn.

The logistic regression model is then trained using the training data. The accuracy of the model is evaluated using the test data and the accuracy_score method from scikit-learn.

Finally, the code uses a sample input data array to demonstrate how to predict whether an object is a rock or a mine. The input data is converted into a numpy array and reshaped to predict for only one instance. The model then predicts the class of the input data, and the output is displayed as either "the object is Rock" or "the object is a Mine".

In summary, this code demonstrates how to train a logistic regression model to classify sonar data as either a rock or a mine and how to use the model to predict the class of new input data.
