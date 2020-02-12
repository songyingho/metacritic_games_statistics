Metacritic All Time Games Statistics (1995 - 2018)

Student Name: Sandy Lee , Song Ying and James Lee

Project Background

This mod 3 project aims to hone skills in Pandas, EDA, SQL, web-scraping and MongoDB, 
followed by statistical concepts and skills such as independent t-test, dependent t-test, ANOVA etc 
in order to test three hypotheses. 

With Hypotheses tests, we could find out new meaningful answers for the test (Alternative Hypothesis) or 
we would back up old traditional findings (Null Hypothesis). These analytical insights will be shared 
to company/stakeholder and they could use it to maximize their assets and minimize their costs.

Task 1 [Web-Scarping] 

We found an interesting dataset (in csv format) from Kaggle website. 
The dataset contains non-categorical columns and good number of games (20,381), 
so we can use number of different statistical tests in order to do Hypotheses testing. 

Task 2 [Data-Cleaning]

With the given dataset, we used Pandas for data cleaning.
Example 1): Since 97% of a column called “attribute” are non-values, we decided to delete that column.
Example 2): Only 10% of a column called “User Score” is missing, 
so we filled the missing data values with a random number within appropriate range. 

In conclusion, final dataset of columns consisting of:
* Name, Platform, Developer, Publisher, Genre, rating, release year, Critics score, User score

Task 3 [SQL] 
We converted them into dataframes and then created a SQL query which basically meant joining tables … 
alongside their ratings and subsequently selected only relevant columns….

Task 4 [Hypothesis Tests]
Hypothesis is generated about a population parameter, and sample statistics 
are used to assess the likelihood that the hypothesis is true. 
The hypothesis is based on available information and the investigator's belief about the population parameters. 
In order to process hypothesis testing, we set up the null hypothesis(H0) and the alternate hypothesis(H1).

Hypothesis 1. 

H0 :
H1:

Hypothesis 2. 

H0:
H1:

Hypothesis 3.

H0:
H1:

Task 5 [Findings & Analysis]

##One selects a random sample (or multiple samples when there are more comparison groups), 
computes summary statistics and then assesses the likelihood that the sample data 
support the research or alternative hypothesis. 
Similar to estimation, the process of hypothesis testing is based on probability theory and the Central Limit Theorem.  
This module will focus on hypothesis testing for means and proportions. 
The next two modules in this series will address analysis of variance and chi-squared tests. ##

Task 6 [Limitations & Improvements]

•For some games, only few users rated “User score” of the game. 

Therefore, the score is from such a subjective opinion and it might not have a significant meaning in terms of statistics. 
Ex) A game called “Marvel's Guardians of the Galaxy” has a user score of “7.1” 
which is regarded as a good game or fairly recommended game. 
However, the score of “7.1” is derived from a single user. 
