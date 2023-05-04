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
I mined a total of 866 data from the website which are reviews from March to April 2023. I checked the dataset for missing data, and duplicates, and removed unnecessary columns, removed unnecessary strings from numerical data, then proceeded to convert the required columns to the right data type before I commenced with data pre-processing.

## DATA PRE-PROCESSING
To be able to use the dataset for sentiment analysis, I used natural language toolkits to pre-process the data by creating functions to remove tags, special characters, punctuations, stop words, and URLs. Also, the reviews were reduced to lowercase and tokenization was applied to break the sentences into single words and lemmatization was applied to break words down into their root meaning.

## SENTIMENT ANALYSIS
Sentiment analysis is also known as opinion mining which is used to determine if a sentence is positive, negative or neutral. To achieve this, I used the TextBlob library to get the polarity score of the reviews where >0 gives a positive polarity, <0 gives a negative polarity and =0 gives a neutral polarity. 

## DATA VISUALIZATION
I exported the data into CSV and used Power BI to create a dashboard communicating my findings.
![Sentiment_analysis_dashboard](https://user-images.githubusercontent.com/47563475/236303539-57378284-cf98-4039-aadb-1703b147c0b2.jpg)

## INSIGHT COMMUNICATION
From the analysis, 94% of those who have watched the movie left a positive review while 6% left a negative review about the movie. And the most common word they used to describe the movie is “action movie” which clearly defines John Wick Chapter 4.

Since the movie was released on March 24th, 2023 most of the reviews were made in the month of March and it gradually drops as we enter the month of April. 

