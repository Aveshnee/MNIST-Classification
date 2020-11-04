# MNIST-Classification
Classification using MNIST handwritten dataset, applying Logistic Regression &amp; Decision Trees to get to the best accuracy, F1 scores and classification report.

## MNIST Logistic Regression & Decision Trees
The MNIST database of handwritten digits has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.

## Two Machine Learning Algos chosen

## 1) Decision Trees

A) Decision Trees chosen as using a decision tree for classification is an alternative methodology to logistic regression. Can handle data of different types, including continuous, categorical, ordinal, and binary. Transformations of the data are not required. Can be useful for detecting important variables, interactions, and identifying outliers. (https://webfocusinfocenter.informationbuilders.com/wfappent/TLs/TL_rstat/source/DecisionTree47

Report on the scores for Decision Trees model:

The Decision Tree was applied on the Train and Dev data without pruning, using a flat dataset. The train and dev scores are good. After pruning the model, and making predications on X, we applied the learning y and on the test data.

At depth: 45

Decision Tree Accuracy on the Train set (without pruning): 1.0

Decision Tree Accuracy on the Dev set(without pruning): 0.8641071428571429

Best performance reached at depth of: 14 ---- Test score - Decision Tree Accuracy (after pruning) on test data: 1.0

F1-score: 0.9739285714285715 Hardest class the models struggled with: 10

The Classification Report gives us a good indication of the other scores achieved.


## 2) Logistic Regression

A) Logistic Regression chosen because it is used as a baseline when comparing other models. Logistic Regression is also used when most dependent variables are numeric.

Report on the scores for Logistic Regression model using Solvers to tune:

Dev score - Logistic Regression Accuracy Train set: 0.92921875

Train score - Logistic Regression Accuracy Dev set: 0.9167857142857143

Test score - Logistic Regression Model Accuracy (after tuning solver): 0.9170714285714285

F1-score: 0.9170714285714285 Hardest class: 9 
