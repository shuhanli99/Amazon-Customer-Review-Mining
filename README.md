# Amazon-Customer-Review-Mining
Based on smartphone reviews from Amazon, this project performs feature extraction and sentiment analysis on review text in order to predict product rating and comment helpfulness.

The feature extraction and sentiment analysis part takes the paper [Mining and Summarizing Customer Reviews](https://www.cs.uic.edu/~liub/publications/kdd04-revSummary.pdf) as reference, mainly realized by NLTK tools in python.

In prediction part, we conpress the vector dimension using PCA, and predict product rating by decision tree, random forest, and SVM, comment helpfulness by linear, lasso, and ridge regressions.

