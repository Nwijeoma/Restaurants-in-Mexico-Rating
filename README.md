# Restaurants in Mexico Rating by Ijeoma Nwosu
![](food.jpg)
---
## Introduction
This data set is called the restaurant rating dataset which contains information about restaurants in
mexico. A customer survey was carried out in this city in 2012 to collate information about each
restaurant, their cuisines, information about their consumers and the preferences of the consumers.

**The Report consists of four pages imbedded in 4 buttons on the dashboard**
1.	Consumer demographics
2.	Consumer analytics
3.	Restaurant overview
4.	Restaurant analytics

## Problem statement

**Question 1**
What can you learn from the highest rated restaurants? Do consumer preferences have an effect on
ratings?

**Question 2**
What are the consumer demographics? Does this indicate a bias in the data sample?

**Question 3**
Are there any demand & supply gaps that you can exploit in the market?

**Question 4**
If you were to invest in a restaurant, which characteristics would you be looking for?

## Data  source
https://drive.google.com/file/d/1c1HKM8UTqwWOgexRLOtEJuxjBiA2N6xf/view?usp=drive_link 

## Skills demonstrated
Data Transformation/Cleaning Data was efficiently cleaned and transformed with the Power Query Editor of Power BI.

**Some of the applied steps included DAX Concepts**
a.	**Conditional column** was used to create a new column ‘Age range’ ages of all the passengers were grouped into 10groups. 0-10, 11-20, 21-30, 31-40, 41-50, 51-60, 61-70, 71-80 and 81-90
![](agerange.png)
---
b.	To replace empty cells with N/A 
________________________________________
c.	Measures in DAX was also used to calculate the total number restaurants, cuisines, consumers, average overall rating, average food rating and average service rating.

## Data Modelling
The 5 tables were connected resulting in a star schema model.
![](model.png)
---

## Visualization 
The Report consists of four pages imbedded in 4 buttons on the dashboard
1.	Consumer demographics
2.	Consumer analytics
3.	Restaurant overview
4.	Restaurant analytics

![](custdem.png)
---
![](custana.png)
---
![](restana.png)
---
![](Restrev.png)
---

Utilizing stacked pie charts, clustered column charts, stacked column charts and 100% stacked bar chart, for effective comparisons and trend, slicers and visual cards were also included to better functionality and better dashboard interaction These components collectively form an interactive and intuitive report, fostering enhanced comprehension and examination of the survey results. Thoughtful attention to accurate labeling, color choices, and relevant annotations ensures that the visuals are easily comprehensible for the audience.

## Insight
Total consumer population is 138
Generally Restaurants in Mexico had an:
- Average overall review of 1(satisfactory)
- Average food rating of 1.22
- Average service rating of 1.09

 **Consumer demographics** 
 
1. 83.3% of the consumer population falls under the age range '21-30', 95 are single, 6 are married.
2. 59.4% of the customers commute via public transport, 25.4% use private cars and 10% walk to the restaurant.
3. 62.3% of the consumer population resides in San luis potosi.
4. 81.9% of the consumers are students, 11.6% are employed while 1.4% are unemployed.
5. 34.06% consumers were casual drinkers, 36.96% consumers were abstemious drinkers (abstemious meaning moderate) while 28.99% consumers were social drinkers. All the consumers are drinkers but with varying drink levels.

 **Consumer analytics**
 1. 65.9% of the consumers had a medium budget, 3.6% of the consumers had a high budget while 25.4% consumers had a low budget.
 2. Most of the customers chose Mexican cuisine as their most preferred cuisine with students constituting 89.2% of this group.
 3. Age range '21-20' which has the highest number of consumer population (83.3%) had the lowest ratings when compared to other age range groups, with overall average rating of 1, Average food rating of 1.16 and average service rating of 1.04

 **Restaurant overview**
 1. 66.9% of the restaurants in the dataset do not offer alcohol service, 26% of the total restaurants offer wine and beer in their restaurants while 6.9% of the restaurants offer a full bar.
 2. 46.2% of the cuisines had a medium price, 34.6% had a low price, 19.2% had a high price. This analysis is consistent with the budget of the consumers.

 **Restaurant analytics**
 1. Mexican cuisine holds top preference exerting a significant influence on restaurant due to its consistently high rating compared to other restaurants.

 **A. What can we learn from highest rated restaurant?**
 
 The highest rated restaurant is **'Restaurant Las Mananitas'** it had an overall rating of 2, Food rating of 2 and Service rating of 2 and this is the only restaurant amongst the 130 restaurants with a perfect rating.
 Restaurant Las Mananitas is located in Cuernavaca, which has 22 customers (16% of the population), 21 restaurants and 9 out of these restaurant, had an overall rating of 2.
 Regardless of its low number of customers and high price budget, the restaurants have good ratings which tells us that they are running very profitable business. 

 **B. What are the Consumer demographics? does this create a bias in the data sample**
 
 from the consumer demographics earlier discussed, it shows that age range '21-30' who are single accounts for the highest consumer demographics, this indicates a bias to the data sample.

 **C. Demand and supply gaps that can be exploited**
 
  1. All the consumers are drinkers but with varying drink levels, yet only 6.9% of the restaurants offer a full bar and 66.9% of the restaurants in the dataset do not offer alcohol service. offering more options of providing alcohol will inevitably increase revenue generated.
  2. The most preferred cuisine is Mexican cuisine, which shows close to 100% of the restaurants showuld be offering this cuisine.

 **D. If you were to invest in a restaurant, which characteristics would you be looking for?**
 
 1. Population size of the customers
 2. Average ratings which cuts across, the food rating, service rating and the overall rating.
 3. Demographics of the consumers
 4. Level of pricing of the restaurant.
    
and going by these characteristics, i would invest in Restaurants in San Luis Potos, as it has
* The highest percentage of restaurants 62.3%
* Highest consumer percentage of 60.8%
* Medium pricing levels
  
**Recommendations**
1. **Transport coupon** - one valid for only public buses which can be provided once weekly.
 As shown from the data most of the customers commute with public transport, therefore showing them that you care and are willing to give them a memorable experience would defintely increase ratings, customer satisfaction, customer retention and revenue generated.

2. **Online Presence** - creating a social media page, where you can showcase the restaurants cuisines would also increase awareness especially for the age range '21-30' which has shown to be social media inclined. make the restaurants be a place they would always want to dine.
