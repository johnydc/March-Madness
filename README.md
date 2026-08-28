# CMSE401 Project - March Madness
Every year, tens of millions of brackets are filled across multiple platforms trying to perfectly predict the NCAA Division I Men's Basketball Tournament, also known as March Madness. The odds of filling out a perfect bracket by flipping a coin for each game, you would have 1 in quintillion odds of correctly predicting the winner of all 63 games in the tournament. But not each game is necessarily a 50/50 matchup. The National Collegiate Athletic Association created a weighted model that calculated the average accuracy of a user, taking into account seed differential and matchup frequency, giving a weighted accuracy that better encompasses the predictability of each game regardless of the teams. Even with this improved accuracy, the odds of filling out a perfect bracket is 1 in 120.2 billion! On top of that, the top performers of the bracket challenge average around 50 games correctly predicted (~80%) throughout the entire tournament.

## Overview
This project uses a public dataset on Kaggle, that includes complete team statistics of every school in NCAA Division I Men's Basketball from 2013-2025. The data will be fed into a machine learning model to explore if a machine learning model is capable of outperforming the average, and top-performing human when it comes to predicting March Madness.

## Data

### Raw Data
The raw, pre-processed data downloaded from Kaggle can be found in the `data/` folder under the file name `og_cbb.csv`

### Processed Data
The updated, processed data can also be found in the `data/` folder under the file name `cbb.csv`
  - Added the `Region` for each team in the tournament
  - Removed all the `R68` values (First Four games); verifying whether or not the team made the 64 team pool
