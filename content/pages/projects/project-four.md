---
type: ProjectLayout
title: 'Top College Restaurants: Metro Detroit vs. NYC'
date: '2025-01-20'
client: ''
description: >-
  How do restaurants that are most frequented by college students in the three
  major college cities in Metro Detroit stack up against a college town like New
  York, NY?
bottomSections: []
metaTags: []
colors: colors-a
featuredImage:
  type: ImageBlock
  url: /images/1.png
  altText: ''
  caption: ''
  elementId: ''
---
University students love restaurants. Whether they’re too busy studying to cook dinner or have burnt the family’s ravioli recipe in their kitchens--restaurants have become one of the saving graces of a busy college student. Nearly half of college students dine off campus every day, with almost 58% visiting a quick-service restaurant and 57% going to a coffee shop once a
1 week or more often.​


What I’ve set out to do is explore the restaurant scene in Michigan, and compare it to a city like New York. The locations chosen were based on my personal experience of attending schools in two cities (Wayne State University in Detroit and the University of Michigan in Ann Arbor) and frequently visiting Michigan State University in Lansing. It would be an interesting comparison to see how Metro Detroit restaurants measure up to the diverse restaurant scene in New York City. These conclusions are my own, but can provide some insight into the best food college cities in Michigan can provide.


**Data**


The data for the restaurants were pulled from the Yelp API, through multiple API calls to the cities that surround the universities in Michigan: Wayne State University is represented by Detroit; University of Michigan is represented by Ann Arbor and Ypsilanti; and Michigan State University is represented by East Lansing and Lansing.


The map below shows the 836 restaurants in Detroit. Downtown Detroit and Midtown are more populated.

![](/images/1.png)

The map below shows Ann Arbor having a high concentration of restaurants in Downtown and along Packard street.

![](/images/2.png)

The maps below show the large amount of restaurants in Downtown Lansing and East Lansing.

![](/images/3.png)

The map below shows many restaurants in Downtown and Midtown New York City.

![](/images/4.png)

**Analysis**


When looking at the most popular restaurants per campus, we see overlapping categories as Pizza, American (new), Mexican, Coffee & Tea, and Sandwiches. New York has a lot more variety of cuisines than the cities in Michigan.

![](/images/5.png)

However, since our demographic is college students, it would be a better comparison to look into restaurant categories that are at or under the two dollar sign ($$). For this price point, we find that pizza, sandwiches, Mexican, and coffee and tea appeared to be the most common among the four cities.


When we break down the review count and ratings for these four categories, we see that high review counts have a slight correlation with higher ratings in most of the cities. The outlier in Lansing is a Mexican restaurant called El Azteco, which has a high number of reviews since it’s close to the MSU campus and frequented by a lot of students.

![](/images/6.png)

Looking at the average prices and ratings for the categories, we see that the price point for more categories is similar--New York does lead the pack for piercing, but that was to be expected. New York has the highest ratings of pizza and coffee & tea, but Detroit is in second place, being tied for Mexican and sandwich ratings.

![](/images/7.png)

I was a little surprised to see that Ann Arbor didn’t rate as highly with “quick food” as Ann Arbor is known to have very good restaurants. But it was great to see that Detroit has the type of restaurants
at the New York level of good. Of course, this is still subjective, as New York still has more reviews and is more costly overall. We can see that Michigan cities don’t have as many diverse options, but they do provide a solid (3+ stars) rating for most of the general categories that students are likely to frequent.


Some limitations in the work included not having access to more granular information such as borough data since Google geocaching costs money. In addition, the Yelp API only allows for three reviews per restaurant, so it doesn’t provide too much information for any real sentiment analysis. I also tried scraping websites, but it was taking a very long time to get any reviews or borough data.

****

**References**
https\://www\.restaurant-hospitality.com/consumer-trends/trend-watch-90-college-students-eat-ca mpus-once-week
