# Sentiment-analysis-using-product-review-data
This is implementation of "Sentiment analysis using product review data" using Natural language processing.

This model can be used for Text processing and prdicting sentiment of customers. 

Model is trained on dataset from kaggle.
Data contains features like reviews,comments and rating from customers of amazon.
Data also contained whether the customer will recommend the product to others or not,which is a good
way to understand whether constomer was satisfied with the product or not.
Dataset contained 34000 reviews which was splitted in 20 percent for test set and 80 percent for training the model.

So with the use of training data we will predict whether costumer will recommend the product to others or not.

The model works on principle of NLP on text reviews and rating (1 to 5) which the uses multinomial naive bayes for predicting the sentiment.

Accuracy of 95.18 percent was achieved on test set wheras it was 95.48 on training set.

The implementation can be found in Sentiment_Analysis_forr_Amazon_review.ipynb file.
Unzip the dataset to run this model. 
