# Data Analysis with Python Certification Projects

This repository contains the projects I completed to earn the FreeCodeCamp Data Analysis with Python certification. Each project is organized into its own folder and contains the source code used for analysis and visualization. Below is a summary of each project, the tools used, and my personal experiences working on them.

## Projects

### 1. Mean-Variance-Standard Deviation Calculator
**Description:**  
This project involved creating a function called `calculate()` in a Python script named `mean_var_std.py`. The function processes a 3x3 matrix and computes various statistical measures, including mean, variance, standard deviation, maximum, minimum, and sum. These calculations are performed along the rows, columns, and for the entire matrix.

**Tools Used:**  
- Python
- Numpy

**Key Features:**  
- Converts a list of 9 digits into a 3x3 Numpy array.
- Calculates statistics for rows, columns, and the entire matrix.
- Returns results in a dictionary format.
- Raises a `ValueError` for input lists with fewer than 9 elements.

### 2. Demographic Data Analyzer
**Description:**  
This project involved analyzing demographic data from the 1994 Census using Pandas. The objective was to answer specific questions about the dataset, such as race distribution, average age of men, income analysis based on education, and work hours.

**Tools Used:**  
- Python
- Pandas

**Key Features:**  
- Counted the number of people of each race.
- Calculated the average age of men.
- Analyzed income in relation to education level and work hours.
- Determined the most popular occupation for high earners in India.

### 3. Medical Data Visualizer
**Description:**  
This project involved visualizing and analyzing medical examination data using Pandas, Matplotlib, and Seaborn. The dataset included patient metrics such as body measurements, blood test results, and lifestyle factors, which were explored in relation to cardiovascular disease.

**Tools Used:**  
- Python
- Pandas
- Matplotlib
- Seaborn

**Key Features:**  
- Added an "overweight" column based on BMI calculations.
- Normalized cholesterol and glucose data.
- Created a categorical plot to show health indicators and cardiovascular disease.
- Generated a heatmap to visualize correlations between key variables.

**Personal Insight:**  
Understanding the `pd.melt()` function was tricky but rewarding once I grasped it.

### 4. Page View Time Series Visualizer
**Description:**  
This project involved visualizing time series data from the freeCodeCamp.org forum to analyze page views from May 2016 to December 2019. The goal was to reveal patterns and trends using various visualizations.

**Tools Used:**  
- Python
- Pandas
- Matplotlib
- Seaborn

**Key Features:**  
- Created a line plot for daily page views.
- Generated a bar chart showing average daily views per month.
- Produced box plots to display yearly and monthly trends in page views.

### 5. Sea Level Predictor
**Description:**  
This project focused on analyzing global sea level changes from 1880 to predict future changes through 2050. The project included data visualization, trend analysis, and predictive modeling.

**Tools Used:**  
- Python
- Pandas
- Matplotlib
- Scipy

**Key Features:**  
- Created a scatter plot to display the relationship between year and sea level.
- Used `linregress` to calculate lines of best fit for both the entire dataset and recent data from 2000 onwards.
- Predicted future sea level rise through 2050.

**Personal Insight:**  
Drawing the line of best fit was challenging, but I gained a deeper understanding of trend analysis.

## Repository Structure
Each project is contained within its own folder, with source code available in both `.ipynb` (Jupyter Notebook) format for analysis and `.py` files for submission.

## Additional Information
While working on these projects, I primarily used Jupyter notebooks for ease of analysis and visualization. The final versions of the projects were then converted to `.py` files for submission. To better understand and explain advanced concepts like `catplot()`, I watched videos and read documentation, which greatly helped in successfully completing the projects.
