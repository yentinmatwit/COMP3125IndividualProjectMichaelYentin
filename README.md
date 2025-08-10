# Boston Celtics Data Analysis
COMP3125 Individual Project – Summer 2025  
Author: Michael Yentin  
School of Computing and Data Science

## Project Overview
This project analyzes the Boston Celtics’ performance from 2000 to 2025 using historical team statistics, correlation analysis, coaching change evaluations, and predictive modeling. The goal is to identify the key statistical factors most strongly associated with winning, understand how coaching transitions have impacted performance, and assess the accuracy of predictive models for point differential. By combining time-series trends, statistical relationships, and regression analysis, the project provides a data-driven view of the Celtics’ competitive trajectory, offering insights that can be applied to strategic decision-making in professional basketball and future team decisions that will lead to success

## Dataset
The dataset used is bostoncelticsdata.csv, which includes:

Season and league information
Team records (wins, losses, win percentage, finish)
Advanced metrics (SRS, Pace, Relative Pace, Offensive/Defensive Rating, Relative ORtg/DRtg)
Playoff results and coaching information
Top player by Win Shares each season
Point differential per season 

### Columns:
Season
Lg
Team
W
L
W/L%
Finish
SRS
Win%
Pace
Rel Pace
ORtg
Rel ORtg
DRtg
Rel DRtg
Playoffs
Coaches
Top WS
PointDifferential

> Note: Data cleaning steps were applied to handle missing values and normalize time fields. 'PointDifferential' column was added by me

##  Methods Used
- **Descriptive Analysis**: Summarize and visualize key Boston Celtics performance metrics from 2000 to 2025, identifying historical trends, standout seasons, and patterns in team statistics
- **Trend Analysis**: Boston Celtics team success trends organizationally and statistically
- **Predictive Analysis**: Predicting future team success through point differential and other combined team statistics

## Tools & Libraries
- Python
- pandas
- matplotlib / seaborn
