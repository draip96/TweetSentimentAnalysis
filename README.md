# TweetSentimentAnalysis

This Recurrent Neural Network uses word embeddings and LSTM modules to analyse the sentiment of tweets. This notebook loads, sanitises, and tokenises tweets from the sentiment140 dataset found here: https://www.kaggle.com/datasets/kazanova/sentiment140. The model then uses a simple RNN to classify tweets as either positive or negative.

The performance of this model is suboptimal, as it only manages to correctly classify 78% of the tweets in the test set, and fails to ascertain a nuanced understanding of language in tweets. To increase the accuracy, a larger model or perhaps an alternate architecture altogether such as a transformer language model,
could be used to gain a better understanding of the english language. Unfortunately, scaling this model is currently infeasable as it would require greater computing power for efficient iteration.

