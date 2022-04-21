# About
 
Online gaming is 1 of the fastest growing form of sports due to advancements in our technology, it is affectionately known as e-Sports. Our team looked into the potential of having players/summoners understand their in-game performances and understand their winning conditions. We created a model and visualization that correlates their data and predict their winning conditions using a Decision Tree and random forest classification model.
 
# Background
 
The growth of eSports globally, with 1 of its biggest game, League of Legends, lead to players wanting to improve their game play. League of Legends, more affectionately called LoL, introduced a ranking system where their game data are considered and then are classified based on their performance to a certain rank, based on a 5 games played in a Rank Game feature of LoL. With summoners always intending to play better and improve their game play, and understanding the game data is not always the simplest to cater for. So being able to determine the factors that cause your win condition, and help understand their game play data better, can assist in their growth in game. Which therefore can help lead to them ranking up and understanding on game mechanics and conditions that are important to win.
 
# Technologies:
 
Python/Pandas/riotwatcher
Google Colab
Tableau
Correlation Matrix
 
# Approach
 
Identify data sources and dependencies
Perform EDA, determine feature set and transform player data
Compile, train and evaluate the model
Compare models for optimization of accuracy metric
Iterate on models
Load model on Random Forest and Decision Tree
Visualize dashboard in Tableau
 
# Data Source

Data was collected from match histories of players obtained through RiotApi
 
Link: https://developer.riotgames.com/apis
 
# Preprocessing
 
Perfomed ETL on the data pulled from RiotApi
Split the preprocessed data into training and testing sets
Created dummy variable
Compiling, Training and Evaluating the Models
Evaluated models: Decision Tree Classifier, Random Forest Classiifier, KNN, Logistic Regression and Neural Network.
Evaluated feature performance
 
# Using the Model
 
Tableau dashboard was used to help visualize the data models and compare the results of the models

# Visualization

Link: https://public.tableau.com/app/profile/ramon.faylona/viz/Lol-Proj4/Story1
 
# Limitations
 
Limited time of project
Data  Variety
 
# Next Steps
Evaluate further feautures, weight features, or consider placing on a live website
Enable user input to continue to train our model 
Consider potential bias in our data, especially related to demographic features
 
# Contributors
 
Christine Li
Ludan Zhang
Ryan Apolonio
Ramon Faylona
