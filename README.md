# PUBG Game Prediction
In a PUBG game, up to 100 players start in each match (matchId) and in this project we will be targeting the percentile winning placement of the players using machine learning techniques.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Usage](#usage)
* [Contact](#contact)

## General Information
In this challenge, we will use a dataset of PUBG game players to predict the winPlacePerc which is a percentile winning placement, where 1 corresponds to 1st place, and 0 corresponds to last place in thebased on its features. The price-per-unit in this data is based on a unit measurement of 3.3 square meters.

The data is part of a Kaggle competition which has scraped 65000 games worth of data using an API. The goal is to predict the win percentage of the player based on 28 given features. For example, in a solo game of 100 players if a player got rank of 80, then its winPlacePerc will be (100-80)/(100-1)=0.204 using the formula winPlacePerc = (maxPlace-winPlace)/(maxPlace-1). The problem is then essentially a regression problem to predict the winPlacePerc of the player between [0,1]. These types of problems are solved by doing extensive exploratory data analysis and feature engineering before applying a regression model. 

We gained insights in the features and added new relevant features by exploring the game and the semantics of the features. We were provided with the Training Dataset so we devided it into Training and Validation Dataset in 70 and 30 ratio respectively.

## Technologies Used
- Python 3.11.1

## Setup
Before getting started with the project you need to familiar with machine learning and especially some kinds of regression algoritm and you need to download our "PUBG_Game_Prediction_data.csv" file provided in this project also. 

## Usage
Anyone curious about PUBG game or trying to figure out some details about PUBG Game based on varous features may use this project as a template. Beyond this project, you can use some other machine learning techniques too and compare your results with the results shown in this project.

## Contact
Created by [@serdbay](https://github.com/serdbay) - feel free to contact me!
