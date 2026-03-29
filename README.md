# Titanic Exploratory Data Analysis (EDA)

This project performs a comprehensive Exploratory Data Analysis (EDA) on the Titanic dataset to identify the patterns and factors that influenced passenger survival during the tragedy.

## Project Overview
The analysis explores passenger details including gender, age, ticket class, fare, and family relationships. By using univariate, bivariate, and multivariate analysis, this project highlights how social status, gender, and age played critical roles in survival outcomes.

## Key Findings
* Overall Survival: Only 38.4% of the 891 passengers in the dataset survived, while 61.6% died.
* Gender Priority: Females had significantly higher survival rates across all classes, reflecting the "women and children first" social standard.
* Social Status: Passengers in 1st and 2nd class were far more likely to survive than those in 3rd class.
* Age Groups: Children were the only age group where survivors outnumbered deaths.
* Family Influence: Passengers in small families (2–4 members) had the highest survival rates, while large families (5+) had the lowest.

## Profile of a Survivor vs. Non-Survivor
* Survivor Profile: Typically a female traveling in 1st or 2nd class, often part of a small family.
* Non-Survivor Profile: Typically an adult male in 3rd class, often traveling alone or as part of a large family.

## Technical Summary
The analysis was performed using Python in a Jupyter Notebook with the following libraries:
* Pandas: For data manipulation.
* Matplotlib & Seaborn: For visualizations like pie charts, count plots, and survival heatmaps.

## Dataset
The dataset is sourced from the [Data Science Dojo repository](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
