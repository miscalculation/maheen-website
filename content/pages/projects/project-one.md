---
type: ProjectLayout
title: Sentiment Analysis of @POTUS
colors: colors-a
date: '2020-05-01'
client: ''
description: Sentiment analysis of Trump and Obama's tweets during their time in office.
featuredImage:
  type: ImageBlock
  url: /images/potus.jpeg
  altText: Trump and obama
media:
  type: ImageBlock
  url: /images/potus.jpeg
  altText: ''
---
<https://github.com/miscalculation/sentiment-analysis-potus>

In the past decade, there has been much interest in the area of sentiment analysis, especially with regards to tweets. In our research, we focus on analyzing and predicting the sentiment of the past two presidents, Donald Trump and Barack Obama. Using three types of different classifier, we predict whether a tweet is positive, neutral, or negative, and evaluate our models using the F1 score and accuracy measures. The dataset used for training our models was taken from data.world and included tweets spanning from 2009 to 2016, when Trump was elected president. We use these predicted tweets to conduct deseasonalized time series analysis on the frequency of tweets for each president to explore specific time periods and the majority tweet sentiment for each president, as well their overall sentiment. We find that the Logistic Regression was the best-performing in both evaluation measures, for both presidents. Also, Trump’s tweets tend to be mostly positive before 2015, after which they become mainly neutral, while Obama’s tweets maintain their predominantly neutral sentiment throughout this time period.

![](/images/Obama_Trump.png)

![](/images/671%20Poster%20Final.jpg)
