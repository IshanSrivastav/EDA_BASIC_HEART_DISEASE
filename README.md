# Heart Disease EDA (Exploratory Data Analysis)

This project performs an **Exploratory Data Analysis (EDA)** on a heart disease dataset using data visualization techniques. The goal is to gain insights and understand the relationships between different features that might help in predicting heart disease.

You can download the dataset here: [heart.csv](./heart.csv)

## Prerequisites

Before running this project, you need to have the following Python libraries installed:

- **Pandas**: Used for data manipulation and analysis.
- **Seaborn**: A data visualization library that makes it easy to create attractive and informative statistical graphics.
- **Matplotlib**: A plotting library for creating static, animated, and interactive visualizations.

You can install these libraries using `pip`:

```bash
pip install pandas seaborn matplotlib
```


This project performs **Exploratory Data Analysis (EDA)** on a heart disease dataset using data visualization techniques. The goal is to gain insights and understand the relationships between different features that might help in predicting heart disease.

## Overview

Data visualization is essential for understanding a dataset. It helps us discover patterns, trends, and relationships in the data. In this project, we use different types of visualizations to explore the heart disease dataset and gain valuable insights.

Some of the common visualizations used in this project include:

- **Histograms**: To understand the distribution of numerical variables.
- **Pie Charts**: To visualize the proportion of categories in categorical data.
- **Box Plots and Violin Plots**: To show the distribution and spread of data.
- **Heatmaps**: To understand correlations between different variables.
- **Pair Plots and Joint Plots**: To visualize relationships between multiple variables.

## Project Breakdown

The project is divided into six parts, each exploring a different aspect of the heart disease dataset:

1. **Heart Disease EDA - Age (DistPlot)**  
   Explore the distribution of ages in the dataset using a `distplot`. This helps us understand the age range of people who are affected by heart disease.

2. **Heart Disease EDA - Categorical Columns (Pie Charts)**  
   Use pie charts to show the distribution of categorical variables, such as gender, and how they relate to heart disease prevalence.

3. **Heart Disease EDA - ViolinPlot**  
   Use a `violinplot` to visualize the distribution of heart disease cases, comparing different categories such as gender. This is a combination of a boxplot and kernel density plot.

4. **Heart Disease EDA - Correlation (HeatMap)**  
   Create a correlation heatmap to visualize the relationships between various numerical variables in the dataset. This shows which variables are strongly correlated with each other.

5. **Heart Disease EDA - Correlation (PairPlot)**  
   Use a `pairplot` to show pairwise relationships between features in the dataset. This helps us identify any potential correlations.

6. **Heart Disease EDA - Correlation - (JointPlot)**  
   Use a `jointplot` to visualize the relationship between two variables, with their individual distributions on the axes. This helps us understand how different factors, like cholesterol levels, affect the heart rate.

## Key Visualizations Explained

### 1. **Heart Disease EDA - Age (DistPlot)**
In this section, we use a `distplot` to show the distribution of ages. The plot reveals that the minimum age is around 30 and the maximum is around 80, with most people falling between the ages of 40 and 70.

### 2. **Heart Disease EDA - Categorical Columns (Pie Charts)**
A pie chart is used to show the proportion of males and females with heart disease in our dataset. From the chart, we see that 79% of the people with heart disease are male, and 21% are female.

### 3. **Heart Disease EDA - ViolinPlot**
The `violinplot` combines a box plot and a kernel density estimate (KDE) plot. It gives us a better understanding of the distribution of heart disease cases for each gender. From this plot, we can see that more males are affected by heart disease compared to females.

### 4. **Heart Disease EDA - Correlation (HeatMap)**
A **correlation heatmap** shows the relationships between the different variables in the dataset. For example, it helps us identify which features are positively or negatively correlated with the presence of heart disease. The heatmap uses color to show these correlations, with darker colors indicating stronger relationships.

### 5. **Heart Disease EDA - Correlation (PairPlot)**
The **pairplot** visualizes the pairwise relationships between variables. Each scatter plot shows the relationship between two variables, and the diagonal shows the distribution of individual variables. It helps us identify potential correlations and trends in the data.

### 6. **Heart Disease EDA - Correlation - (JointPlot)**
The **jointplot** shows the relationship between two variables, such as cholesterol and max heart rate (MaxHR), with histograms on the axes showing the distribution of each variable. This plot helps us understand how one feature affects another.

## Conclusion

Using various data visualization techniques, we are able to:

- Visualize the age distribution of individuals with heart disease.
- Understand the gender distribution and its impact on heart disease.
- Identify relationships between different variables using correlation heatmaps, pair plots, and joint plots.

These insights can be valuable for healthcare professionals and researchers looking to understand the patterns in heart disease data and improve diagnosis or treatment plans.

# Contributing

**Contributions are welcome! If you have ideas for enhancements or spot any issues, feel free to submit a pull request.**
