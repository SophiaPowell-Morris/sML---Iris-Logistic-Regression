# sML---Iris Segmentation-Logistic-Regression

## Iris-Setosa or Not (Iris-Versicolor, Iris-Virginica)
There are three iris classes in the dataset and we want to create a classifier that will predict whether an iris belongs to the ‘Iris-setosa' class or not. 

This means that we have two classes, ‘Iris-setosa' and not-‘Iris-setosa' (which consists of 'Iris-versicolor' and 'Iris-virginica' ).

The IVs were identified and set to an variable x.

The DVs were encoded to 0 and 1, where 0 corresponds to the 'Iris-setosa' class, and 1 corresponds to the
not-‘Iris-setosa' class, which includes 'Iris-versicolor' and 'Iris-virginica'.

The data was split into a training and test set with an 80:20 split.

Sklearn’s logistic regression function was used to fit a model and then make predictions on the test set.

A confusion matrix was then genereated to compare the predictions to the gold labels. The matrix was then examined to make prediction about the models Precisiom and Recall scores.

The accuracy, precision, and recall scores where calculated and interpreted.

## Iris-Setosa OR Iris-Versicolor OR Iris-Virginica

The same steps were repeated above, except when encoding the numeric values of 0, 1 and 2 were used to encode the categories to ‘Iris-setosa', 'Iris-versicolor', and 'Iris-virginica' respectively.
