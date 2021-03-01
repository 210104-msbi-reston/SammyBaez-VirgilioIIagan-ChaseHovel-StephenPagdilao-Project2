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

1. To view how we used ETL in SSIS, navigate to SSIS Folder, open the NBA-SSIS folder and click on NBA-SSIS.sln to open our solution
2. If prompted with password, enter SqlCSVV123

 ![](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/Project%20Screenshots/SSIS%20Navigation.PNG)
 
 You will be presented with this screen where you can navigate our packages.
 
 ![](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/Project%20Screenshots/SSIS%20Solution.PNG)
 
 3. To view our SSAS Cube, click on SSAS folder, open Virgil-SSAS , then open NBA-Cube and finally click on NBA-Cube.sln to view our cube.
 
   ![](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/Project%20Screenshots/SSAS%20Navigation.PNG)
  
  You will be presented with this screen where you can explore our cube.
  
  ![](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/Project%20Screenshots/SSAS%20Cube.PNG)
  
  Within the cube you can explore the calculations and hierarchies that we created. 
  
  4. In the project screen shots folder you can see examples of our reports. Here are some examples.

   ![](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/Project%20Screenshots/%5BChase%5D%20Game%20Stats.png)
   ![](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/Project%20Screenshots/%5BSammy%5D%20PowerBI%20Player%20Statistical%20Contribution.PNG)
   ![](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/Project%20Screenshots/%5BStephen%5D%20PowerBI%20Player%20Statistics.png)
   ![](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/Project%20Screenshots/%5BVirgil%5D%20Wins%20Predictions.png)
   
  
  
  
   

## License

This project uses the following license: [MIT License](https://github.com/210104-msbi-reston/SammyBaez-VirgilioIIagan-ChaseHovel-StephenPagdilao-Project2/blob/main/LICENSE.txt).
