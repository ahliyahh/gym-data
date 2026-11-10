# Exercise Ratings by Equipment Type

## Overview

An exploratory analysis of an exercise dataset, focused on how user ratings are distributed across equipment categories. The project practices data inspection, cleaning, descriptive analysis, and visualization.

## Research question

How do exercise ratings vary across equipment types, including bodyweight exercises and exercises that require equipment?

## Data

The notebook uses the `megaGymDataset` dataset downloaded through KaggleHub. The fields include exercise title and description, exercise type, targeted body part, equipment, difficulty level, rating, and rating description.

## Methods

1. Load the dataset with pandas and inspect its structure and summary statistics.
2. Standardize column names and remove an extraneous index column.
3. Examine missing values and duplicate records.
4. Use a boxplot to compare the distribution of exercise ratings across equipment categories.

## Tools

- Python
- pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- KaggleHub

## Preliminary observation

The notebook's boxplot is intended to compare the spread and central tendency of ratings across equipment categories, including bodyweight exercises. The visualization is exploratory and should not be treated as evidence that one exercise category is objectively better than another.

## Limitations and next steps

The current notebook uses forward filling to handle missing values. This can carry a previous row's value into a later record and may affect rating distributions. A stronger revision would assess missingness by column, avoid imputing ratings without a defensible reason, and compare groups using only valid rating observations. The dataset also reflects user-submitted ratings rather than a controlled assessment of exercise effectiveness.

