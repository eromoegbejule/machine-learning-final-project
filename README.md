# machine-learning-final-project

This, is an [ongoing] version of my final project in Machine Learning for the Algorithms class in the Data Journalism program, looking at the sentiments of Twitter users to US airlines. This data set, originally scraped by and published in the Crowdflower Data for Everyone library, is now archived at the Internet Wayback Machine - and missing as at the time of this project. I worked with the slightly reformatted version that was available on Kaggle.

The original data is present here: https://web.archive.org/web/20160426032027/http://www.crowdflower.com/data-for-everyone/

The formatted data is present here: https://www.kaggle.com/crowdflower/twitter-airline-sentiment?select=Tweets.csv

This data was very fascinating to me, because I saw a friend complaining about US Airlines and getting sympathy from Americans. So I decided to play around with Twitter and see just how much worse it would be if Americans were complaining about American airlines. Eventually, I found this interesting dataset on the web to mine.

I ran a few classifiers to determine the nature of these sentiments - positive, negative or neutral. What I found was an overwhelmingly negative perception of these airlines. Both the RandomForestClassifier and Perceptron that I used,classifiers returned the same predictions and accuracy score of 100%.

Also, I attempted to use different features in determining more details about the negatives and found that Bad Customer Service and Late Flights are the most common complaints about these airlines.

I also found out that Americans are really angry about their airline services and don’t hold back when expressing their anger...
