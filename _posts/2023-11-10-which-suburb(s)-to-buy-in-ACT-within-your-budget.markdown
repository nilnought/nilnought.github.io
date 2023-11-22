---
layout: post
title:  "Which suburb(s) to buy in Canberra Australia within your budget"
date:   2023-11-10 08:09:06 +1000
category: Australian property analysis
---

There are more than 100 suburbs in Canberra and most of the property inspections are on Saturdays. So which suburb(s) should you focus on? This post shows how you can identify which suburb(s) to buy within your budget. It only examines the detached houses as land, in our opinion, will become more valuable due to its scarcity. 

## Grouping suburbs

Since there are so many suburbs. Why not group them first and see which ones are similar? We fed <a href="https://dbr.abs.gov.au/region.html?lyr=sa2&rgn=801011001">the ABS income and employment industry data from the year 2015 to the year 2019</a> into the Fuzzy C-means (FCM) clustering method and grouped all the suburbs into 9 assignments.  

<iframe src="https://nilnought.github.io/plots/clustering_employment_income_NC9.html" width="100%" height="700"></iframe>

For example, it seems that Aranda, O'Connor, Ainslie, Reid, Campbell, Barton, Griffith, Garran, Hughes, Curtin, Isaacs and Chapman are similar in terms of income and employment industries. After having an understanding of the similarities between suburbs then comes the next question, which suburb(s) can you afford with your budget?  

## Within your budget?

The chart below displays the likelihood of affording a house within your budget, based on the recent sales[^1] from January to September 2023. The darker the color the higher chance of affording a house. You can slide the budget scrollbar at the bottom, which ranges from $800k to $1.8m. The default display is at $1.8m. If a suburb is not shown, that means there has not been a house sale within that price range. You can click a suburb to highlight its statistics. Take Florey as an example. Between January and September 2023, there have been 17 houses sold, their median price is $1m and all the sale prices are below $1.8m so if your budget were $1.8m, the likelihood of you affording a house there would be 100%. Take Braddon as another example. Although the median price is $1.6m, because there has been one sale above $1.8m, the likelihood of affording a house there would be 50% with the same budget $1.8m.  

[^1]: Number of sales in this analysis may be fewer than the actual number sold due to data cleansing 

<iframe src="https://nilnought.github.io/plots/budget_chance.html" width="100%" height="700"></iframe>

If you had $1.2m in mind as your budget, you could either wait longer for a house to appear in a more expensive suburb like Griffith or choose a similar but cheaper suburb like Aranda.  
 
