# default-of-credit-card
The aim of this project is to compare different methods for predicting a customer’s default score, drawing on the work of (I. Yeh, 2009)

Data set
30,000 customers (April–September 2005)
23 variables, including 14 numerical variables and 9 categorical variables
Target variable: default in the following month (22.12 per cent)

Algorithms used in the article:
K-nearest neighbours, Logistic regression, Discriminant analysis, Naive Bayes algorithm, Neural networks, Classification trees

Our approach
Pre-processing
Qualitative variables → one-hot encoding
Quantitative variables → normalised (min–max)
Implementation: Random Forest, SVM and XGBOOST in addition to the algorithms described in the article

To evaluate binary classification performance (default / non-default), we use:
The error rate derived from the confusion matrix
The ROC curve and the area under the curve (AUC)
The lift chart (cumulative gain curve)
