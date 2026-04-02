AI Tools Data Analysis
Project Overview

This project focuses on the analysis of a dataset containing information about popular Artificial Intelligence tools. The objective is to perform data cleaning, statistical analysis, and visualization in order to better understand trends and patterns within the AI tools ecosystem.

The analysis was performed using Python in Google Colab, and the results were visualized through an interactive dashboard created in Looker Studio.

Dataset

The dataset used in this project was obtained from Kaggle:

Dataset source: https://www.kaggle.com/datasets/nudratabbas/top-100-ai-tools-2026

The dataset contains information about different AI tools and their characteristics. Before performing the analysis, the dataset was cleaned to ensure consistency and improve data quality.

Two versions of the dataset are included in this repository:

ai_tools_original.csv → Original dataset downloaded from Kaggle
ai_tools_limpio.csv → Cleaned dataset used for analysis and visualization
Data Cleaning Process

Before performing the analysis, the dataset was reviewed and cleaned. The cleaning process included:

Verifying the number of rows and columns
Reviewing data types for each variable
Removing or correcting inconsistent values
Preparing the dataset for statistical analysis and visualization

This process ensured that the dataset was structured and ready for analysis.

Data Analysis

The exploratory analysis included several statistical and analytical steps:

Calculation of descriptive statistics for numerical variables
Analysis of mean, median, and standard deviation
Grouping data by categorical variables using groupby()
Comparison of averages between categories
Correlation analysis between numerical variables

These steps helped identify patterns and relationships within the dataset.

Data Visualization

To better understand the data, different visualizations were created during the analysis, including:

Histograms of numerical variables
Bar charts comparing categories
Correlation analysis between numerical variables

These visualizations helped highlight trends and distributions in the dataset.

Dashboard

An interactive dashboard was created using Looker Studio to present the results of the analysis in a visual and easy-to-understand format.

Dashboard link:
https://lookerstudio.google.com/reporting/9289f238-62e4-41ee-8054-347ca1cc5fff

The dashboard provides a visual summary of the dataset and allows users to explore the information more easily.

Tools and Technologies

The following tools and technologies were used in this project:

Python
Pandas
Matplotlib
Google Colab
Looker Studio
Project Structure

The repository is organized as follows:

data

ai_tools_original.csv
ai_tools_limpio.csv

analysis

data_analysis.ipynb

README.md

Conclusion

This project demonstrates a basic data analysis workflow, including dataset cleaning, statistical exploration, and visualization. The goal was to transform raw data into meaningful insights and present them through an interactive dashboard.


## Dashboard Preview

<p align="center">
  <img src="image/dashboard.png" width="800">
</p>
