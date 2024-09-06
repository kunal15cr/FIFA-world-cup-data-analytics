# FIFA World Cup Data Analytics

Welcome to the FIFA World Cup Data Analytics project! This repository provides a comprehensive analysis of FIFA World Cup data, including team performances, historical match data, and rankings. The analysis leverages several datasets to uncover insights into team performance, ranking changes, and match statistics.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Setup and Installation](#setup-and-installation)
4. [Data Analysis](#data-analysis)
   - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Team Performance Insights](#team-performance-insights)
   - [Substitution Impact Analysis](#substitution-impact-analysis)
   - [Expected vs. Actual Performance](#expected-vs-actual-performance)
5. [Conclusions](#conclusions)
6. [Future Work](#future-work)
7. [Acknowledgements](#acknowledgements)

## Project Overview

This project analyzes FIFA World Cup data to provide insights into team performance, historical match statistics, and the impact of various factors on the outcomes of matches. The primary focus areas include:

- **Match Statistics:** Total goals, average goals per match, and attendance over time.
- **Team Performance:** Winners, runners-up, and third-place finishers.
- **Substitution Impact:** Evaluating whether substitutions affect match outcomes.
- **Performance Deviations:** Comparing expected goals to actual goals.

## Data Sources

The project uses the following datasets:

- **FIFA Ranking Data:** `fifa_ranking_2022-10-06 - fifa_ranking_2022-10-06.csv`
- **World Cup Data:** `world_cup - world_cup.csv`
- **World Cup Matches Data:** `matches_1930_2022 - matches_1930_2022.csv`

## Data Analysis

### Exploratory Data Analysis (EDA)

- **Data Loading and Overview:** Load datasets and check for missing values, duplicates, and data types.
- **Match Statistics:** Analyze total goals scored, average goals per match, and total attendance.
- **Team Performance Insights:** Visualize the number of titles won, runner-up positions, and third-place finishes.

### Team Performance Insights

- **Winners and Runners-Up:** Pie charts showing the number of times each country has won the World Cup, and bar charts for runner-up and third-place positions.
- **Yearly Participation:** Heatmaps illustrating which teams participated in each World Cup year.

### Substitution Impact Analysis

- **Substitution Effectiveness:** Determine whether substitutions lead to goals or improved performance.
- **Substitute Player Performance:** Analyze the impact of substitute players on match outcomes.

### Expected vs. Actual Performance

- **Goals Analysis:** Compare the expected goals (xG) to actual goals scored by teams in recent World Cups.
- **Performance Deviations:** Highlight teams that performed better or worse than expected.

## Conclusions

- **Title Winners:** Brazil has won the most titles, followed by Italy and Argentina.
- **Runner-Up Insights:** Argentina, Netherlands, and West Germany have the most runner-up positions.
- **Performance Analysis:** Teams like Russia and Netherlands exceeded expectations in recent tournaments, while Brazil underperformed.

## Future Work

- **Expanded Analysis:** Incorporate more recent data and additional metrics like player statistics and tactical analysis.
- **Interactive Dashboards:** Develop interactive dashboards for a more dynamic exploration of the data.

## Acknowledgements

Special thanks to the creators of the datasets and the open-source community for their contributions. This project uses data from publicly available sources and visualizations powered by Plotly and Seaborn.
