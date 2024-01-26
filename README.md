# Cricket Best 11 Players Analysis

## Overview

The Cricket Best 11 Players Analysis project aims to identify the top-performing cricket players in the T20 World Cup 2022 and assemble the best 11 players for a hypothetical cricket team. Leveraging web scraping techniques in Python and data visualization capabilities in Power BI, this project provides insights into player performance, strengths, and contributions to their respective teams.

## Introduction
Selecting the best 11 players for a cricket team requires thorough analysis and consideration of various factors such as batting, bowling, fielding, and overall performance. The Cricket Best 11 Players Analysis project utilizes  the json fies which we got from web scraping techniques to gather player statistics and performance data from the ESPN website, followed by data analysis and visualization using Power BI.

## Technologies used
- Python
- Jupyter Notebooks
- Pandas
- json
- Power BI



## Steps Followed 

- Converting json to csv: Converting json file got from web scraping to csv files using python's json and pandas library.
- Data Cleaning and Preprocessing: Prepare and clean the scraped data to ensure accuracy and consistency.
- Player Performance Analysis: Analyze player statistics, including batting averages, bowling averages, strike rates, and fielding performances.
- Best 11 Selection: Identify the best 11 players based on their individual performances and contributions to their teams.
- Power BI Visualization: Visualize player statistics, team compositions, and performance insights using Power BI dashboards and reports.

## Expected Outcome
- The team should be able to score atleast 180 runs on an average
- They should be able to defend 150 runs on an average

## Parameter Scoping

## OPENERS
|  PARAMETERS       | DESCRIPTION | CRITERIA |
| :---------------- | :------: | :----: |
| Batting Average        |   Average runs scored in an innings   |>30 |
| Strike Rate           |   No of runs scored per 100 balls   | >140 |
| Innings Batted    |  Total Innings batted   | >3 |
| Boundary % |  % of runs scored in boundaries   | >50 |
| Batting Position    |  Order in which the batter played   | <4 |


## ANCHORS / MIDDLE ORDER
|  PARAMETERS       | DESCRIPTION | CRITERIA |
| :---------------- | :------: | :----: |
| Batting Average        |   Average runs scored in an innings   |>40 |
| Strike Rate           |   No of runs scored per 100 balls   | >125 |
| Innings Batted    |  Total Innings batted   | >3 |
|  Avg. Balls Faced | Average balls faced by the batter in an innings   | >20 |
| Batting Position    |  Order in which the batter played   | >2 |


## FINISHER / LOWER ORDER ANCHOR
|  PARAMETERS       | DESCRIPTION | CRITERIA |
| :---------------- | :------: | :----: |
| Batting Average        |   Average runs scored in an innings   |>25 |
| Strike Rate           |   No of runs scored per 100 balls   | >130 |
| Innings Batted    |  Total Innings batted   | >3 |
|  Avg. Balls Faced | Average balls faced by the batter in an innings   | >12 |
| Batting Position    |  Order in which the batter played   | >2 |


## ALL-ROUNDERS / LOWER ORDER 
|  PARAMETERS       | DESCRIPTION | CRITERIA |
| :---------------- | :------: | :----: |
| Batting Average        |   Average runs scored in an innings   |>40 |
| Strike Rate           |   No of runs scored per 100 balls   | >125 |
| Innings Batted    |  Total Innings batted   | >3 |
| Batting Position    |  Order in which the batter played   | >4 |
|   Innings Bowled          |   Total Innings bowled   | >2 |
| Bowling Economy    |  Average runs allowed per over   | <7 |
|  Bowling Strike Rate    |  Average no. of balls required to take a wicket   | <20 |

## SPECIALIST FAST BOWLERS
|  PARAMETERS       | DESCRIPTION | CRITERIA |
| :---------------- | :------: | :----: |
|   Innings Bowled          |   Total Innings bowled   | >2 |
| Bowling Economy    |  Average runs allowed per over   | <7 |
|  Bowling Strike Rate    |  Average no. of balls required to take a wicket   | <20 |
|    Bowling Style          |   Total Innings bowled   | "%fast%" |
| Bowling Average    |  Average runs allowed per wicket   | <20 |
|  Dot Ball %    |  % of dot balls bowled   | >40% |

## Final Dashboard Preview

![image](https://github.com/sausau02/Cricket-Best-11/assets/157574244/d0c237ad-4833-47f7-a728-ab4684bbbfb2)


