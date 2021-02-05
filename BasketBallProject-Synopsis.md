# Fantasy Basketball Predictions and Analysis

## Description
Our project aims to finding meaningful statistics on NBA regular season historical data (about 16 years amount of data) such as average points they get per game, how many shots did they make on average, or a prediction of their chance of winning compared to a specific team, etc. All values will be obtained by SSIS through excel, flat files, and/or web services and analyzed by SSAS and delivered by SSRS in easy to digest information and all data will be stored in MS SQL Server 2016

## Automation
1. Fitler data from downloaded [.CSV files](https://www.kaggle.com/nathanlauga/nba-games?select=players.csv)
2. Data processing: 
   * Finding relationships between .CSV files
   * Removing null rows and exception handling to log it to a table
   * Transformation of data and mapping columns to a centralized database
3. Search and data scrap specific NBA player's overall statistics based on player name
4. Search and data scrap each NBA player's statistics in a single team based on team name
5. Search and data scrap specific NBA player's statistics in a specific year or a range of years
6. Search and data scrap specific NBA player's statistics in a specific game
7. Search and data scrap specific game statistics based on 
## Tech Stack
* Microsoft SQL Server 2016
* SSIS
* SSAS
* SSRS

## Team
* Chase Hovel
* Stephen Pagdilao
* Sammy Baez
* Virgilio Ilagan
 
