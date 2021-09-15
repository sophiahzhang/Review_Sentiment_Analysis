Sentiment Analysis of Online Reviews

*The goal of this project is to develop binary classifiers that can generate sentiment-labels for new sentences in text reviews, automating the assessment process.

*We have several thousand single-sentence reviews, collected from three domains: imdb.com, amazon.com, and yelp.com. Each review consists of a sentence, and has been assigned a binary label indicating the sentiment (1 for positive and 0 for negative) of that sentence.  While the reviews were collected from websites where much of the content is in English, the reviews may contain slang, spelling errors, and foreign characters. 
*The collected data consists of 2,400 training examples. 
Input data has two columns, for the source-website and review text; outputs are given as binary values, where 1 indicates a positive review. 


Data Contents

* `data_reviews`: train/test data
    * x_train.csv : Each row is a training set example, contains raw text of a review observed on a website, as well as the name of the website (amazon, yelp, imdb)
    *  y_train.csv : Binary sentiment labels (1 = positive, 0 = negative) for each review in x_train
    * x_test.csv : Each row is a test set example, contains raw text of a review observed on a website, as well as the name of the website (amazon, yelp, imdb)
* `load_train_data.py`: sample code to load data

