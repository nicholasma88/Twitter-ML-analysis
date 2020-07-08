# SuperBowl Tweets sentiment analysis

Of the many reasons why people watch the Super Bowl, one is for the excitement on the field and another is to watch and cast judgements on the halftime advertisements. We explore the use of the sentiments of individual tweets as a means to perform data analytics on these two topics. We identify five high importance individuals and six advertisements to investigate. The five high importance people are Patriots quarterback Tom Brady; Seahawks quarterback Russell Wilson; Patriots coach Bill Belichick, Seahawks coach Pete Carroll; and Seahawks running back Marshawn Lynch. And, the six advertisements we analyze are for Budweiser, Fiat, Microsoft, Dodge, Toyota, and Doritos. 

We analyze the #superbowl dataset from 8:00 AM until 8:00 PM on the day of the Super Bowl for each of the five high importance people separately and use all six advertising companies to represent advertisement sentiment collectively. We use bins of 5 minute duration for our analysis. First, we preprocess the data by removing hashtags, punctuation, links, stopwords, and digits. Then, we use tweepy and the class TwitterClient to generate sentiment scores for every tweet, where 1 is positive and -1 is negative. For each high importance person, we search for the following terms and aggregate the total number of positive tweets, negative tweets, and the total number of tweets pertaining to each person. 

### Code
The code folder contains questions related to report file
