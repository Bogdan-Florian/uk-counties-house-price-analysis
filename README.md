# House Prices Analysis and Recommendation System

This repository contains a university data science project aimed at analyzing house prices based on multiple quantitative factors and subsequently creating a recommendation system. The dataset includes variables such as house prices, crime rates, broadband speeds, build types, and others.

## Project Structure

The project is structured into several parts, as described below:

1. **Data Loading:** Data is loaded from a SQLite database with the help of SQL queries and pandas library.

2. **Data Processing:** This includes generating user-based scores, calculating final scores based on Z-score normalization, sorting and ranking, and fetching top locations.

3. **Data Analysis:** Detailed exploratory data analysis is performed. It includes visualizations, correlations and statistical summaries. Libraries used for this purpose include pandas, seaborn, matplotlib, and scipy.

4. **Outlier Detection:** Outliers in the house price data are identified using the Z-score method. Outliers are visualized in the crime rate vs prices plot.

5. **Data Visualization:** Various data visualizations are generated using seaborn and matplotlib libraries. These visualizations include a correlation heatmap, histograms, relational plots, and box plots.

6. **Model Building:** A multiple linear regression model is built with the help of sklearn library to predict house prices based on crime rates, broadband speeds and new build status.

## Usage

Each part of the project can be run independently, as long as the necessary data is available in the SQLite database. 

## Features

- **Data analysis with pandas and SQL queries:** Enables effective and efficient data manipulation and analysis.

- **Exploratory Data Analysis with visualization libraries (Seaborn, Matplotlib):** Provides insights into the data and its characteristics.

- **Outlier Detection:** Identifies anomalies in the dataset that could potentially skew the results.

- **Correlation Analysis:** Determines the relationships between different variables in the dataset.

- **Multiple Linear Regression model implementation using sklearn:** Provides a method to predict house prices based on other relevant factors.
