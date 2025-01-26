# Titanic Survey EDA: Exploratory Data Analysis on Titanic Dataset
This repository contains a comprehensive Exploratory Data Analysis (EDA) project focused on the Titanic dataset, one of the most popular datasets for data science projects. The dataset records information about passengers aboard the RMS Titanic, which sank on its maiden voyage in 1912. The main objective of this analysis is to investigate patterns, identify significant features, and draw conclusions about the factors that may have influenced survival chances on the Titanic.

The Titanic dataset consists of both numerical and categorical data about passengers, such as age, sex, passenger class, embarkation port, and more. Through this project, the goal is to perform an in-depth analysis to uncover insights and trends that can explain how various passenger attributes relate to their likelihood of survival.

## Project Objectives

**Data Cleaning and Preprocessing:** Handle missing data, outliers, and ensure the dataset is in a usable format for analysis.
Exploratory Data Analysis (EDA): Use various statistical and graphical techniques to explore the relationships between different features and survival outcomes.
**Data Visualization:** Employ advanced visualization libraries to better understand trends, distributions, and correlations in the data.
Insight Generation: Draw actionable insights from the analysis that highlight significant predictors of survival.
**Feature Engineering:** Explore how to transform and create new features that could improve prediction models (for example, categorizing age groups or grouping similar passenger classes).

# Datasets
The primary dataset used in this project is the Titanic Passenger dataset, which contains the following columns:

PassengerId: Unique identifier for each passenger.
Pclass: Passenger class (1 = First class, 2 = Second class, 3 = Third class).
Name: Name of the passenger.
Sex: Gender of the passenger (male or female).
Age: Age of the passenger (some entries may be missing).
SibSp: Number of siblings or spouses aboard.
Parch: Number of parents or children aboard.
Ticket: Ticket number.
Fare: Fare paid by the passenger.
Cabin: Cabin number (many values are missing).
Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
Approach
1. Data Preprocessing
Handle missing values: The dataset contains missing values in columns like Age, Cabin, and Embarked. Various techniques like filling with mean/median values or removing rows/columns are explored.
Encoding categorical features: Variables such as Sex, Embarked, and Pclass are categorical and need to be encoded appropriately for statistical analysis and visualizations.
Feature scaling: Normalization and scaling techniques are applied where required, particularly for continuous variables like Age and Fare.
2. Exploratory Data Analysis (EDA)
Univariate Analysis: Understanding the distribution of individual features using histograms, boxplots, and bar charts.
Bivariate Analysis: Exploring the relationships between pairs of features and how they correlate with survival rates using scatter plots, heatmaps, and pair plots.
Survival Analysis: The main focus of the analysis is the Survived column, which indicates whether the passenger survived (1) or not (0). Various techniques, such as group comparisons, statistical tests, and visualizations, are used to examine how features like Age, Sex, Pclass, and Embarked influence survival rates.
3. Data Visualization
Matplotlib & Seaborn: Used to create insightful visualizations, such as:
Distribution plots of continuous features like Age and Fare.
Count plots to examine categorical features like Sex and Pclass.
Pairwise relationships between key features using seaborn’s pairplot.
Correlation heatmap to analyze how different features are correlated with each other.
Plotly (Optional): Interactive visualizations to allow more dynamic exploration of the dataset.
4. Statistical Analysis
Statistical tests such as Chi-square tests, t-tests, and correlation coefficients are applied to evaluate the significance of relationships and determine which features have the most impact on survival.
Hypothesis testing to validate assumptions about the data, such as whether Sex has a significant effect on survival chances.
5. Conclusion and Insights
After thorough analysis, several key insights are drawn, such as:
Women were more likely to survive than men, with a notably higher survival rate in first-class passengers.
Passengers in higher-class cabins (Pclass = 1) had a higher chance of survival.
Age and family size (SibSp + Parch) played a significant role in survival rates.
The dataset provides a fascinating opportunity to explore the impact of social class, gender, and family relationships on survival during a disaster.
Technologies Used
Python: The primary programming language for data analysis.
pandas: Data manipulation and analysis.
numpy: Numerical computing and handling of missing values.
matplotlib: Static plotting library for visualizations.
seaborn: Advanced statistical data visualization.
plotly: Interactive visualizations (optional).
scipy: Statistical analysis and tests
