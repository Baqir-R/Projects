# Movie Analysis

This project performs exploratory data analysis (EDA) on a movie dataset.  
Using Python libraries like pandas, numpy, matplotlib, and seaborn, it aims to uncover key patterns, trends, and relationships within the data.

## File

- Notebook: Movie.ipynb
- Data: The notebook reads a CSV file (movies.csv) from your local directory.  
  The CSV contains information about movies, including attributes such as movie titles, genres, release years, scores, gross earnings, and more.

## Main Goals

The main goals of this notebook are to:

- Perform Exploratory Data Analysis (EDA) on the movie dataset.
- Handle missing values and check for outliers.
- Provide descriptive statistics to better understand the distribution of the data.
- Visualize relationships and patterns (using box plots, scatter plots, and other charts).

## Contents

- Import Packages: Import libraries required for data analysis.
- Load Data: Loading the CSV file into a pandas DataFrame.
- General Inspection: View first few rows, data types, and missing values.
- Missing Values: Loop through columns to check for missing data.
- Outliers: Box plot to visualize potential outliers in gross.
- Additional Analysis (to be added by you):
  - Distribution of scores and revenue
  - Top movies by earnings
  - Mean score by genre or year

## Installation

To view or execute this notebook:

1. Make sure you have Python 3+ installed.
2. Install required libraries (if you don't already have them) by running: 

```bash
pip install numpy pandas matplotlib seaborn notebook

