# Tweets classification

## Purpose

The purpose of this project is to predict which tweets are about real disasters and which aren't.
To accomplish this the following steps have been executed:

1. Data preprocessing including feature engineering, text mining operations (to obtain information from tweets), handling missing data, selecting important features.
2. Predictive modelling including testing models of logistic regression, random forest and XGBoost.

## Data set information

The dataset was downloaded from kaggle competition <a href="https://www.kaggle.com/c/nlp-getting-started/overview">Natural Language Processing with Disaster Tweets</a>.
The features available in the dataset are as following:

- `id` - unique identifier of a tweet
- `keyword` - particular keyword from the tweet
- `location` - location the tweet was sent from
- `text` - text of the tweet
- `target` - whether a tweet is about a real disaster or not

The dataset consists of 7613 tweets, out of which 3271 are about real disasters.

## Analysis

The file `tweets_classification.ipynb` contains the main jupyter notebook with the whole preprocessing and modelling process.

The analysis was performed in Jupyter Notebooks using libraries such as: numpy, pandas, matplotlib, scikit-learn, seaborn, nltk, xgboost.
