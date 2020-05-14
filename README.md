# Data Science for Economic Development

For my senior thesis, I plan to explore how we can apply big data and machine learning techniques to the field of development economics. Using data to better understand existing economic problems can help contribute to plans to solve these problems, and my goal is to apply data science techniques to a large household survey dataset to see if these techniques produce significant and accurate results. 

This repository will be updated throughout the year as I conduct my research.

## Dependencies
- [causal-tree-learn 2.31](https://pypi.org/project/causal-tree-learn/)

## Data Description

The Young Lives surveys tracked the lives of 12,000 children over 15 years. There were five rounds of surveys conducted on two groups of children. In the first round, the children in the younger group were age 1 while children in the older group were age 5. In the second round they were 5 years old and 12 years old, in the third round they were 7-8 years old and 14-15 years old, in the fourth round they were 12 and 19 years old, and in the last round, they were 15 and 22 years old. 

Ethiopia dataset: 2999 children at each of the 5 rounds, 14995 data points overall. 214 variables, which include panel information, general characteristics, household characteristics, and child characteristics. 

Important features: Child-health related variables, Caregiver education level, Household descriptors (Housing quality index, Consumer durables index, access to drinking water, access to sanitation, access to electricity, access to adequate fuels for cooking), Shocks (ex. Theft, eviction, death in family, job loss, etc.)

Outcome variables: Vocab test scores, Math scores, Reading scores

The data from the Young Lives study is available through the UK Data Service, and through their portal, I have been able to download the original data from the study as well as a dataset that combines all the survey data specifically for Ethiopia. The downloaded data comes with data dictionaries that describe the different features and their values. The Ethiopia dataset contains data for 2999 children at each of the 5 rounds, so it has 14995 data points overall. This dataset contains 214 variables, which include panel information, general characteristics, household characteristics, and child characteristics. 

