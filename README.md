## Sentiment-Analysis-of-John-Wick-4

## INTRODUCTION
After John Wick Chapter 3, there was so much anticipation for the release of John Wick Chapter 4 and it premiered at the Odeon Luxe Leicester Square in London on March 6, 2023, and was released in the United States on March 24. Having been a fan of the movie I was thrilled with the release of John Wick Chapter 4, and I decided to perform a sentiment analysis to show what other viewers think of the movie.
This analysis enabled me to learn more about Data Mining and the use of the Natural Language Processing Tool Kit to draw out meanings from textual data.

## AIM OF THE ANALYSIS
This analysis was done to show viewers’ perceptions of the movie. I decided to carry out this analysis to find out the most common words used in the reviews, and the months and days with the highest rating.

## DATA ANALYSIS PROCEDURE
Below are the steps taken to achieve the result of this analysis;
1.	Data mining
2.	Data cleaning
3.	Data pre-processing
4.	Sentiment Analysis
5.	Data Visualization
6.	Insight communication

## DATA MINING
I started by scraping data from the reviews of John Wick Chapter 4 from the IMDB website. Then I imported the necessary libraries to extract the data from the website. I was able to get the reviews, titles, dates, and ratings to proceed with my analysis.

## DATA CLEANING
I mined a total of 866 data from the website which are reviews from the months of March to April 2023. I checked the dataset for missing data, and duplicates, and removed unnecessary columns, removed unnecessary strings from numerical data, then proceeded to convert the required columns to the right data type before I commenced with data pre-processing.

## DATA PRE-PROCESSING
To be able to use the dataset for sentiment analysis, I used natural language toolkits to pre-process the data by creating functions to remove tags, special characters, punctuations, stop words, and URLs. Also, the reviews were reduced to lowercase and tokenization was applied to break the sentences into single words and lemmatization was applied to break words down into their root meaning.

