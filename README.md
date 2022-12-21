# Forecasting-Bitcoin-Prices

Since Bitcoin’s launch in 2008, cryptocurrencies have stormed the financial world. Since inception
to present, Bitcoin’s market cap exceeds USD $800 Million1 and the more than 3000
cryptocurrencies now hold a market value of approximately USD $2 Billion

Cryptocurrencies are also characterized by extreme volatility, both over time and even within a
single day. 

On average, 6,000 tweets are posted on Twitter every second, 350 thousand every minute, and
500 million every day.

Not only is Twitter an important social media platform used to share
personal opinions, but it is also a tool used to instantly spread and receive breaking news. Twitter
is also a powerful tool for traders as it can provide them with the latest information quicker than
even the most reliable news vendors.
According to research, people may have found that Bitcoin’s value has been manipulated by
some of the public sentiment. A study conducted by News BTC, showed that some periods of
increased activity in social media commentary have significant influence in price movements
related to Bitcoin. To clarify, according to the analysis, Tweets and comments from the vocal
minority did not seem to have the power to influence Bitcoin’s price. Moreover, the study has
found that, interestingly, the infrequent users who commented on the perspective of Bitcoin
might be able to move the price more. Therefore, the Bitcoin’s value is manipulated by the public
sentiment, especially by those positive comments by infrequent social media users. 6


## 2.2 Business Case
Considering the extreme volatility of Bitcoin, if someone were able to predict its short-term
movement, if only with a slightly better-than-chance accuracy, one could potentially unlock
profitable short-term trading strategies.

Considering the large amount of information flowing daily through Twitter, it is plausible that it
could serve as a mine of information that could inform future price movements. Some of that
information include, analyzing:
• The daily number of tweets, retweets, and likes that make mention of Bitcoin
• The sentiment, positive-neutral-negative, expressed in those tweets
• The actual content of those tweets

Predicting a system as chaotic as the bitcoin market accurately, is near impossible to conduct
using traditional analytical methods. However, there may be opportunities for AI Deep Learning
to succeed where traditional methods come short. Deep Learning techniques that can be
considered include:
• Determining tweet sentiment via natural language processing
• Classifying the content of tweets for price movement leveraging pre-trained language
models and transfer learning
• Using dense deep feed-forward networks on a range of metadata about the tweets and
the price of bitcoin to predict future price movement
• Using Recurrent Neural Networks to explore if time-series of the data can provide
information about future price movement

## 2.3 Scope
This project will explore different Deep Learning architectures to predict the future (next-day)
price movement of Bitcoin. Since Bitcoin trades on a continuous basis, we will attempt to predict
the price movement for a Universal Time Coordinate (UTC) day based on the information from
the previous day, or previous days. The tweet information was procured from a Kaggle dataset.

For example, we may aggregate the sentiment from the previous day to see if it correlates to a
price movement the following day. The price movement will be calculated as the difference
between the ‘close’ price and the ‘open’ price of Bitcoin as provided by Yahoo Finance.

## 2.4 Limitations
The first major limitation comes from the dataset employed, the dataset may not be entirely
representative of twitter activity during the period it covers, it may contain errors and is limited
in both time and scope. In time, any relationship we identify, or not, may not hold true for
different time periods and since it is limited to tweets containing ‘Bitcoin’ or ‘BTC’ it does not
provide information such as the interest in Bitcoin compared to the overall activity on Twitter.
- Kaggle: Bitcoin tweets – 16M tweets, https://www.kaggle.com/alaix14/bitcoin-tweets-20160101-to-20190329
- Historical Price of Bitcoin at Yahoo Finance: https://ca.finance.yahoo.com/quote/BTC-CAD/history?p=BTC-CAD

The second limitation comes from the nature of tweet data itself; it is incredibly ‘dirty’ both in
terms of how it was produced and in terms of content. A very large proportion of “users” in the
dataset are bots. Comparing to other datasets and projects, it has been noted that up to half of
the users tweeting about coronavirus was from bots9 and we would not be surprised that it would
be worse for cryptocurrencies. There are bots simply retweeting the price information, others
trying to push pyramidal schemes, phishing, or other scams

Meanwhile, even ‘human’ users will use language that is far from grammatically sound English. Tweets may also be in different
languages or multiple languages, may contain misspelling, special characters or emojis; all which
pose a challenge to analysis.
The final limitation came from the amount of time, personnel availability, and computing
resources available for this project that would have enabled us to explore many other
hypotheses, models, and a more rigorous exploration of the problem space. As such, our project
should be considered as a Proof-of-Concept and fact-finding exercise whereas we will identify if
we can successfully predict the price movement of Bitcoin and, if not, what avenues have been
explored as well as further options that may be investigated
