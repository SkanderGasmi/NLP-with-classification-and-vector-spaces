# Sentiment-Analysis-with-Logistic-Regression

Welcome to the "Sentiment Analysis with Logistic Regression" project. This repository contains a series of notebooks that walk goes through the process of performing sentiment analysis using logistic regression. Each  focuses on a specific aspect of the project.

1. [Preprocessing](https://github.com/SkanderGasmi/Sentiment-Analysis-with-Logistic-Regression/blob/main/1_preprocessing.ipynb) - This notebook covers the preprocessing steps required to prepare the text data for sentiment analysis which include:
   * Tokenization 
   * Lowercasing
   * Removing stop words and punctuation
   * Stemming
     
2. [Word Frequencies](https://github.com/SkanderGasmi/Sentiment-Analysis-with-Logistic-Regression/blob/main/2_word%20frequencies.ipynb) - This notebook covers the function `build_freq` that build a word frequency dictionary, mapping each (word, sentiment) pair(tuple) to its frequency, which helps us when extracting the features of a list of tweets.
   
3. [Sentiment Analysis with Logistic regressionR](https://github.com/SkanderGasmi/Sentiment-Analysis-with-Logistic-Regression/blob/main/3_sentiment_analysis_with_logistic_regression.ipynb) - This final notebook combines all the previous steps to perform sentiment analysis using the logistic regression model, we implement the model from scatch, update its weights using gradient descent and visualize the decision boundary the we compute the accuracy on the validation set which is 99.5 %

Feel free to explore each notebook to understand the details of each step involved in the sentiment analysis process.
