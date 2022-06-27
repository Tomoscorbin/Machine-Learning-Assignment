# Machine-Learning-Assignment

This report involves two tasks: 
 - A binary classification model predicting good/bad debtors with the Satlog German Credit Data Dataset.
 - A convolutional neural network classifying 13,000 images of diverse objects like parachutes, chainsaws, and fish.
 
A cost matrix accompanies the Satlog dataset stating that "it is worse to class a customer as good when they are bad (5) 
than it is to classify a customer as bad when they are good (1)". The target variable is heavily unbalanced, with a distribution 
of 70% negative class (0/good credit) and 30% positive class (1/bad credit). Since the aim is to minimize false negatives, 
the primary evaluation metric used is the F2 score. The optimum model achieves an F2 score of 0.7.

A simple convolutional neural network architecture was built that classifies the objects with an accuracy of 72%.
 
 
 
