# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends

### Overview of the Project
We have a Kickstarter dataset containing information on different cases from accross the world spanning from 2010 to 2017. Our data includes campaign data from start to finish. Some of the information includes, the campaign type, name, outcome, funding goal, and launch date. Our client, Louise, is planning to launch a campaign to help fund her play, Fever. Louise is looking to gain a better understanding on whether or not there are specific factors that make a campaign successful so she can set up campaign to mirror successful campaigns in the same category.

### Purpose
The purpose of this analysis is to identify how different Kickstarter campaigns fare in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The chart below shows theater kickstarter outcomes based on their launch date. Our data includes 1369 different theather campaigns and is categorized by its outcome; successful, failed, and canceled. With our data spanning from 2010 to 2017, it was determined best to organize the outcomes by month so we can determine the best time of year to launch a successful campaign. In order to have more concrete conclusion, we decided to leave out live campaigns because their outcome has not been decided. 

We see a big increase in success rate from April to May and, from there on, a steady decline of successful launches leading through December. 

![test](https://github.com/Jmsambaj/Kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The chart below shows kickstarter outcomes based on their funding goals. The data shows 1047 different Play campaigns organized by funding goal amount in intervals of $5000. There is no data on canceled campaigns so it will be easier to see the relationship of successuful vs failed campaigns. We also did not include live campaigns because their outcome have yet to be determined. 

There is an inverse relationship for Play kickstarter funding goals and their success rates. The campaigns with the highest success rates have lower funding goal amounts while the campaigns with the lowest success rates have higher funding goals amounts.



![test](https://github.com/Jmsambaj/Kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered



## Results

In conclusion, the best chance of having a successful theater Kickstarter campaign is to have the launch date set in the month of May. After May, there is a downwards trend of success rates as the year progressess. The least chance of having a successful theater Kickstarter campaign is to have the launch date set in the month of December. As for eastablishing a goal amount, The highest rate of success for Play kickstarter campaign goals is to have a campaign goal no more than $5000. A limitation to the data set is the most recent record being dated in 2017. We do not have any data from the last 3 years to further determine the most ideal launch date or goal amount to for a successul campaign. While we only used line graphs to illustrate our findings, we can utilize bar graphs as an alternative or linear regression lines in to further illustrate our data trends. 

When Louise decides to launch her campaign, I suggest she launch it during the month of May with a funding goal of $5000.
