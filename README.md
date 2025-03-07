This repository contains the final product of my project for PSTAT131: Statistical Machine Learning. The goal of the project was to find a dataset of interest online and apply the machine larning techniques learned from the class. I sourced my dataset from Kaggle, a dataset about the sale of video games. Given the dataset contains observed variables (sales globally and across specific regions) the aim of the project was to create a variety of models and compare their predictive accuracy. 

Table of Contents of the Final Report:
1. Introduction

   a. Loading packages

2. Exploratory Data Analysis

   a. Missing Data

   b. Critic_Score

   c. Platform

   d. Correlation Matrix

   e. Critic_Score vs User_Score

3. Setting Up and Fitting the Models

   a. Collapsing categorical variables

   b. Splitting Data & Making Folds

   c. Making the Recipe

   d. Making Models and Workflow

   e. Training Tuned Models on Folds

   f. Finding the Best Parameter Values

   g. Autoplots for Tuned KNN, Random Forest, and Boosted Tree Models

   h. Further Exploring the Best Models

4. Testing the Models

   a. Variable Importance Plots

5. Conclusion

File Descriptions:
* DataMemo.Rmd: initial assignment for the project where we pitch our plan for the project and include some basic EDA of the data we sourced
* Extra.Rmd: contains extra code and analysis of elements which were left out of the final report
* Project.Rmd: final project file
* Video_Games.csv: data of video games sales, sourced from Kaggle
* game_data_codebook: describes the variables in Video_Games.csv
* rda files: data saved during the project to save computational cost
