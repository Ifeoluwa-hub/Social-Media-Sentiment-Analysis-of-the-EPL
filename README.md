# Social-Media-Sentiment-Analysis-of-the-EPL
Natural Language Processing (NLP) on twitter data using roBERTa model with python for sentiment analysis.
# Sentiment Analyis
Sentiment analysis is a natural language processing (NLP) algorithm to identify, extract, and quantify the emotional tone behind a body of text. We can use sentiment analysis to determine whether the emotion of a tweet is positive, neutral, or negative.
# Data Collection
The data was collected from the twitter using tweepy, a python library for accessing twitter API. About 5000 tweets were collected from 6th of August 2022 when the premier league started using the keyword 'EPL'. 
# Data Cleaning
The data was cleaned, removing unwanted text, symbols and punctuations. Duplicates was also dropped and this reduced the number of tweets to about 3293 from 5000
# Exploratory Data Analysis
EDA was done using pandas, matplotlib, wordcloud. From the EDA, the Subjectivity (i.e how subjective each tweet is and the polarity of each tweet was gotten.
A wordcloud showing the distribution of sentiment was also plotted
# Sentiment Analyis Model
The sentiment analyis model was built leveraging roBERTa, an AI developed by the Meta Research Team.
