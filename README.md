# NLP ASSIGNMENT

## Data preprocessing

1. Remove punctuation

   Punctuations are tokenized as words so removing them

2. Remove digits

   Not considering digit to be words



## Document clustering 

k-means clustering using tfidf of bigram of text as feature vector. Chose it as it is comparatively easier to understand, and implement but have good results. 

**Finding:**

Most top bigrams were made of stop words so removing stop words from the text corpus will be better as it will give better insight to the data. 

**Problem encountered:**

Spacy nlp parser can only parse text of length 1000000. Tried to increase the maximum length of the parser but it resulted in memory error ( for 16 GB ram). So I divided the text corpus to 6 parts having maximum length of 1000000.



