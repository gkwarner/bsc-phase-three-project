# Phase Three Project Repo
### Authors: Gabriel Warner, Charlie Fountain, Will Toranto

## Overview:
### Predictive model of PGA tour players performance to determine if they should be considered for a sponsorship or not to maximize the companies profit. 

## Business Problem:
### Callaway golf team has came to us looking for new players to sponsor. They want us to analyze data and determine which players are worthy of a sponsor. In order to make a useful model predicting which players should be sponsored, we had to acknowledge that many of the top end players  already have sponsors. We determined that using improvement over the years would show the Callaway team which players are most likely to keep getting better, therefore deserve a sponsorship. 

## Data:
### The pgaTourData from Kaggle was used for our analysis.  This data set contains 18 columns and 526 unique players from 2010-2018.  We removed rows with missing data and filtered the money column to only include players who have made over $500000.  After this, we had 438 unique players.

## Comparisions:
### We examined the correlation between different targets such as Money, Wins, and sponsorship with the features.  This helped us answer questions such as how much a player should get paid based on how they play, if a player will win a tournament, and if a player should receive a scholarship or not.

## Results:

![Money_and_acg_scarmbin_correlation](./images/Money_and_acg_scarmbin_correlation.png)
### As average scrambling increses money also increses.
#
#
![Money_and_gir_correlation](./images/Money_and_gir_correlation.png)
### As gir increses Money also increses.
#
#
![Money_avg_distance_correlation](./images/Money_avg_distance_correlation.png)
### There is a moderate positive correlation between money and avg distance.
#
#
![Money_avg_SG_total_correlation](./images/Money_avg_SG_total_correlation.png)
### There is a strong correlation between Money and avg SG total 
#
#

![Money_and_average_score_correlation](./images/Money_and_average_score_correlation.png)
### As average score increses Money decreses.



### For our predictive money model, multiple machine learning models were used.  The graph shows that the logistic regression model had the best training and validation scores and the least difference.

![Money_and_average_score_correlation](./images/Money_and_average_score_correlation.png)
### As the average score increases, money decreases.
![Money_Precission_Score_Graph](./images/Money_Precission_Score_Graph.png)
#### For our money model, multiple machine learning models were used.  The graph shows that the logistic regression model had the best training and validation scores and the least difference.

# Conclusion:
#### Players that showed improvement over the eight years based on score and performance should be considered for a sponsorship: the amount paid increases, and performance increases.  