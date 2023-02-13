# World_Cup_Analysis


## Overview of the Analysis:

### Resources Used:
Source: https://www.kaggle.com/datasets/evangower/fifa-world-cup
Source: https://www.kaggle.com/code/shivan118/fifa-world-cup-data-analysis/notebook#Most-Number-of-World-Cup-Winning-Title
Source: https://www.kaggle.com/datasets/abecklas/fifa-world-cup?resource=download

Python. . .
Jupyter Notebook . . .
Matplotlib . . .
PostgreSQL . . .

## Questions to Answer:
1. Have goals generally increased or decreased from cup-to-cup? Do they generally increase or decrease at different stages of the tournament?
2. Which country had the best performance while acting as host for that year's World Cup?
3. Which host city has seen the most exciting matches? Which host city has been the most disappointed with boring matches?
4. Are there any trends in attendance? (Cup-to-Cup, City-to-City, Stage-to-Stage)
5. What is the best performance each country has ever had while participating in the World Cup?
6. On average, which teams make it to the furthest stage in each World Cup?
7. Which teams have appeared in the most World Cups?
8. Which teams have advanced past the group stage the most?
9. Which matchups are the most common/have the most history for each team?
10. Which matchups have each team struggled with the most/could be considered their biggest rivalrys?
11. Which team has scored the most total goals in all of their World Cup appearances?
12. Which team averages the most goals for/against in their matches?
13. Which teams have pulled off the most comeback wins after being down at 45 minutes?

## Results:

### 1. Have goals generally increased or decreased from cup-to-cup? Do they generally increase or decrease at different stages of the tournament?

To answer the first part of this question, it appears goals have trended downwards each year, with a peak in 1950 as can be seen below. Interestingly we can break this data down even further and filter by half and by winners/losers to see more trends. For instance, the average goals by losing teams has remained relatively stable around 1 goal in a loss, while the average goals for winning teams is what seems to be trending downwards, from 4 goals in the 30's/40's to 3 goals in the modern day. Essentially the data shows that matches are getting closer, either due to weaker offense from winning teams or stronger defense from losing teams.

To answer the second part of the question, the losing teams appear to consistently score more and more goals as the tournament progresses, likely due to the fact that weaker offensive teams have been eliminated and do not participate in the later stages. However the winning team goal trend is not as straightforward, as it dips to its lowest point in the middle of the tournament before rising to a peak in the final stages. The consistent rise from Round of 16 through the Finals can likely be explained in a similar fashion, with better teams making it further in the tournmanet. The anamoly in the group stages however may be in part to the weakest teams being present, and are much more likely to lose by the largest margins (i.e. more 'blowout' wins are possible here).

Charts detailing these trends can be found by clicking the link below.

[Average Score Graphs](Analysis/Year-to-Year/). 


### 2. Which country had the best performance while acting as host for that year's World Cup?
There are several countries who have won the World Cup while also acting as the host country. These nations are Brazil, Uruguay, England, Argentina, and Italy. Sweden almost made this esteemed list, but sadly lost in their final match. 

The full list of host results can be found at the link below.

[Host Results](Analysis/Country_Comparisons/Host_Data/Best_Results_as_Host.csv)

### 3. Which host city has seen the most exciting matches? Which host city has been the most disappointed with boring matches?
First, it should be stated that match excitement is not directly correlated to amount of goals scored. Rather this question could be phrased to state "Which cities have seen the most/least goals scored?"

The easier question to answer is to state that the worst cities to attend a World Cup match are Palermo, Italy and Vigo, Spain. Each of these cities have hosted 3 matches, but have yet to see a team score any goals in their stadiums. The slightly more abstract question asks which city has seen the most goals. While the most goals title would be held by Montevideo (70 total goals), to only look at the sum seems unfair to the spirit of 'most high-scoring matches'. To that end we can find the average goals in each city. However that would bestow the title to Strasbourg, France (a potential anomaly, with 11 goals-per-game in one single game). To account for both factors (high total goals AND a high goal-per-game average), we can find two cities from Switzerland, Basel and Zurich. These cities both boast roughly 6 goals-per-game, while having a decent sample size of 5+ matches played in their cities.

More extensive lists of city results can be found at the links below.


[Least Goals](Analysis/Country_Comparisons/Host_Data/Least_Exciting_Host_Cities_(Average_Goals).csv)
[Most Goals](Analysis/Country_Comparisons/Host_Data/Most_Exciting_Host_Cities_(Average_Goals).csv)


### 4. 


### 5.


### 6.


### 7.


### 8.


### 9.


### 10.


### 11.


### 12.


### 13.

# Potential Errors
Russia/Soviet, EastGer/WestGer/Germany, etc.
No 1942/1946 WCs

Fix host city dataframe to show years in which the country obtained that result