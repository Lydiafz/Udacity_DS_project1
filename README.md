
# Table of Contents
- [Heading]


# Overview of world suicide rates from 1985-2016

## Dataset:

From Kaggle: https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016

## result blog post:

https://medium.com/@lydiafz_Zoe/know-it-before-it-happens-potential-factors-associated-with-suicides-f8cd364de729

## Code:

Jupyter notebook.

## Questions and results summary:

In this prjoect, I aimed to explore the following questions using explorotary and visualization analysis:

1. How does the world suicide rates change across 30 years?

Take the suicides/100 k pop as the interested variable, I got the barplot of the mean suicide rates across 30 years.

2. Differences between females and males in suicide rates.

Create lineplot of mean suicide rates across 30 years for males and females respectively, and found that males show higher suicide rates than females.

3. How does the age affect suicide rates?

Create lineplot of mean suicide rates across 30 years by gender and age groups, and found 75+ years group shows the highest suicide rates. Also, males show higher suicide rates than females across all age groups.

4. Top 50 predictors of suicide rates.

Using sklearn to fit the linearregression model, I found that among the top 50 predictors, except males and 75+ years, all other predictors are countries.

