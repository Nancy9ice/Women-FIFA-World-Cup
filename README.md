# Women-FIFA-World-Cup
*This is a project by the Data Titans team that won the Women in Data Africa Datathon 2023. It portrays our skills in statistical analysis and data storytelling*

**Team Name: Data Titans**

**Team Members: [Nancy Amandi](https://github.com/Nancy9ice) and [Kaosarah lawal](https://github.com/Kaosarah)**

![](Women%20FIFA%20World%20Cup%20Image.jpg "Image by @benwiththelens on Unsplash.com")

*Image by [Ben Weber](https://unsplash.com/@benwiththelens) on Unsplash*

## Introduction

According to the Women In Data Africa (WIDA) datathon challenge, we were expected to gain valuable insights into the evolution of women's soccer over the years, the performance of the top teams and players, and/or the strategies used by coaches to succeed in this highly competitive sport. 

However in our analysis, we decided to focus on the strategies that most teams use to win.

## Problem Statement

What strategy is most likely to turn a football team to the champion in the women FIFA world cup?

## Skills/concepts demonstrated

The following tools and skills were used in this project:

* **Python** used to wrangle the data.
* **PowerBI** used to design the visualizations and dashboard.
* **Statistical Modelling** used to reject or accept the generated hypothesis.

## Data Sourcing

It was a one table dataset gotten from the [kaggle website](https://www.kaggle.com/datasets/mattop/fifa-womens-world-cup-stats/versions/1?resource=download).

## Data Transformation/Cleaning

The data was efficiently cleaned and transformed using Python. Some of the steps are listed below:

* Conversion of the data types of some variables

* Replacement of null values with the median values of that associated variable by team

* Attempt to remove duplicates

* Detection of outliers by the Interquartile range method

* Capping of outliers using the Winsorization method

* Derivation of the "champions", "hosts", and "distance_in_miles" variables. 

## Methodology

* Domain knowledge acquisition

* Generation of problem statement

* Data transformation/cleaning

* Univariate analysis

* Bivariate and Correlation analysis

* Hypothesis (Null hypothesis) generation

    * Goals has no effect on teams winning the women FIFA world cup

    * Assists has no relationship with goals scored

* Statistical Modelling 

    * Logistic Regression

    * Linear Regression

## Analysis and Visualizations

[![Women FIFA World Cup Dashboard Image](Women%20FIFA%20World%20Cup%20Dashboard%20Image.PNG)](https://app.powerbi.com/view?r=eyJrIjoiM2Q0ZTYyOWMtOWRkNC00YWI4LTg0OWItMWI0NzYzZmQzYmFlIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

***Click the image to be redirected to the interactive dashboard***

According to our dashboard, here are the following observations:

* So far, there have been 8 tournaments but 4 unique champions.

* USA, Germany, Japan, and Norway have won 4, 2, 1, and 1 times respectively. 

* There is a direct relationship between assist and goals except in the years 2015, 2007 and 1991. 

* The bar charts of assists and goals that lay side by side have the same pattern as regards the position of the champion teams where USA, Germany, and Norway are in top 3 while Japan is at the 9th position. 

* A click through the interactive dashboard reveals that every champion team always have the highest number of assists and goals in that year. However, there are exceptions in 2015, 2003, and 1995. 

## Conclusions and Recommendations

* 5 out of the 8 tournaments (the majority) align with our conclusion: Assists have a direct relationship with Goals.

* Assists is a measure of team play. Hence coaches of each team should do the following to promote team spirit in their teams to increase their chances of winning:

    * Make players undergo drill exercises where they have to rely on each other to scale through

    * Set measurable goals for team work like keeping track of the goals that had assists

    * Understand the strengths and weaknesses of players and put them in strategic positions where the strengths of one player complements the weakness of the other player beside her. This will make it easier for team work to reflect in the team

    * At the end of the training match, the coach should go extra mile in calling out specific actions exhibited by some players that expressed team spirit. This will make players more team spirit conscious during the game

    * Engage the players in team building activities

    * Make every player feel heard and seen

## Acknowledgements

Special thanks to my teammate, [Kaosarah](https://github.com/Kaosarah), for working with me to make this project a huge success. 

Thank you to the [Women in Data Africa Community](https://twitter.com/WomenInDataAfri) for hosting this Datathon and giving us the opportunity to learn so much more than we expected. 



