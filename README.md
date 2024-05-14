# Yulu Electric Cycle Demand Analysis

## Business Problem
Yulu, India's leading micro-mobility service provider, has experienced a dip in revenues. The company aims to understand the factors affecting the demand for shared electric cycles to improve their service and adapt their business strategy accordingly.

## Dataset
The dataset contains records of cycle rentals including date, weather conditions, temperature, humidity, wind speed, and the count of rented cycles (both casual and registered users). The key challenge is to analyze these factors to predict and understand the demand dynamics in the Indian market.

## Approach
### Data Analysis:
- **Data Import and Cleaning**: Load the dataset and perform initial data cleaning, removing any irrelevant or duplicate data.
- **Exploratory Data Analysis (EDA)**: Analyze the dataset to understand the distribution and relationship of various variables like weather, working day, and season on the cycle rental counts.

### Hypothesis Testing:
- **Working Day Effect**: Perform a two-sample t-test to determine if there is a significant difference in rentals on working days versus non-working days.
- **Seasonal and Weather Effects**: Use ANOVA to test if the number of cycles rented varies significantly across different seasons and weather conditions.
- **Dependency Check**: Conduct a Chi-square test to see if the weather condition is dependent on the season.

## Insights and Recommendations
Based on the statistical tests and EDA, provide insights into which factors most significantly affect cycle demand and offer actionable recommendations for Yulu to optimize their deployment strategy.

## How to Run
- Ensure Python 3 and Jupyter Notebook are installed on your system.
- Clone the repository and navigate to the project directory.
- Install required dependencies: `pip install -r requirements.txt`.
- Open the Jupyter Notebook: `jupyter notebook Yulu_Analysis.ipynb`.
- Run all the cells in the notebook to reproduce the analysis and results.

## Conclusion
This analysis provides Yulu with a clear understanding of the demand patterns for their electric cycles, helping them make informed decisions to enhance their services and maximize user satisfaction and revenue.
