# Assessment1

## Overview ##
This project aims to analyse the differences in energy access globally, particularly focused on the number of people with or without access to electricity and clean cooking fuels. The analysis uncover the inequalities of distribution in energy infrastructures and informs policymakers with important evidence, thereby boosting eocnoomic growth and living standards.

## Techniques to Use ##
We use packages in R in order to analyse the dataset, like ggplot2 (for visualisation), tidyverse, dplyr, glue, skimr etc.

## Dataset Description ##
The dataset includes 6 variables are follwoing:
- Entity: regions, countries and income groups
- Year: observation year
- Number of people with access to electricity
- Number of people without access to electricity
- Number of people cooking with clean fuels
- Number of people cooking without clean fuels

## Data Wrangling ##
The purpose of data wrangling is to get more clear and reliable data. Main steps of data wragling are following:
- Column slection and rename:
  Select relevant columns for the task and rename them with more accesible titles.
- Remove missing values:
  Use filter to exclude the regions, income groups and organisations. Remove all missing values (N/A) to improve the     reliability and completeness.
- Calculate averages:
  Group by country to calculate the mean number of people with or without access to electricity and clean fuels in order to      better understand situations in each country.
- Create a new variable:
  Create a new variable called 'high_access' to check whether the number of people with energy access exceeds those without,   thereby providing evidence to evaluate the equilibrium of energy distribution.

## Data Visualisation ##
  - Visualisation 1: the global trend of electricity access over time
    Gives a long-term trend.
  - Visualisation 2: the distribution of 10 countries with the lowest access to clean cooking fuels
    Highlights the inequalities of energy access distribution.
  - Visualisation 3: the relationship between income groups and electricity access
    Illustrates energy inequality across income levels.

## Collaboration with ChatGPT ##
In this project, we embraced the collaboration with ChatGPT, especially in the areas of code optimization and data processing. ChatGPT provides important advice on how to filter and aggregate data and helps solve the problem of data consistency. However, ChatGPT sometimes falls short in understanding context and requires further processing of the data for accurate interpretation
  






  
