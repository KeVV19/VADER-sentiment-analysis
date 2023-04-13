# VADER-sentiment-analysis
This project is a part of Text Analytics and Sentiment Analysis module assignment in university.

Musical_Instruments_Reviews.csv is the dataset used to perform sentiment analysis, the dataset consists of string values of musical instruments review.

The goal of this project is to know the sentiment (positivity / negativity) of the review from the dataset given by using sentiment prediction module
and create a supervised text classification model.

Valence Aware Dictionary and Sentiment Reasoner (VADER) is a model which is available in the NLTK module used for sentiment analysis. VADER works by using a 
dictionary to map different features and emotional intensity of a text called polarity score. VADER is chosen for the sentiment prediction section because it doesn’t 
require any pre-processing as well as training data, and it can understand a text with underlying context such as emoticons, capital words, punctuations, slang, etc, 
which will be effective to predict the dataset which consists of these features.

Multinomial NB (Naive Bayes) model is used to create the supervised classification model.
