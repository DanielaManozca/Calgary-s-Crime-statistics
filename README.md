###Calgary Crime Statistics
This repository contains an in-depth analysis of crime and social disorder trends in Calgary, using publicly available crime data. The goal is to explore crime rates, trends, and patterns over the last few years and understand their correlation with social disorder events in the city. The project includes visualizations for various crime categories, including violent crime, property crime, robbery, theft, and total crime incidents.

##Project Overview
This project uses crime data from Calgary alongside data on social disorder events to explore trends and relationships between crime and social disturbances across different communities. The analysis includes:

##Data Preprocessing: Merging crime and disorder datasets.
Aggregating Data: Grouping data by year and month to sum the crime and disorder counts.
Visualization: Creating line plots and scatter plots for various crime categories to observe trends and patterns over time.
Analysis: Drawing conclusions about the prevalence of different crime types and their potential correlations with social unrest.

##Datasets
The primary datasets used in this project are:

#Crime Data: Contains information about various types of crimes, including violent crimes, property crimes, theft, and robbery in Calgary.
#Disorder Data: Contains information on social disturbances such as public disturbances, disorderly conduct, and similar events across Calgary communities.
#Both datasets were merged and analyzed based on the community, year, and month.

##Data Sources
Crime Data: Available from Calgary’s public crime reporting datasets.
Disorder Data: Sourced from publicly available disorder event data.
Steps and Methodology
1. Data Preprocessing
The raw crime and disorder datasets were first cleaned and formatted for analysis. This involved:

##Merging Datasets: The crime and disorder datasets were merged based on the Date - Community column.
Column Renaming: The columns were renamed for easier reference (e.g., "Year_crime" was changed to "Year").
Handling Missing Data: Missing values were identified and treated.
2. Aggregation and Grouping
The data was grouped by year and month to aggregate the Crime Count and Disorder Count. This allowed for a comparison of total crime and disorder events on a monthly basis.

3. Data Visualization
The data was visualized using Matplotlib and Seaborn. Different crime categories (violent crime, property crime, robbery, theft, and total crime) were plotted against time to examine their trends and relationships with disorder events. The following types of plots were used:

Line Plots: To track crime counts and disorder event counts over time.
Dual-Axis Line Plots: To compare crime events with disorder events on the same graph using two y-axes for clear comparison.
Scatter Plots: For comparing relationships between crime and disorder events across different communities.
4. Analysis and Insights
The visualizations provided insight into crime trends over the years, helping answer questions like:

##What is the most common crime in Calgary?
##Which community is most affected by crime?
##How have crime rates evolved over the last five years?
##Are any crime categories rapidly increasing?

##Installation
To run the code and replicate the analysis, follow these steps:

Requirements
Python 3.x
Pandas
Matplotlib
Seaborn
Numpy

##Conclusion
Through this project, we have gained insights into how crime events and social disorder correlate over time in Calgary. The visualizations allow us to track crime trends and investigate how these trends evolve, potentially aiding policymakers, law enforcement, and community leaders in making data-driven decisions.
