# Titanic-Data-EDA
Titanic Dataset Exploratory Data Analysis (EDA) Project
# Overview

This GitHub repository contains an Exploratory Data Analysis (EDA) project on the Titanic dataset. The project aims to understand, interpret, and analyze various aspects of the dataset, including its columns, univariate and bivariate analyses, and key insights derived from the data.

In this Exploratory Data Analysis (EDA) project, we delved into the Titanic dataset to gain insights into the tragic events surrounding the sinking of the Titanic. Through a thorough examination of the dataset columns, univariate analysis, bivariate analysis, and feature engineering, we uncovered several key findings that shed light on the passengers and their experiences on that ill-fated voyage

**Dataset Columns:**

You have explored various columns in the dataset, including Age, Fare, Survived, Pclass, Sex, SibSp, and Parch

**Age Analysis:**

The mean age of passengers is 29 years with a standard deviation of 14.52.
Ages are mostly between 18 to 38, indicating a concentration in that range.
The minimum age of 0.42 suggests the presence of children.
Age distribution appears to be almost normally distributed.
20% of the passenger ages are missing.
There are some outliers in the age data.

**Fare Analysis:**

The average ticket price (fare) is $32.
Some fares are recorded as 0, indicating potential data errors.
The maximum fare is $512, which appears to be an extreme outlier.
It is noted that some fares represent group fares, not individual fares.

**Survived Analysis:**

Only 38.4% of passengers survived, indicating that the incident was deadly, with over 61.6% not surviving.

**Pclass Analysis:**

More people traveled in Pclass 3.
Further investigation is needed to understand why more people chose this class, possibly by examining fare data.

**Sex Analysis:**

The Sex column does not have missing values.
There are more male passengers than female passengers.

**SibSp and Parch Analysis:**

Most passengers were traveling alone (SibSp = 0).
Many passengers had parents and/or children with them (Parch > 0).

**Bivariate Analysis:**

Questions about survival rates based on Pclass, gender, age groups, and family size have been explored.
Some notable findings include higher survival rates for passengers in Pclass 1, females, and children aged 0 to 5.

**Feature Engineering:**

You've suggested creating a fare column for individual passengers.
Merging the train and test datasets for further analysis.
Created family size bins and family type categories (alone, small, large).
Investigating titles in passenger names and finding that "Miss" titles had a higher survival rate.
Exploring cabin names and potential correlations with deck location for survival.


_This description provides a concise overview of your Titanic dataset EDA project, highlighting key findings and the structure of your GitHub repository. You can customize it further to suit your repository's style and purpose._
