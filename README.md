# Stock-Market-Sentiment-Analysis
Analyzed stock market sentiment tweets to obtain top 3 gaining and top 3 losing stocks using R statistical tool and twitter API.


## Stocks Chosen
Gainer Stocks:
WINS – Wins Finance Holdings Inc.
NAV – Navistar International Corp
PTLA – Portola Pharmaceuticals

Loser Stocks:
UBIA – UBI Block Chain Internet Ltd
FDS – Factset Research Systems Inc.
SLCA – US Silica Holdings Inc. 


## Libraries Installed
install.packages("twitteR")

install.packages("ROAuth")

install.packages("tm")

install.packages("SnowballC")

library("twitteR")

library("ROAuth")

library(tm)

library(wordcloud)

library(SnowballC)


## Sentiment Score
We characterize the text by positive and negative words.
A positive score means that the text is characterized by positive words.
A negative score means that the text is characterized by negative words.

We have two files which consists of Positive and Negative words.
