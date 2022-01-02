# Decision-Tree-Classifier

Note: Code is kept private, can show on a need-to-know basis.

This project implements a Decision Tree Classifier for binary classification problems. 

Given the training data and maximum depth, the program learns a decision tree of the specified depth. The algorithm uses mutual information as the splitting criterion (to determine which attribute to split on). As a stopping rule, the program splits on an attribute only if the mutual information is greater than 0. At the leaf, a majority vote classifier is used to predict a label.

The program also computes the training and test error.

