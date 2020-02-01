# Anatomy of CEOs on Twitter

### Introduction :

Twitter is a microblogging and social networking site. With growing twitter users, twitter can act as platform for CEOs to directly interact with customers. So tweets could be possibly influence how stock prices change in the short term like the immediate day etc. Intrigued by this thought, we went out to analyse tweets and see how it is making a difference on the company. Also we looked at tweeting styles of CEOs from various sectors like technology, finance, airline

### Technology :

Python 3.7.3
Libraries used : tweepy, spacy, genism, nltk, textblob

### Approach :

1.	Scrapped Twitter accounts of 31 CEOs of top 100 FORTUNE companies using twitter API and also extracted daily stock and financial statistics from Yahoo finance for the respective companies.
2.	Data pre-processing – Removed stop words, bigrams, lemmatization, word-frequency filters. 
3.	Sentiment analysis - Classified CEOs based on sentiment scores of tweet – positive, neutral and negative.
4.	LDA topic modeling on tweets to discover tweeting styles and topics tweeted about.
5.	Regressed stock price on - number of CEO attributes like (age, compensation etc), twitter attributes (tweeting style, number of tweets, number of likes, sentiment score) and company attributes (company statistics, daily returns, volume of stock traded etc.) 
6.	Engagement analysis using logistic regression to determine types of topics which increase engagement.

### Insights :

1.	It is unable to distinguish between genuine and sarcastic tweets using the method of  sentiment analysis. John Legere (T-Mobile) has a good number of sarcastic tweets directed towards his competitors but they were classified as positive.
2.	Aaron Levie turned out to be CEO with negative tweets, but with topic modeling he is a very generous and positive person on Twitter.
3.	Some tweeting styles of CEOs –
a.	Elon Musk uses his twitter account to talk about various products and uses it as a marketing platform
b.	Tim Cook tweets about current events and talks how apple is involved to help.
4.	When CEOs actively use twitter as a platform to show side of their part from being a company CEO who is promoting products customer engagement is high. 
5.	Influential CEOs can actually impact stock prices through tweets.  

### Recommendations :

1.	More company CEOs should take advantage of twitter as a platform to connect with customers directly.
2.	They should express about variety of other topics apart from their company or company products’. This way they can form an emotional connection and increase engagement

 


