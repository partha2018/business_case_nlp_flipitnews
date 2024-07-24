# business_case_nlp_flipitnews

## Objective:

The goal of this project is to use a bunch of news articles extracted from the companies’ internal database
and categorize them into several categories like politics, technology, sports, business and entertainment
based on their content.

## About the Dataset:

This dataset consisting of 2225 instances has 2 columns:

1. Article: The content of article
2. Category: The category to which the Article belongs (Technology, Sports, Entertainment, Politics or
Business). Needless to say, This is our target variable.

## How will we accomplish the classification of News Articles?

• We will clean the data (news articles) by performing preprocessing tasks such as removing punctuation,
tockenization, removing stopwords and lemmatization
• We will use NLP techniques like BagOfWords and TF-IDF to convert the content of the articles into vectors.
• We will train different models like Naive Baye's, Decision Tree, Random Forest, K-Nearest Neighbours on
the vectorized data and compare their performance.
