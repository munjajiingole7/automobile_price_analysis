# Automobile Price Analysis
---

## Project Overview

This project aims to analyze and clean an automobile dataset to identify and visualize key parameters affecting the price of vehicles. By understanding these factors, we can provide actionable insights for pricing strategies.

## Dataset Description

The dataset contains the following columns:
- `symboling`
- `normalized-losses`
- `make`
- `fuel-type`
- `aspiration`
- `num-of-doors`
- `body-style`
- `drive-wheels`
- `engine-location`
- `wheel-base`
- `length`
- `width`
- `height`
- `curb-weight`
- `engine-type`
- `num-of-cylinders`
- `engine-size`
- `fuel-system`
- `bore`
- `stroke`
- `compression-ratio`
- `horsepower`
- `peak-rpm`
- `city-mpg`
- `highway-mpg`
- `price`

For this analysis, we only removed the `symboling` column as it was irrelavant to our analysis. The target output column is `price`.

## Data Cleaning

The data cleaning process involved:
- Replacing null values with the mean of the respective columns.
- Changing the data types of some columns to ensure consistency and accuracy in analysis.

## Visualization Tools

We utilized the following visualization libraries:
- Matplotlib
- Seaborn
- Plotly

These tools helped us create informative and interactive visualizations to better understand the relationships between different parameters and the price of automobiles.

## Findings and Presentation

At the end of the project, we created a PowerPoint presentation discussing the factors affecting automobile prices. The presentation includes visualizations and insights derived from our analysis.

## How to Run the Project

1. Clone the repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Run the analysis script:
   ```bash
   python automobile_price_analysis.py
   ```
4. Review the generated visualizations and refer to the PowerPoint presentation for detailed insights.

## File Structure

- `automobile_price_analysis.py`: Contains the data cleaning and analysis code.
- `AUTOMOBILE ASSIGNMENT by Munjaji Ingole.pdf`: The PowerPoint presentation discussing the findings.

## Conclusion

This project provides a comprehensive analysis of the factors affecting automobile prices. By cleaning the data and utilizing advanced visualization techniques, we have identified key insights that can help in making informed pricing decisions.
