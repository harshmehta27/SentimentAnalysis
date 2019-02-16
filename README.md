# SentimentAnalysis

The Sentiment Analysis of user feedbacks on airlines was made using NLP and ML Algorithms

The project was carried out in Python
Libraries Used: numpy, pandas, sklearn, nltk, scipy 

Natural Language Processing was done using Python's NLTK library and the following steps were executed:
- Tokenization of Tweets
- Case Conversation of Tokens
- Stemming and Lemmatization
- Removing Stop Words
- Part of Speech (POS) Tagging

Lexicon Based Approach:
- GeneralInquirer Dictionary was used to assign polarity values to tokens
- SentiWordNet and Opinion Lexicon were also used to create the dictionary
- Assigned a Semantic Orientation Score to each token
- Created a list of words from Taboada to account for intensifiers

Features of the Model:
- Frequency of Adverb, Adjective, Noun, Verb (in each tweet)
- Polarity of the Tweet
- Number of Positive Words
- Number of Negative Words 

Methodology and Implementation:
- Implemented Naive Bayes in Python 
- Implemented Decision Tree Classifier (ID3) in Python
