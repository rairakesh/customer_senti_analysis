**Customer Sentiment Preprocessing and Feature Extraction**

**Overview**

This project processes customer review data for sentiment analysis. It reads customer sentiment data from a CSV file, cleans and normalizes the review text, extracts NLP-based features, and prepares the data for training and testing a sentiment classification model.

**The code uses:**

* pandas for reading and manipulating CSV data
* numpy for numerical operations
* nltk for natural language processing
* re for regular expression-based text cleaning
* random for shuffling the dataset

**Short Summary** - 
This notebook preprocesses customer review text for sentiment analysis. It cleans hashtags, handles, URLs, emoticons, punctuation, and repeated characters, then converts each review into NLP features such as word presence, positive word indicators, and negation-based features. The processed data is shuffled and split into training and test sets using a 5-fold style split, preparing it for a future sentiment classification model.
