---

# CardioGoodFitness Data Analysis Project

## Overview
This project analyzes customer data from CardioGoodFitness to understand customer preferences, demographics, and usage patterns for different treadmill models. The analysis aims to provide insights for marketing strategies and product improvements.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## How to Run
1. Ensure all required libraries are installed
2. Load the dataset 'CardioGoodFitness.csv'
3. Run the Jupyter Notebook or Python script containing the analysis

## Dataset
The dataset (`CardioGoodFitness.csv`) contains information about customers, including:
- Product (Treadmill model)
- Demographics (Age, Gender, Education, Marital Status)
- Usage patterns
- Fitness levels
- Income
- Expected miles to run

## Analysis Performed

### Data Exploration
- Basic statistics of the dataset
- Checking for missing values

### Univariate Analysis
- Distribution of treadmill models
- Age distribution of customers
- Gender distribution
- Education levels
- Marital status
- Usage frequency
- Fitness levels
- Income distribution
- Expected miles to run

### Bivariate Analysis
- Product preference by gender
- Usage patterns by product and gender
- Usage patterns by product and marital status
- Fitness levels across age groups
- Relationship between fitness and income
- Fitness levels and expected miles by gender
- Income and expected miles by marital status
- Treadmill usage and income by gender

## Key Insights

1. Customer Demographics:
   - Age range: 18-50 years, mean age of 28 years
   - More male customers (104) than female customers (76)
   - Most customers are graduates or undergraduates

2. Product Preferences:
   - TM195 is the most popular model, followed by TM498 and TM798
   - Slight gender differences in model preferences

3. Usage Patterns:
   - Most customers want to use the treadmill 3-4 times a week
   - Higher income correlates with more frequent treadmill usage

4. Fitness and Miles:
   - Higher self-rated fitness correlates with more expected miles
   - Highly fit women expect to run more miles than highly fit men

5. Income Insights:
   - Average income: $53,719
   - Higher income correlates with higher self-rated fitness
   - High-income couples expect to run more miles than singles

## Recommendations

1. Target marketing for TM798 to attract more customers, especially females
2. Develop fitness programs for high-income males who want to use treadmills daily
3. Investigate why highly unfit females are less likely to use treadmills
4. Consider creating specialized programs for couples, particularly high-income couples
5. Develop strategies to engage younger customers (25-30 years) who rate themselves as unfit

## Future Work
- Collect more detailed data on customer preferences and fitness goals
- Perform advanced statistical analyses to validate findings
- Develop predictive models for customer behavior and product preferences
