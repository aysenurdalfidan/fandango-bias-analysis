# Fandango Bias Analysis

This project investigates potential rating bias in Fandango's displayed movie ratings by comparing them with actual user ratings and reviews from other platforms (Rotten Tomatoes, Metacritic, and IMDb).

## Overview

Have you ever wondered whether online movie ratings are trustworthy? Especially when the platform showing the ratings also profits from ticket sales. This analysis dives into Fandango's 2015 movie ratings to uncover discrepancies and biases.

## Key Features

- **Data Analysis**: Utilised Python and pandas for data processing and analysis.
- **Visualisation**: Created insightful plots with matplotlib and seaborn to highlight differences.
- **Comparison**: Normalised ratings from multiple platforms for a fair comparison.

## Tools and Libraries

- Python
- pandas
- numpy
- matplotlib
- seaborn

## Data Sources

The data for this project comes from [FiveThirtyEight's GitHub repository](https://github.com/fivethirtyeight/data) and includes:
- `fandango_scrape.csv`
- `all_sites_scores.csv`

## Visualisations

![Scatterplot of Ratings vs Votes](images/rating_vs_votes.png)
*Shows the relationship between Fandango movie ratings and their vote counts.*

![Distribution of Rating Differences](images/rating_difference_distribution.png)
*Comparison of Fandango's displayed stars versus actual ratings.*
