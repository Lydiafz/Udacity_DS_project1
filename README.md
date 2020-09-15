# Overview of world suicide rates from 1985-2016

# Table of Contents

1. [Installation](#instal)

2. [Project Motivation](#motive)

3. [Research questions](#topic)

4. [File Descriptions](#files)

5. [Results](#Results)

6. [Licensing, Authors, and Acknowledgements](#terms)

<a name = "install"></a>
## Installation
All the analysis were done using jupyter notebook implemented in Anaconda (python 3). No special toolbox needs be installed. Sklearn was used for the linearRegression model fit.

<a name = "motive"></a>

## Project Motivation

As a researcher in human cognitive neuroscience field, we are digging the deep brain mechanism of suicide, and we are trying to find ways to predict and prevent suicides. However, besides underlying neural correlates, there are some explicit factors linked to suicide rates, such as gender, age, culture etc. An overview and exploratory analysis on these potential factors will help us predict and implement effective interventions at population, sub-population and individual levels to prevent suicides and suicides attempts. Also, I believe this project is a good practice for my Data Science learning.

<a name = "topic"></a>

## Research questions
This project aims to explore the potential factors that might be associated with suicide. In this project, I am intereted in the following questions:
- How does the world suicide rates change across 30 years?
- Differences between females and males in suicide rates.
- How does the age affect suicide rates?
- Is there any relationship between suicide rates and other numerical variable?
- Which factors are the best predictors of suicide rates?

<a name = "file"></a>

## File Descriptions

### Dataset:

The dataset is dataset of suicide rates overview 1985 to 2016 provided by Kaggle,

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

