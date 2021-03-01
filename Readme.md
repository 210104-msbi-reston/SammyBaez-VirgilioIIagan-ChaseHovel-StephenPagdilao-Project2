# Basketbal Prediction and Analysis

## Project Description

The project aims to find meaningful statistics on NBA regular season historical data (about 16 years amount of data) such as average points a team makes per game or how many shots they make on average. Using this data, our project can make a number of predictions such as a team's chance of winning against another team, who might win the MVP award, etc. All values will be obtained by SSIS through Microsoft Excel, flat files, and/or web services to be stored onto MS SQL Server 2016. This data will then be analysed using SSAS. Finally, the data is processed using SSRS into easy-to-digest information.

## Technologies Used

- MS SQL Server - version 2016
- SQL Server Integration Service - Visual Studio 2017/2019
- SQL Server Analysis Service - Visual Studio 2017/2019
- SQL Server Reporting Service - Visual Studio 2017/2019
- MS ExcelBI
- MS PowerBI
- LogMeIn Hamachi

## Features

List of features

- Power BI and Excel BI report on Individual Overall Performance
- Power BI report on Individual Contribution to team performance.
- SSRS report on Team Performance
- SSRS report on Individual Performance
- SSRS report on Game Results
- SSRS report on predicted result of a game given the seasonal performance of two teams.
- SSRS report on predicted outcomes of a season
- Normalized Database on NBA statistics from 2003 to 2020.
- Multidimensional Cube of NBA statistics from 2003 to 2020 for faster querying.
- Data Mining Model on Predicting which team will will a given game.

To-do list:

- Incorporate more attributes for the data mining model to increase predictive capabilities.
- Use SQL Server Agent to automatically run SSIS packages to do some ETL processes on new NBA games.
- Incorporate more historical data from the start of the NBA.
- Create a data mining model to try to predict who will win the MVP award based on top performing players at the time and winner of the award.
- Predictive reports based on our data mining models.
- Host server on cloud
- Automatically update reports from live server
- Update some reports to add more interaction and useful information.
- Add detailed playoff predictions to see a teams chances of winning each individual round and their chances of winning the championship.

## Getting Started

1. Create a directory that will store the project data
2. Locate that directory in Git Bash
3. Type git clone https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2.git 
   (include all environment setup steps)

## Usage

> Here, you instruct other people on how to use your project after they’ve installed it. This would also be a good place to include screenshots of your project in action.

## License

This project uses the following license: [MIT License](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/LICENSE.txt).
