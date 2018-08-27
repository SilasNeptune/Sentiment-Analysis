# Twitter Sentiment-Analysis


This repository contains my second SpringBoard Capstone Project.

## Summary: 
Building off the VADER sentiment analysis tools (Valence Aware Dictionary and sEntiment Reasoner) and applying it to tweets mined thru twitter API. After tweets about Kanye are gathered, and sentiment analysis will be performed on gathered data to analyse positivity/negativity over time, and corresponding to different public events. Other trends such as location, time of day, Iphone users vs android in sentiment, mobile vs pc, Length of tweet, etc will be considered. I would like to see what factors contribute to public sentiment, in this case on Kanye West. 

## Data:

[Kanye.csv](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/kanye.csv) - Collection of 3692 recent public tweets with the hashtag #Kanye

[West.csv](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/west.csv) - Collection of 31,732 recent public tweets with the hashtag #Kanyewest (including duplicates*)

[Allkanyewest.csv](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/allkanyewest.csv) - Roughly 30,000 Kanye and Kanyewest combined with duplicates* removed

[Fromk.csv](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/fromk.csv) - 180 Recent public tweets from Kanye West’s account 

[Fromdt.csv](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/fromdt.csv) - 176 Recent public tweets from Donald Trump’s account

[Fromjk.csv](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/fromjk.csv) - 181 Recent public tweets from Jimmy Kimmel’s account

*Duplicates are any tweet repeated exactly from the same user more than once, only the first is kept. This also weeds out duplicates created when a tweet includes both #Kanye and #Kanyewest.


## Code:

[Data](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/Data.ipynb) : Creating Twitter App to gather tweets using hashtags relating to Kanye West or from certain celebrities. 


[Analysis](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/Analysis.ipynb) : Scoring sentiments for each tweet and exploring trends by time, source, location and user.



## Reports
 
[Twitter Sentiment Analysis](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/Capstone%20Project%202%20Sentiment%20Analysis%20Final.pdf) : Full Report on Project

Presentation TBD
