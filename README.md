# pandas-challenge
Bootcamp HW 4 - Pandas
Congratulations! After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.
Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.
Your final report should include each of the following:

## Player Count

*Total Number of Players


## Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue


## Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed


# Purchasing Analysis (Gender)

The below each broken by gender

* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person by Gender



## Age Demographics

The below each broken into bins of 4 years (i.e. <10, 10-14, 15-19, etc.)

* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person by Age Group


## Top Spenders

Identify the the top 5 spenders in the game by total purchase value, then list (in a table):

* SN
* Purchase Count
* Average Purchase Price
* Total Purchase Value




## Most Popular Items

Identify the 5 most popular items by purchase count, then list (in a table):

* Ttem ID
* Item Name
* Purchase Count
* Item Price
* Total Purchase Value




## Most Profitable Items

Identify the 5 most profitable items by total purchase value, then list (in a table):

* Item ID
* Item Name
* Purchase Count
* Item Price
* Total Purchase Value


--------------------------------
# Results

HeroesOfPymoli.jpynb contains the results for the required lists. Using the resulting tables, we can see three trends emerging from the data:

## Age Demographics
The highest percentage of players (44.79%) are in the age range of 20-24, coming in at 258 of 576 players in the data set. The second highest percentage of players (18.58%) are in the 15-19 age range. That means that the majority of players who have bought an item in-game (66.37%) are in the age group of 15-24. The players of this game that will spend money after the initial purchase of the game tend to be young adults.

## Spending Habits of Players
Of the 576 players, we can see that no individual has spent more than $20 on additional content for the game. The highest recorded total purchase value was by the screen name Lisosia93, who bought 5 items for a total of $18.96. Most players in this data set (of the players who actually purchased something) only bought one item. 

## Item Popularity
The item that appears to be the most popular as well as the most profitable for the company is Oathbreaker, Last Hope of the Breaking Storm. It was purchased 12 times in the data set, 3 more times than any other item. Looking at the lists of the most popular items and the most profitable items, many items reappear near the top of the list. We can probably assume that popularity and profitablity have a relationship with each other. The more popular an item is, the more times it has been purchased, and each purchase increases the profits for the company. 
