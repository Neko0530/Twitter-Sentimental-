# Twitter Sentiment Analysis for Mental Health Tweets

This code performs sentiment analysis on a dataset of Twitter data related to mental health. It analyzes the sentiment of the tweets and visualizes the sentiment distribution, trains a logistic regression model for sentiment classification, and evaluates the model's performance.

## Sentiment Analysis and Visualization

The code first pre-processes the text data by removing URLs, mentions, hashtags, and punctuation, and converting the text to lowercase. It then performs sentiment analysis on the cleaned text using the TextBlob library and categorizes the sentiment as positive, neutral, or negative. The sentiment distribution is visualized using a count plot.

## Sentiment Classification

The code uses TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction. It splits the data into training and test sets and trains a logistic regression model on the training data. The model is then used to make predictions on the test set. The classification report and accuracy score are printed to evaluate the model's performance.

## Confusion Matrix

The code generates a confusion matrix to further evaluate the model's performance. The confusion matrix is visualized using a heatmap, with true labels on the y-axis and predicted labels on the x-axis.

## Classification Scores

The code creates a bar chart to display the precision, recall, and F1-score for positive sentiment classification. Replace the placeholder scores with your actual scores.

## Usage

To use this code, ensure that you have the 'Twitter_Data.csv' dataset in the same directory. Run the code in Python, and the sentiment analysis, classification, and visualizations will be performed.

Note: Make sure to install the necessary libraries (e.g., pandas, re, textblob, sklearn, matplotlib, seaborn) if you haven't already.

Feel free to modify the code and explore the dataset further.
