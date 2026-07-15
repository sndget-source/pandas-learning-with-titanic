# Pandas Learning with Titanic Dataset

This repo is my hands-on practice log for learning pandas. I followed Corey Schafer's pandas series on YouTube, and instead of just watching, I rebuilt every concept myself in Jupyter Notebook, lesson by lesson, using the Titanic dataset.

## Why this repo exists

I wanted proof, mainly for myself, that I actually understood what I was watching, not just following along. Each notebook is one lesson, done independently, committed as I finished it.

## Lessons

1. Introduction to pandas with the Titanic dataset
2. DataFrames and Series
3. Working with the index
4. Filtering data
5. Modifying data within DataFrames
6. Adding and removing rows and columns
7. Sorting, largest and smallest values
8. Grouping and aggregations
9. Cleaning data - missing values and categorical data
10. Pivot tables
11. Correlation coefficient and heatmaps
12. Dropping duplicates
13. Binning with cut and qcut
14. Reading and writing data in different file formats
15. Working with dates and time series

For lesson 15, Titanic didn't have a date column, so I used a separate dataset (Smart Mobility Traffic Dataset, CC0 licensed) that had timestamps, just to practice datetime handling properly instead of skipping it.

## Data used

- train.csv, test.csv, gender_submission.csv - Titanic dataset (Kaggle)
- Smart Mobility Traffic Dataset (Kaggle, CC0) - used only for the dates and time series lesson

## Tools

Python, pandas, seaborn, matplotlib, Jupyter Notebook

## What I took away from this

Some things that stuck with me while doing this, not just from the syntax but from actually looking at the data:

- Class and fare mattered more to survival than I expected going in
- Age binning made it obvious that children survived at noticeably higher rates
- Binning with qcut vs cut finally made sense once I saw fare split unevenly between the two

## What's next

Applying this to a dataset I haven't touched before, and starting to bring in visualization properly instead of just describe() and corr().
