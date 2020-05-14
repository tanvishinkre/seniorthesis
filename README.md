# Data Science for Economic Development

Education is widely recognized as an important factor in stimulating growth and addressing widespread poverty in developing countries. While universal access to education is a first step, the quality and impact of this education is also important. In recent years, global priorities have shifted from ensuring “access for all” to ensuring “basic skills for all”. Recent studies have shown that a child’s home situation can affect their learning, and thus prevent them from gaining these basic skills. For my senior thesis, I explored how a household shock like death of livestock can impact a child’s performance in school, and compared the efficacy of different analytical methodologies in understanding causal effect. I compared the methodologies of multivariate regression, the Rubin causal model, propensity score matching, and causal trees in evaluating the impact of the shock of death of livestock on children’s school performance. While each of these methods estimates treatment effect differently, all of the results indicate that the investigated shock has a negative impact on children’s school performance.

## Dependencies
- [Python 3](https://www.python.org/)
- [Jupyter](https://jupyter.org/)
- [Anaconda](https://www.anaconda.com/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Scikit-Learn](https://scikit-learn.org/stable/index.html)
- [causal-tree-learn 2.31](https://pypi.org/project/causal-tree-learn/)

## Data Description

The Young Lives surveys tracked the lives of 12,000 children over 15 years. There were five rounds of surveys conducted on two groups of children. In the first round, the children in the younger group were age 1 while children in the older group were age 5. In the second round they were 5 years old and 12 years old, in the third round they were 7-8 years old and 14-15 years old, in the fourth round they were 12 and 19 years old, and in the last round, they were 15 and 22 years old. 

Ethiopia dataset: 2999 children at each of the 5 rounds, 14995 data points overall. 214 variables, which include panel information, general characteristics, household characteristics, and child characteristics. 

Important features: Child-health related variables, Caregiver education level, Household descriptors (Housing quality index, Consumer durables index, access to drinking water, access to sanitation, access to electricity, access to adequate fuels for cooking), Shocks (ex. Theft, eviction, death in family, job loss, etc.)

Outcome variable: Vocab test scores

The data from the Young Lives study is available through the UK Data Service, and through their portal, I have been able to download the original data from the study as well as a dataset that combines all the survey data specifically for Ethiopia. The downloaded data comes with data dictionaries that describe the different features and their values. The Ethiopia dataset contains data for 2999 children at each of the 5 rounds, so it has 14995 data points overall. This dataset contains 214 variables, which include panel information, general characteristics, household characteristics, and child characteristics. 

