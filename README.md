Exercise Dataset Analysis
Overview

This project analyzes a dataset of exercises to understand patterns in user ratings, exercise types, targeted body parts, and equipment usage. The goal was to clean the dataset, explore trends, and visualize key insights about exercise popularity and perceived quality.
Dataset

The dataset includes the following columns:
title – Exercise name
desc – Short description
type – Type of exercise (strength, cardio, stretching)
bodypart – Targeted muscle group
equipment – Equipment required (dumbbell, barbell, bodyweight, etc.)
level – Difficulty (beginner, intermediate, advanced)
rating – Numeric user rating
ratingdesc – Text-based rating


Data Cleaning
Removed extraneous columns (e.g., unnamed index columns)
Standardized column names
Checked for missing values and duplicates
Verified correct data types (numeric vs text)
Analysis & Visualization

The main analysis focused on exercise ratings by equipment type.

Equipment vs Rating

A boxplot was used to visualize how ratings vary across equipment types:

Key Insight:
Bodyweight exercises have median ratings comparable to exercises requiring equipment.
Equipment-based exercises show slightly more variability in ratings, but there is no clear advantage in median rating.
This suggests accessibility does not reduce perceived quality, and users rate exercises highly regardless of equipment.
Other optional analyses:
Average rating by difficulty level
Exercise count by body part
Equipment vs difficulty distribution

Key Takeaways
Cleaned and structured data for accurate analysis
Visualized rating distributions across categories
Derived actionable insights that could inform fitness program design or app recommendations
Skills Highlighted
Data Cleaning: Handling missing values, duplicates, and column formatting
Data Analysis: Grouping, aggregation, descriptive statistics
Data Visualization: Boxplots with Matplotlib and Seaborn
Interpretation: Translating numeric trends into actionable insights

