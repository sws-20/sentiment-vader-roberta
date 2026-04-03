# sentiment-vader-roberta
Sentiment analysis of Amazon customer reviews comparing NLTK's VADER (lexicon-based) and Hugging Face's RoBERTa (transformer-based) models.

#Amazon Review Sentiment Analysis: VADER vs. RoBERTa
This project explores Sentiment Analysis on Amazon customer reviews using two distinct approaches: a traditional lexicon-based model (VADER) and a modern transformer-based model (RoBERTa). By comparing the two, we can visualize how deep learning handles context and nuance differently than rule-based methods.

The goal is to classify customer sentiment as Positive, Neutral, or Negative. We benchmark the results of:

#NLTK VADER: (Valence Aware Dictionary and sEntiment Reasoner) - A bag-of-words approach that is fast and efficient.

#Hugging Face RoBERTa: A transformer model pre-trained on a large corpus of data, providing much deeper contextual understanding.

#Key Features
Data Processing: Exploratory Data Analysis (EDA) of Amazon reviews using Pandas and Seaborn.

#VADER Sentiment: Generating polarity scores (pos/neu/neg/compound).

#RoBERTa Model: Leveraging the cardiffnlp/twitter-roberta-base-sentiment model from the Hugging Face Hub.

#Comparison: A side-by-side visualization of how both models perform on the same review samples.
