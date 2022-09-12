# Movies-ETL
## Overview
For this project we will create an automated pipline that takes in new data, performs the appropriate transformations, and loads the data into existing tables for Amazing Prime to analyze.

## Resources
wikipedia-movies.json, movies_metadata.csv, ratings.csv

## Results
# Write ETL function
The function takes the wikipedia-movies.json, the Kaggle metadata and csv files and creates separate Dataframes
# Extract and Transform Wiki data
We filtered out TV shows, consolidated redundant data, removed duplicates and formatted the Wikipedia data
# Extact and Transform Kaggle & Rating data
We consolidated redundant data, removed duplicates, formatted and grouped the data. Then we merged the kaggle and rating data with the Wikipedia movies dataframe.

## Summary
The ETL function we created for this project collects and cleans movie data from different sources. It also transforms, merges and loads that data into updateable PostgreSQL dataset tables to be used by Amazing prime in their analysis.
