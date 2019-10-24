# digitRecognizer

*The data set comes from the Kaggle Digit Recognizer competition. The goal is to recognize digits 0 to 9 in
handwriting images.*

The Data can be found at:-
https://www.kaggle.com/c/digit-recognizer/data

Techniques used:-
1. Naive bayes Classifier
2. K-Nearest Neighbor Classifier
3. Support Vector Machine Classifier 

3-fold cross validation as used for paramter tuning. Additional, a package called doParallel as used. This package uses all the cores available for parallel processing.

Validation Accuracies achieved:-
1. Naive Bayes:- 65.79%
2. K-NN:- 85.65%
3. SVM Model:- 85.17%

**comparison plot for 3 fold cross validation:-**

![alt text](https://github.com/mihird94/digitRecognizer/blob/master/comparison.PNG)
