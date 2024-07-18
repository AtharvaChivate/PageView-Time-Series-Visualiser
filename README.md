# Page View Time Series Visualizer

This project visualizes the time series data of page views on the freeCodeCamp platform. The dataset contains daily page views over a specified period, and the project includes data cleaning, filtering, and plotting to provide insights into the trends and patterns in the data.

## Dataset Description

The dataset used in this project contains the following columns:
- `date`: The date of the page view.
- `value`: The number of page views on the freeCodeCamp platform on that date.

## Project Summary

In this project, the following tasks were performed:

1. **Data Cleaning**: 
   - Imported the dataset and set the `date` column as the index.
   - Filtered the dataset to remove the top 2.5% and bottom 2.5% of page views to remove outliers.

2. **Line Plot**:
   - Created a line plot to visualize the daily page views from May 2016 to December 2019.

3. **Bar Plot**:
   - Added `month` and `year` columns to the dataset.
   - Grouped the data by `year` and `month` and calculated the average page views for each month.
   - Created a bar plot to show the average monthly page views for each year.

4. **Box Plot**:
   - Prepared the data for box plots by adding `year` and `month` columns.
   - Created two box plots using Seaborn:
     - A year-wise box plot to show the trend of page views over the years.
     - A month-wise box plot to show the seasonality of page views within each year.

## Visualizations

### Line Plot
![Line Plot](https://github.com/AtharvaChivate/PageView-Time-Series-Visualiser/blob/main/line_plot.png)

### Bar Plot
![Bar Plot](https://github.com/AtharvaChivate/PageView-Time-Series-Visualiser/blob/main/bar_plot.png)

### Box Plot
![Box Plot](https://github.com/AtharvaChivate/PageView-Time-Series-Visualiser/blob/main/box_plot.png)
