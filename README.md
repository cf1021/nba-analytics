# NBA 2023-24 Player Performance Analysis 

## Overview 
Exploratory data analysis of NBA player statistics from the 2023-24 season using Python and Pandas. This project examines scoring trends, positional averages, and the relationship between age and performance. 

## Tools USed 
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset 
NBA Players Stats 2023-23 - 213 players, 29 statistical categories including points, rebounds, assists, shooting percentages, and efficiency metrics. 

## Analysis 
### 1. Top 10 Scorers 
Identified the highest scoring players in the league. Joel Embiid led the dataset at 33.0 PPG, followed by Jalen Brunson (32.4) and Damian Lillard (31.3) 

### 2. Age vs Scoring 
Scatter plot analysis of age against PPG revealed most players cluster between ages 20-27 scoring 0-10 PPG. Older outliers at 38-40 years represent rare elite performers, notably Lebron James, demonstrating survivorship bias in aging NBA players. 

### 3. Age vs Scoring Trend Line 
Added a linear trend line revealing a slight upward slope, however this is misleading due to survivorship bia. Only elite older players remain in the league, inflating the average for higher age groups. 

### 4. Scoring by Position 
Centers averaged the highest PPG despite the modern NBA being guard centeric. This reflects survivorship bias, elite centers like Embiid and Jokic inflate the positional average while the larger pool of role playing guards brings down their average.

## Key Insight 
Raw averages can be misleading without context. Understanding why data looks a certain way, not just what it shows, is what drives meaningful analysis. 

## Author 
Christopher Frank - MSc IT & Data Analytics, University of the West of Scotland 
github.com/cf1021
