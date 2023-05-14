# Readme: Sentiment Analysis on Review Texts
This project involves performing sentiment analysis on customer reviews. The objective is to train and test a Bag-of-Words (BoW) text classifier on the review texts using the ratings as labels. The ratings are binned into three categories, i.e., negative (ratings 1 & 2), neutral (rating 3) and positive (ratings 4 & 5). The binned ratings are then coded with negative as 0, neutral as 1, and positive as 2. The new column with these codes is called Sentiment.

However, the ratings are very unbalanced, with a significantly higher number of positive ratings than negative ratings. As a result, to balance the data, positive ratings are dropped to achieve approximately equal numbers of negative, neutral, and positive ratings.


# Project Steps
Data collection: Collect customer review data from a reliable source.
Data preprocessing: Clean and preprocess the review data by removing stopwords, punctuations, and special characters. Also, lemmatize the text data.
Data labeling: Bin the ratings into three categories, i.e., negative, neutral, and positive, and encode them with negative as 0, neutral as 1, and positive as 2. Add the new column, Sentiment, to the dataset.
Data balancing: Since there are significantly more positive ratings, drop some of the positive ratings to balance the data.
Feature extraction: Convert the preprocessed review texts into numerical data using BoW technique.
Model training: Split the data into training and testing sets and train a text classifier on the training data using the extracted features and the Sentiment column as labels.
Model testing: Evaluate the performance of the trained model on the test data using metrics like accuracy, precision, recall, and F1 score.
Model refinement: Refine the model by tuning its hyperparameters and feature extraction techniques.
Model deployment: Deploy the final model for sentiment analysis on new customer reviews.

# Required Libraries
The following Python libraries will be used in this project:

pandas
numpy
scikit-learn
matplotlib
seaborn

# Conclusion
Sentiment analysis is a critical task in understanding customers' perception of products or services. By training and testing a BoW text classifier on customer reviews, we can classify the reviews as negative, neutral, or positive sentiment. Balancing the data is crucial in preventing the model from being biased towards a particular sentiment. Through this project, we will gain insights into how to perform sentiment analysis on customer reviews and build an accurate model to classify them.
