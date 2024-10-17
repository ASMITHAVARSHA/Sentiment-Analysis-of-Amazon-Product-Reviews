# Sentiment-Analysis-of-Amazon-Product-Reviews

# Project Overview
This project performs Sentiment Analysis on Amazon product reviews using machine learning models and NLP techniques. The analysis aims to classify reviews into positive, neutral, or negative sentiments based on the star ratings provided by users.

# Dataset
Star-rating: The rating given by the reviewer.

Name: The name of the reviewer.

Review Title: Title of the review.

Review Content: Detailed text of the review.

Date: The date when the review was posted.

# Data Loading:
The dataset is loaded from an Excel file.

Missing values are handled by filling names with 'Anonymous' and dropping rows where review content is missing.

# Text Preprocessing:
Convert the review text to lowercase.

Remove punctuation and numbers.

Tokenize the text and remove stopwords using NLTK.

Lemmatization is performed to reduce words to their base form.

# Sentiment Labeling:
Reviews with a star rating of 4 or 5 are labeled as Positive.

Reviews with a star rating of 3 are labeled as Neutral.

Reviews with a star rating of 1 or 2 are labeled as Negative.

# Visualization:
A count plot of sentiment labels.

A pie chart of sentiment distribution.

A bar chart showing the distribution of star ratings.

# Model Training:
TF-IDF Vectorization: Text is transformed into numerical features using TF-IDF.

Train/Test Split: Data is split into training and testing sets (80%/20%).

# Models:
Logistic Regression

Decision Tree

# Model Evaluation:
Confusion Matrix: Used to evaluate model performance for both Logistic Regression and Decision Tree.

Precision, Recall, F1-Score: Detailed classification reports are generated for both models.

# Results
Logistic Regression Accuracy: ~79.3%

Decision Tree Accuracy: ~71%

# Libraries Used
pandas

numpy

nltk

sklearn

matplotlib

seaborn

wordcloud

re
