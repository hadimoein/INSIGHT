# INSIGHT

TORONTO MOVES - Summer 2019

Forecasting neighbourhood population economics

### Introduction
This project provides a data-driven tool for city of toronto to predict the migration of low-income population in different nighbourhoods. This tool helps the city management to plan business investments, and modify policies for cummunity development ahead of time for 2021. The web-app tool is available at https://insight-242021.appspot.com. 

### Data Source
There are three sources of data: 
1. Listing.ca (2001 to 2016) (Web-scraped) 
2. Census Data (2001 to 2016) 
3. Toronto-Wellbeing (2006 to 2014). 
The final data is available in the Data folder. 

### Data Analysis and modeling
Please refer to the Jupitor notebooks in the Modelling folder for the following topics:
1. PCA and Features engineering
2. Regression (Linear, Random Forest, NN) (Please refer to MVP_Reg_RF_V3.ipynb for the final model.)
3. Classification (Logestic Regression, Guassian Naive-Bayes, NN, RF, SVM)
4. Mapping Function


Following show the screenshots of the web-app. 
<p align="center">
  <img width="500" src="https://raw.githubusercontent.com/hadimoein/INSIGHT/master/Images/Image%202019-06-04%20at%2011.54%20AM.jpg"></img>
</p>

After choosing the desired neighbourhood from the drop-down menu, you click on the MAP button. The result will include the change in low-income population change in year 2021 for the chosen neighbourhood. 

<p align="center">
  <img width="500" src="https://raw.githubusercontent.com/hadimoein/INSIGHT/master/Images/Image%202019-05-31%20at%207.43%20AM.jpg"></img>
</p>
