# SENTIMENT-SPECTRUM
"Analyzing and visualizing social media sentiment to understand public opinion on various topics and brands."

This analysis focuses on examining sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands. The steps taken to achieve this are summarized below:

**Data Import and Initial Exploration:**

The data is loaded from a CSV file using pandas.
The columns are named 'ID', 'entity', 'sentiment', and 'comment'.
Basic exploration of data structure and content, including checking the shape of the dataset, unique sentiment values, and frequency of different entities.

**Data Cleaning and Preprocessing:**

Duplicate rows are identified and removed to ensure data quality.
Missing values are checked and dropped.
The number of unique values in each column is analyzed.

**Initial Data Visualization:**

Pie chart displaying the distribution of sentiments (Positive, Negative, Neutral, Irrelevant).
Count plots showing the frequency of each sentiment and the distribution of sentiments by entity.
Bar plot illustrating the count of each entity in the dataset.

**Sentiment Analysis by Entity:**

A bar plot showing the average sentiment distribution for each entity, helping to identify overall public opinion towards each entity.

**Text Cleaning and Word Cloud Generation:**

Text data in comments is cleaned using a custom function to remove URLs, HTML tags, punctuation, stopwords, and digits. Words are also stemmed.
Separate WordClouds are generated for comments with Positive, Negative, Neutral, and Irrelevant sentiments. The word 'game' is excluded from the text data to focus on other significant words.

**Conclusion:**

The analysis provides a comprehensive overview of public sentiment towards various entities based on social media comments.
The use of visualizations such as pie charts, bar plots, and word clouds helps in understanding sentiment distribution and identifying key words associated with each sentiment. 
