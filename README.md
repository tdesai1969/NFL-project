# Project: Analyze NFL player career length and statistical data for potential Hall of Fame (HOF) induction.
## Project description outline:
Analyze NFL player data to answer the following questions:
What does it mean when they say a player’s career was cut short? 
What is the mean length and standard deviation of the seasons played for a set of offense players? 
What criteria would be best used to predict a future Hall of Fame candidate? (* Players)

## The data exploration and cleanup process
We identified many online sources; however, after quality analyses, they were rejected due to missing or incorrect data. The Pro Football reference site was used as it was the largest, most concise, and single source of information that we could identify.
https://www.pro-football-reference.com/play-index/psl_finder.cgi

Dataset – We took 30 years of data 
Data for 4 NFL positions focusing on QB, TE, WR, RB for all NFL teams. 
We downloaded the data, structure, and validated the data.
We used Jupyter Notebook and Pandas to clean and format the data and used Matplotlib plotting library to create various visualizations. 

## The analysis process
Compared and contrast a set of current offensive players (QB, TE, WR, RB) against the records of Hall of Fame players. This analytical process narrowed down the criteria to 3 key areas: yards gained, seasons played, and total career touchdowns. 
Created a series of scatter plots to visualize which of the current players are on target to be potentially inducted into the Hall of Fame. Layered the Hall of Fame players on top of those current players to illustrate if they were nearing the criteria. 
![qbscatterplot](Images/qb_scatterplot.png)
![scteatterplot](Images/te_scatterplot.png)
![scteatterplot](Images/wr_scatterplot.png)
![rbscatterplot](Images/rb_scatterplot.png)

We found mean, standard deviation, and Inner quartile range (IQR) of player career length and created a box plot using Matplotlib plotting library to understand the career length of player over the season.

![Boxplot](Images/players_boxplot.png)

## Conclusions
• Hall of Fame predictors for the offensive line positions RB, WR & TE would be recording over 8,000 yards gained and playing at least 7-9 seasons, for the QB positions would be recording over 30,000 yards passing and playing at least 11 seasons.
• If QB position career did not reach the median of 5 seasons, for WR and RB 3 seasons, and for TE 4 seasons then their career could be considered cut short.
