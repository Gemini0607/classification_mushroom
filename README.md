# classification_mushroom

1. Source Information

The description of the dataset can be found in the description.txt file. The data set was downloaded from the UCI Machine Learning Repository.

2.The Approach

-- Multiple classification models were trained since there was a difference in performance measures of a linear model versus other models.
-- After various iterations, it was observed that models built using only 12 feature variables(originally 22) gave insignificant performance difference(except linear models), thus models other than linear are best suited for this dataset.
-- The different evaluation metrics used also confirm the high performance of the models achieved.

3. Technique used

-- We have made of use of Linear models, Tree based model, Support vectors and Nearest Neighbour to build the the best possible classifier.
-- Out of the following, the best results obtained(with PCA) are of KNN Classifier(default parameters - 99.5), Decision Tree Classifier(default parameters - 99.35), Logistic Regression(88.62) and Support Vector Classifier(default parameters -100)
-- This high accuracy did not require any further tuning of the parameters.
-- The evaluation metrics used are AUC ROC score, confusion matrix, classification report(precision, recall, f1-score, support)
