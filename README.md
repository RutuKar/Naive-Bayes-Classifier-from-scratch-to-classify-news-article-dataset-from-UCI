
# Multinomial Naive Bayes Classifier from scratch for news article Classification

I have taken 20 news group dataset from UCI. Dataset contains 20,000 news articles from 20 different news topics.

Aim is to predict the topics of the news articles.

Cleaning is performed on the text files. Removed the stopwords, punctuation. Formed a vocabalry of words which is occuring freaquently in articles. This vocabalry of words are then used as features for further analysis.

Coded the Multinomial Naive Bayes Classification algorithm from scratch (without using any external modules). Laplace correction was implimented in the algorithm.

This algorithmic model is then trained on training data and tested on testing data. The testing text data is Classified into one of the 20 classes with the accuracy score of 79%.

Then for checking the performance of the model builded from scratch, I compared it with MultinomialNB naive bayes Classifier from sklearn module.
This model from sklearn is trained and tested on same data as previous and I got the same accuracy score as 79% from the sklearn model also.


## Dataset used
20 Newsgroups:
http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups