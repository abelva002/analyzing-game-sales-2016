# Welcome to my Analyzing Game Sales (2016) Project
In this project, I explore a game sales dataset which contains various informations about games and their sales information. The full dataset is obtained from Kaggle, which can be downloaded here: https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings

The objective of this project is to find insight contained in the dataset and to create a Machine Learning that can predict the sales number of a video game from various features in the dataset. The insight could then be used to help make informed business decision while the Machine Learning model could be used to try to predict sales numbers that could also help in making business decision.

# Data Overview
The dataset is comprised of 15 rows with 16,719 entry.
Features included are as follows:

Name: Name of the game
Platform: Platform of the game
Year of Release: Release Year of the game
Genre: Main genre of the game
Publisher: Publisher of the game
NA Sales: Sales in North America territory
EU Sales: Sales in Europe territory
JP Sales: Sales in Japanese territory
Other Sales: Sales in Other territory
Global Sales: Sales in every territory
Critic Score: Aggregate of Critic Score given to a game
User Score: Aggregate of User Score given to a game
Critic Count: Number of Critics giving Score to a game
User Count: Number of Users giving Score to a game
Developer: Developer of the game
Rating: Rating of the game

# Modelling

The dataset is split into Training Data and Test Data with 80:20 ratio
Several Machine Learning model is used in this project namely: Decision Tree, Random Forest, and Gradient Boosted Tree
Evaluation metrics used are: Root Mean Square Error, Mean Absolute Error, and R2 Score
Further details can be obtained in the Python Notebook
