# Text Analysis
we analyzed text data to determine when an article may be fake news. Our goal is to Build a text classification model to predict whether the news is reliable or not.
we've got the data from kaggle (data: https://www.kaggle.com/c/fake-news/data ) 
our data contains 5 columns and 20800 rows. The columns we have are:
id: a unique identifier for a news article
title: the title of the news article
author: the author of the news article
text: the text of the article; it may be incomplete
label: a label indicating whether the article is unreliable
The results are as follows:
1: unreliable
0: reliable
 we imported  libraries such as pandas and nltk  for data analysis. We loaded the necessary resources from NLTK, including text segmentation tools and stop words.
 Next removed stop words and analyzed the most frequent words, then presented the results in a chart to better understand the content. We also applied Tokenization and lemmatization to improve data quality and provide better features for the models. and discoverd most common words in reliable label was "trump", "new" and in unreliable label "woman" , "lifes" .

So,after cleaning data and prepared data we moved to modeling step , we choose Naive Bayes models (ComplementNB, BernoulliNB, MultinomialNB) on the same dataset.

Navies Bayes Modelling
We compared the performance of three different Naive Bayes models (ComplementNB, BernoulliNB, MultinomialNB) on the same dataset. We evaluated each model by calculating its accuracy, displaying confusion matrices, and providing a classification report 
Results:
ComplementNB:
Model accuracy: 74.90%.
The confusion matrix shows the number of correct and incorrect classifications.
The classification report displays performance for each class.
BernoulliNB:
Model accuracy: 78.22%.
The confusion matrix illustrates performance.
The classification report provides detailed insights into the results.
MultinomialNB:
Model accuracy: 77.91%.
The confusion matrix indicates how the model classified the data.
The classification report shows performance for each class.


TF-IDF: Term Frequency-Inverse Document Frequency
providing a classification report.

Results:
ComplementNB:
Model accuracy: 75.70%.

BernoulliNB:
Model accuracy: 78.17%.

MultinomialNB:
Model accuracy: 78.17%.

Conclusion:
From the results, we observe that the BernoulliNB model performed the best, achieving the highest accuracy of 78.22%, making it the most suitable option for use.
