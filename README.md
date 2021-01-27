# Project 2 - Ames Housing Data and Kaggle Challenge

**Problem Statement**
To create a model that would help home-owners find the best possible way to renovate their house in order to create the largest amount of home value increase in Ames, Iowa. 

## Model 

The data used in this model was taken from Ames, Iowa Assessor's Office and contained housing sold data from 2006-2010. The data contained a total of 82 variables and 2930 observations. 

The data documentation can been found at:
http://jse.amstat.org/v19n3/decock/DataDocumentation.txt
## The Modeling Process
Throughout the modeling process of creating my best model, I went through several different types of models; 7 specifically before I was confident with my results. My models ranged from having very few descrete vaiables to having multiple different catagorical variables(that were dummified) and descrete variables. One of the main ways I began each one of my models was to begin with finding corrlations with my data that relates to the Sale Price of the home.

## Major Findings 
Throught the modeling process I had found major findings in what affacts house data in Ames, Iowa. Some of the major factors i found that greatly affect housing are:
The size of the houses lot 
How much of the lot is on a road
The overall Sqft of the home
If there is a garage and how large it is
If there is a basement and the quality of it
How highly rated the kitchen is
The overall condition of the home
The overall condition of the exterior of the home

## Conclusions 
Knowing that not all of parts of a house can be renovated easily (ie. increasing house Sqft,building a garage,ect); I found that the best areas to renovate a house would be to make sure to have a finished basement. If one does not have a finsihed basement then the next best recommndation would be to increase the rating of a kitchen; such as getting new applance and updating the kitchen. If these recommendations were to be used then a home owerner shoudl be able to see an increase in home value with a ~81% confidence (R^2)

