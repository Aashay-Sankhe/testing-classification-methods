# testing_classification_methods
A jupyter notebook containing various methods of binary classification, and evaluating metrics based on a sample dataset.


**About this code**
Data1 and Data2 contain the sample classification data for the tasks
There are three files contained in this repo, two containing data and one containing the notebook.
The notebook is a display of various classification methods, so all cells can be run at the same time.

There are three methods used:
1. A raw implementation of binary classification, using gradient descent built from scratch with vectorized code via NumPy.
2. A standardized implementation where the data is normalized using z-score normalization in order to enhance accuracy of the initial classification model.
3. A neural network which uses two hidden layers and a single output layer. The output layer contains no activation function, so as to enhance the accuracy of the final computations of loss (from_logits=true).

Data was split 70/30 for train/test sets with no cross validation used.
(I intend to add more classification methods to this file, such as decision tree ensembles using XGBOOST and SVM decision boundaries).
