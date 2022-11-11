# Predicting Fifa 19 overall score of players

## Introduction 
The aim of this project is to compare and study the different optimization techniques for linear regression on a medium scale dataset. 

The file "data.csv" includes FIFA 2019 players attributes. Some of them are "real life" attributes:
Age, Nationality, Club, Value, Wage, Preferred Foot, International Reputation, Weak Foot, Skill Moves, Work Rate, Position, Jersey Number, Joined, Loaned From, Contract Valid Until, Height, Weight, Release Clause. Others are game attributes given by FIFA 19.

The attributes can be either numerical or categorical. We will use these attributes to predict the "Overall" by regression. The bigger is the overall, the better must be the player in the game.

The dataset contains 18207 rows for 88 features and can be found [here](https://www.kaggle.com/nitindatta/fifa-in-depth-analysis-with-linear-regression/data) on Kaggle. Some parts of the work on the dataset is derived from this [notebook](https://www.kaggle.com/nitindatta/fifa-in-depth-analysis-with-linear-regression/notebook).

## Conclusions

We can see  in the following figure that linear regression performs well for the prediction of overall score ... ![regression](https://user-images.githubusercontent.com/45072645/201325842-ed3d82c6-222d-4d30-b178-863212f278ad.png)

... and that Stochastic Gradient Descent converges faster than other descent algorithms.
![descent](https://user-images.githubusercontent.com/45072645/201326004-51d9b66f-1ac2-413d-9909-c145f5ec68e9.png)


