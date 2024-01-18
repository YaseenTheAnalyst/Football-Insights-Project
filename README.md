# Football Insights Project: Exploration and Analysis

## Introduction

### Dataset Overview

This project delves into a comprehensive soccer database containing extensive data on matches, players, and teams from various European countries spanning the period 2008 to 2016. The dataset comprises seven tables (Country, League, Match, Player, Player Attribute, Team, and Team Attribute). The data was initially explored and then exported into CSV files using DB Browser for subsequent analysis.

### Key Questions for Exploration

1. **Team Performance: Home Wins**
   - Identifying the team with the highest number of home wins.

2. **Team Performance: Away Wins**
   - Determining the team with the highest number of away wins.

3. **Performance Metrics Relationship**
   - Exploring the relationship between key performance metrics (Speed Buildup, Defence Pressure, Chance Creation) and winning percentages.

## Data Wrangling

### Importing Data

- Utilized Pandas library to read CSV files.

### Data Cleaning

- Eliminated unnecessary columns to focus on relevant information.
- Removed missing values and handled duplicates.

## Exploratory Data Analysis

### Research Question 1: Team Performance - Home Wins

- Created a 'result' column to categorize match outcomes.
- Visualized the distribution of home wins.

### Research Question 2: Team Performance - Away Wins

- Examined the team with the highest number of away wins.
  
### Research Question 3: Performance Metrics Relationship

- Analyzed the relationship between metrics (Buildup Speed, Defence Pressure, Chance Creation) and winning percentages.
- Generated scatter plots for visual representation.

### Correlation Analysis

- Utilized correlation coefficients to quantify relationships between variables.

## Conclusions

- FC Barcelona emerged as a dominant team with the most away and home wins between 2008 and 2016.
- Notable findings include a lack of significant correlation between buildup speed or chance creation and winning percentages, while a slight correlation exists between defense pressure and winning percentage.
- Marco Rues is the player with the greatest increase in rating between 2008 and 2016.

