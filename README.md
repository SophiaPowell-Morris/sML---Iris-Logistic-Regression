# sML---Iris-Logistic-Regression

There are three iris classes in the dataset and we want to create a classifier
that will predict whether an iris belongs to the ‘Iris-setosa' class or not. This
means that we have two classes, ‘Iris-setosa' and not-‘Iris-setosa' (which
consists of 'Iris-versicolor' and 'Iris-virginica' ).

Identify your independent variables x.

Encode your dependent variable y such that ‘Iris-setosa' is encoded
as 0, and 'Iris-versicolor' and 'Iris-virginica' are both encoded as 1. (0
corresponds to the 'Iris-versicolor' class, and 1 corresponds to the
not-‘Iris-setosa' class.)

Split the data into a training and test set.

Use sklearn’s logistic regression function to fit a model and make
predictions on the test set.

Use sklearn to obtain a confusion matrix comparing the predictions
to the gold labels.

Examine the confusion matrix and predict in a comment whether
the model is likely to have higher precision, higher recall, or similar
precision and recall.

Write your own code to calculate the accuracy, precision, and recall,
and check whether your prediction was right.

(optional) Repeat this task but change it so that we only have all three
categories ‘Iris-setosa', 'Iris-versicolor', and 'Iris-virginica' corresponding to the
numeric values 0, 1, and 2 respectively; this will now be a three-class
problem. Observe how this changes the confusion matrix.
