# PRODIGY-DS-01

# Adult Census Income Data Analysis

## Overview

This project is part of the internship program at Prodigy Infotech, focused on data science. It analyzes the Adult Census Income dataset obtained from Kaggle. The dataset contains information about individuals' demographic and socioeconomic characteristics, with the target variable being income.

## Table of Contents

- [Data Loading](#data-loading)
- [Data Exploration](#data-exploration)
  - [Exploring Age](#exploring-age)
  - [Exploring Gender](#exploring-gender)
  - [Exploring Combination of Both](#exploring-combination-of-both)

## Data Loading

The project starts with loading necessary libraries and importing the dataset using pandas. 

```python
import pandas as pd

# Loading the dataset
data = pd.read_csv('/kaggle/input/adult-census-income/adult.csv')
````
## Data Exploration

### Exploring Age
The age feature is explored first. A histogram, kernel density estimate plot, and box plot are used to visualize the distribution of age.

### Exploring Gender
Next, the gender feature is explored. The count of males and females in the dataset is examined using value counts and bar plots.

### Exploring Combination of Both
Finally, the combination of age and gender is explored. Separate histograms for males and females are compared, and a combined histogram is created to visualize the distribution of age across genders

