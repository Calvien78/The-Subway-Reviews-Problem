# Subway Reviews Analysis

## Description
This project analyzes customer reviews of Subway stores from the Yelp Open Dataset to address operational and customer satisfaction issues. The analysis helps determine trends in ratings and supports strategic decision-making by Subway's executive team.

## Problem Context
Subway's CEO is concerned about low average ratings across U.S. stores and aims to achieve an average rating of **4.5/5**. Key questions include:
1. Are customer ratings improving over time?
2. Are Subway's ratings low compared to competitors?
3. How do national chains compare to local restaurants?
4. Are extreme ratings (1 and 5 stars) disproportionately represented?

## Objectives
- Evaluate the validity of executive team statements using data.
- Provide actionable insights and recommendations for improving Subway's ratings.

## Features
- **Trend Analysis**: Analyze trends in Subway ratings over time.
- **Competitor Comparison**: Compare Subway’s ratings with those of competitors.
- **Chain vs. Local Analysis**: Assess differences in ratings between national chains and local restaurants.
- **Polarization Analysis**: Explore the distribution of ratings to identify biases.

## Getting Started

### Prerequisites
- Python 3.x
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`  
  Install them via pip:
  ```bash
  pip install pandas numpy matplotlib seaborn jupyter

## Dataset
The project uses subsets of Yelp Open Dataset:
- **Review Dataset: Contains user ratings and review dates.**
- **Restaurant Dataset: Includes restaurant names, categories, and locations.**
