# Text Sentiment Analysis Project #

VADER model from NLTK and RoBERTa pretrained model from Hugging Face library.

--- a pretrained approch to review tokenization, 
--- sentiment analysis will be through NLTK's SentimentntensityAnalyzer to categories negative, neutra, and positive using valance aware dictionary and sentiment reasoner.
--- this approach will use bag of words approach, removing stop words such as is the.
--- this approach does not account for relationships between words

Dependencies:
- numpy, pandas, matplotlib, seaborn, tqdm, nltk, nltk.sentiment, transformers, spicy.special for softmax function.
