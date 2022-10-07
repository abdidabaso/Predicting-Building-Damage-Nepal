# Predicting-Building-Damage-Nepal
In this project, data was collected from querying a SQL database. Data was explored and cleaned to build a classification model to predict building damage for the district of Kavrepalanchok. • Wrote a wrangle function that create a “severe_damage” column, where all buildings with a damage grade greater than 3 should be encoded as 1. All other buildings should be encoded at 0, drop any columns that could cause issues with leakage or multicollinearity in your model.

Used seaborn to create a boxplot that shows relationship between the footprint size of a building and the damage it sustained in the earthquake
Created a logistic regression model to predict building damage using an appropriate encoder for categorical features.
Built a decision tree model that perform better than logistic regression.