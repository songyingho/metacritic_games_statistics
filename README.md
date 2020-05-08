# Metacritic All Time Games Statistics (1995 - 2018)

Student Name: Sandy Lee , Song Ying and James Lee

Project Background

This mod 3 project aims to hone skills in Pandas, EDA, SQL, web-scraping and MongoDB, 
followed by statistical concepts and skills such as independent t-test, dependent t-test, ANOVA etc 
in order to test three hypothesis. 

With Hypothesis tests, we could find out meaningful answers for the test (Alternative Hypothesis) or 
we would back up old traditional findings (Null Hypothesis). These analytical insights will be shared 
to company/stakeholder and they could use it to maximize their assets and minimize their costs.

Task 1 [Web-Scraping] 

We found an interesting dataset (in csv format) from Kaggle website. 
The dataset contains non-categorical columns and good number of games (20,381), 
so we can use number of different statistical tests in order to do Hypotheses testing. 

Task 2 [Data-Cleaning & Feature Engineering]

With the given dataset, we used Pandas for data cleaning.
Example 1): Since 97% of a column called “attribute” are non-values, we decided to delete that column.
Example 2): Only 10% of a column called “User Score” is missing, 
so we filled the missing data values with a random number within appropriate range. 

In conclusion, final dataset of columns consisting of:
* Name, Platform, Developer, Publisher, Genre, Rating, Release year, Critics score, User score

Task 3 [SQL] 
We converted them into dataframes and then created a database using sqlite.

Task 4 [Hypothesis Tests]
Hypothesis is generated about a population parameter, and sample statistics are used to assess the likelihood that the hypothesis is true. 
The hypothesis is based on available information and the investigator's belief about the population parameters. 
In order to process hypothesis testing, we set up the null hypothesis(H0) and the alternate hypothesis(H1).

Hypothesis 1 (ANOVA Test)

Due to the introduction of new genre in 2015 , expectation of potential customers towards the games is high. 
Thus, they might give lower rating to Action game.

H0 : The user rating of Action in Year 13-14 , Year 15-16 and Year 17-18 have no differences.
H1 : The user rating of Action in Year 13-14 , Year 15-16 and Year 17-18 have a clear difference.

Hypothesis 2 (ANOVA Test)

We suspect that influence of well-known pubishers whihin game industry are high and 
employee of those publishers might be one of the panel of critics who gives the score of the games.
Thus, we would like to find it out.

H0: Well-known game pubishers (Ubisoft, Atlus, Zen Studios) do not influence the critic's score
H1: Well-known game pubishers (Ubisoft, Atlus, Zen Studios) does influence the critic's score

Hypothesis 3. (Welch's T - test)

We believe that If we like something good (ex. foods from Michelin starred restaurants or Chanel etc) then, we would think that other people would like it too.

With the same logic, we might believe that If we like that particular game, then, we would think that other people would like it too.
However, Review Scores are rated from subjective view points of individuals and Gaming publishers could lobbying to Critics and influence the scores.

Therefore, we decided to check whether Users and Critics give Similar Scores in PC games. From this result, we would expect to advise Gaming companies whether they should value the critic review or not. 

H0: Users and Critics give similar scores in PC games
H1: Users and Critics DO NOT always give similar scores in PC games.

Task 5 [Findings & Analysis]
1. Since there is no difference before and after the introduction of “ Battle Royal”
We recommend the gaming company to carry on their genre of games. 
However, the growth of Battle ground games are very fast, we recommend them to monitor it.
  
2. We can confidently say that it is highly likely that not only do reviewers consistently rate 
PC games higher than users, but they do so significantly. 
What this means for the business is that we should continue to 
divert existing levels of PR funding into engaging with professional reviewers.  

3. Zen Studios perform significantly well against Atlus and Ubisoft, so Zen Studios 
may be a better publisher for the business upcoming new game, 
however more analysis should be done to compare the publishing cost, 
distribution channel and sales figure by 3 of the leading gaming publishers.


Task 6 [Limitations & Improvements] 
   
i) Due to insufficient spending data by publishers, there might be a doubt on the validity of the user/critic scroes.
    International game publishers have an abiity to spend more money on maketing which might influence critics, whereas small-to medium companies cannot.

ii) We assumed that good review(scores) of games would increase sales of the game. 

[ Important Note ]

1) Metacritic website has their own way to calculate the score.
   (Metacritic's scoring converts each review into a percentage, either mathematically from the mark given, or which the site decides      subjectively from a qualitative review. Before being averaged, the scores are weighted according to the critic's fame, etc)
