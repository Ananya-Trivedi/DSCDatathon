# DSCDatathon

A combination of 3 datasets was used to merge into a single, cleaned and more useful dataset using R (see DSCDatathon 2\merged.csv in the attached GitHub files)

## Links to the datasets used
Obesity dataset: https://apps.who.int/gho/data/node.main.A900A?lang=en <br />
CO2 emissions dataset: https://www.kaggle.com/kkhandekar/co2-emissions-1960-2018 <br />
GDP/capita dataset: https://www.kaggle.com/nitishabharathi/gdp-per-capita-all-countries <br />
**For the set-up, please scroll down to the bottom of this README.md file**

The rapid climate change and increasing obesity rates are two significant concerns for policy makers around the world. We aim to determine if climate change, in particular increasing CO2 emissions, be a driver for the global obesity rates. At first it might seem like CO2 and obesity rates are completely unrelated. However, on analyzing trends including the countries' GDP per capita and the meat consumption/production frequencies, we were able to understand why there is an underlying relationship.


## Data Analysis and Methodology 
For the purpose of this project, 3 primary data sets were used; global CO2 emissions, prevalence of obesity among adults and the GDP per capita, with all values categorized based on countries. For purposes of data cleaning, processing and plotting, we decided to use R as a programming language since it was common in the team-members' skill-set.

We chose to take the regression route since we were more focussed on the gathering, cleaning and processing big-data rather than machine learning. In the future, however, we can employ machine learning models to provide an estimated value from predictive features with the same datasets. For instance, if policy makers were to implement caps on how much CO2 emissions a nation is allowed to produce annually. A machine-learning predictive model will be extremely useful in this case as it might give us predictions of limits on meat production and other industries (which will inturn curb the national CO2 emissions)


## Conclusion
Based on our findings, there was a clear positive relationship between the GDP per capita, global CO2 emissions and the obesity rates throughout all countries. Although we cannot establish a clear causative relationship between the two, we were able to identify possible factors that played a role. 

The following observations and inferences were made:
1. The GDP per capita also had a positive relationship with the CO2 emmissions and obesity levels.
2. An increase in the global CO2 levels was liked to an increase in the prevalence of obesity worldwide.


## Setting up the environment for reproducability
Our code is in the form of an RMarkdown File. In order to reproduce the code, all you really need is the .zip file with the 3 datasets we used and the .rmd file (uploaded onto GitHub).

You will, however, need to edit the root folder in the commands that import the datasets (or you can go into RStudio, navigate to File-> Import Dataset to import the 3 datasets and then you can ignore the following code block in the .rmd file)
