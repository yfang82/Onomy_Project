# Onomy_Project
Codes and Reports of the data project with the start-up 

Onomy is a startup online education company who provides contents about adulting, including videos and articles about tax forms, health insurance and job seeking. Our data team did NLP analysis on Reddit posts to obtain the topics that people mostly concerned of on the path of adulting. 

The five ipynb files are the pipelines of the project. text_cleaning and n-grams_pipelines.ipynb is a collaboration with other team members, while the other four is independently written. 

Reddit_scrapping.ipynb: 
Used PushShiftAPI to get Reddit text data(including post selftext, scores, author etc.) under personalfinance, adulting and other subreddits.

text_cleaning and n-grams_pipelines.ipynb: 
For word frequency and word cloud report. Cleaned the text data and made n-grams frequency tables, corresponding barcharts and wordclouds. Took the post with highest score as examples to analyze the hot topics on Reddit(for word frequency analysis report) 

sentiment_VADAR.ipynb: 
Used VADAR model in nltk to give sentiment scores to each post selftext(for part I and II of sentiment analysis report)

sentiment_filter_pipelines.ipynb and multi-sentiment__topic modeling&n-grams_pipeline.ipynb:
Use a multi-sentiment lexicon to sort each post into a sentiment category, then do topic modeling under each sentiments to see the difference (for last part of sentiment analysis report).
