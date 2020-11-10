# Twitter-US-Airline-Sentiment-classification

This is a sentiment classification project with Twitter US Airlines Sentiments Dataset available on Kaggle
It is a record of tweets about airlines in US. 
Along with other information, it contains ID of Tweet, sentiment of tweer ( neutral, negative and positive), reason for negative tweet, name of airline and text of tweet.
Here it is posed as a binary classififcation problem by converting neutral and positve tweets into one category.
Suitable Exploratory Data Analysis has been done followed by modeling as follows
1. Bag of Words with Naive Bayes
2. TFIDF with Naive Bayes
3. Word 2 vec with Naive Bayes
4. TFIDF weighted word2vec with Naive Bayes
5. Multilayer perceptron with embedding layer

Different techniques has given different recall values as follows

Naive Bayes with BOW = 0.75274
Naive Bayes with TFIDF = 0.7556
Naive Bayes with Word2Vec = 0.8061
NB with TFIDF weighted Word2Vec = 0.78127
Embedding layer in Keras = 0.865
Embedding layer with pretrained glove vectors = 0.907

Please follow along.......
