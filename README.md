# Twitter Sentiment-Analysis


This repository contains my second SpringBoard Capstone Project.

## Summary: 
Building off the VADER sentiment analysis tools (Valence Aware Dictionary and sEntiment Reasoner) and applying it to tweets mined thru twitter API. After tweets about Kanye are gathered, and sentiment analysis will be performed on gathered data to analyse positivity/negativity over time, and corresponding to different public events. Other trends such as location, time of day, Iphone users vs android in sentiment, mobile vs pc, Length of tweet, etc will be considered. I would like to see what factors contribute to public sentiment, in this case on Kanye West. 

## Data:

[Kanye.csv](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/kanye.csv) - Collection of 3692 recent public tweets with the hashtag #Kanye
West.csv - Collection of 31732 recent public tweets with the hashtag #Kanyewest (including duplicates*)
Allkanyewest.csv - 30895 Kanye and Kanyewest combined with duplicates* removed
Fromk.csv - 180 Recent public tweets from Kanye West’s account 
Fromdt.csv - 176 Recent public tweets from Donald Trump’s account
Fromjk.csv - 181 Recent public tweets from Jimmy Kimmel’s account

*Duplicates are any tweet repeated exactly from the same user more than once, only the first is kept. This also weeds out duplicates created when a tweet includes both #Kanye and #Kanyewest.


## Code:

[Data](https://github.com/SilasNeptune/Sentiment-Analysis/blob/master/Data.ipynb) : Creating Twitter App to gather tweets using hashtags relating to Kanye West or from certain celebrities. 


[Exploratory Data Analysis](https://github.com/SilasNeptune/Dental-Health-in-Youth/blob/master/EDA_and_Inferential_Statistics.ipynb) : Exploring different trends in each variable along with correlations and trends among them. Using graphs and tables to get a better understanding of the world's distributions.


[Machine Learning](https://github.com/SilasNeptune/Dental-Health-in-Youth/blob/master/Machine%20Learning.ipynb) : Using two different clustering methods to group countries and comparing results.

## Reports
 
[Capstone Report](https://github.com/SilasNeptune/Dental-Health-in-Youth/blob/master/Capstone%20Project%201.pdf) : Full written report of this project.

[Presentation Slides](https://github.com/SilasNeptune/Dental-Health-in-Youth/blob/master/Dental%20Issues%20in%20Youth%20across%20the%20Globe.pdf) : Presentation slides to accompany capstone report.
