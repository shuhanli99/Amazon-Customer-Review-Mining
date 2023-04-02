# Amazon-Customer-Review-Mining
Based on smartphone reviews from Amazon, this project performs feature extraction and sentiment analysis on review text in order to predict product rating and comment helpfulness.

The feature extraction and sentiment analysis part takes the paper [Mining and Summarizing Customer Reviews](https://www.cs.uic.edu/~liub/publications/kdd04-revSummary.pdf) as reference, mainly realized by NLTK tools in python.

In prediction part, we conpress the vector dimension using PCA, and predict product rating by decision tree, random forest, and SVM, comment helpfulness by linear, lasso, and ridge regressions.


note: Please download the code for reading instead of previewing here, since the output cells in [feature_extraction&sentiment_orientation.ipynb](https://github.com/shuhanli99/Amazon-Customer-Review-Mining/blob/main/feature_extraction%26sentiment_orientation.ipynb) is really long. 
