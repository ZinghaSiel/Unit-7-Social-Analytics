# News Mood


**Twitter** has become a wildly sprawling jungle of information—140 characters at a time. Somewhere between 350 million and 500 million tweets are estimated to be sent out _per day_. With such an explosion of data, on Twitter and elsewhere, it becomes more important than ever to tame it in some way, to concisely capture the essence of the data.

![Scatter-Plot](Images/Sentiment_Analysis_of_Media_Tweets)

This project consisted of analyzing tweet sentiments of some of the top Media/News outlets worldwide by pulling 100 of their latest tweets (from each account) using Tweepy API, storing them in a dataframe (later exported into a csv file) and presenting the findings visually (using a scatter plot and bar graph).

## Observable Trends

![Bar-Chart](Images/Overall_Media_Sentiment_based_on_Twitter)

* The Overall Media Sentiments for CBS and BBC were (positive), with CBS topping BBC by 0.18 points.

* CNN and New York Times had neutral sentiments overall compared to Fox News that had a relative negative sentiment analysis.

* One limitation faced when analyzing these results was probably the fact that, the analysis performed here focused only on a 100 tweets and not necessarily a collection of tweets posted over a defined period of time.