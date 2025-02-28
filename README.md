# Project Name: COVID19-Data-Project

### Introduction
This is a practice file from the 30 Days of learning organized by Microsoft. Trying to work on my excel cleaning, transformation and visualization skills. 


--------
# Project Objective: Problem Statement
The purpose of this dataset is to do an exploring the global COVID19 dataset to obtain some meaningful  insights from it

## Project Objectives
The problems to be solved are:
* The top and bottom 5 countries with prevalence (Confirmed cases) of COVID19
* The top and bottom 5 countries with Death cases of COVID19
* Cumulative yearly and monthly confirmed cases
* Cumulative yearly and monthly death cases
* Cumulative confirmed cases, Death cases and death rate of COVID19
* Other analysis



--------------
# Data Sourcing
The data was gotten from @oyinbooke github page with respect to the 30 days of learning. Here is the link to the dataset ![click here](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data)
It contains three difeerent data for confirmed cases, death cases and recovered cases



-------------
# Data Transformation
* Data was scraped from github and imported into excel using powerquery, the source was edited in order to edit the number of columns out so the data can keep updating itself every day
* The data was imported as a wide data, it was then unpivoted into a long data so as to enable us view the data better. From the unpivoting, we got two new columns named date column and the value column containing the number of confirmed cases.
* The Other two sheets of death cases and recovered cases were scraped into excel using the same method as above and transformed from the wide data into a long data by unpivoting.
* The three tables were then merged together to give one table that was named the consolidated data
* It was then loaded into excel for further analysis.
* In excel, we extracted the Year, Month and day column using the year, text and day function 
![alt text](https://github.com/MariamAdekanye/COVID19-Data-Project/blob/main/2022-07-19%20(1).png)


# Data Analysis and Visuals
The data was analysed using the pivot table in excel.
## Analysis of Confirmed  cases
![alt text](https://github.com/MariamAdekanye/COVID19-Data-Project/blob/main/2022-07-19%20(2).png)


It was then visualized using the pivot chart in excel 
![alt text](https://github.com/MariamAdekanye/COVID19-Data-Project/blob/main/2022-07-19%20(4).png)

![alt text](https://github.com/MariamAdekanye/COVID19-Data-Project/blob/main/2022-07-19%20(5).png)

## Analysis of Death  cases
![alt text](https://github.com/MariamAdekanye/COVID19-Data-Project/blob/main/2022-07-19%20(6).png)


It was then visualized using the pivot chart in excel 
![alt text](https://github.com/MariamAdekanye/COVID19-Data-Project/blob/main/2022-07-19%20(7).png)


![image](https://user-images.githubusercontent.com/96249899/179721223-93ced50c-82b7-4c08-9f3a-08035acf3ea9.png)

* 

-----------
# Findings 
From the dashboard, 
* The number of confirmed cases is far more that the death cases, thus the death rate is 1.70%
* It is noted that US has the most prevalence of both confirmed and death cases.
* The confirmed cases gradually increased from the year 2020 with high prevalence in 2022
* During the first half of the year, there are more confirmed cases
* The least country affected is North Korea
* There are some countries that are yet to have any record of death cases such as Antarctica, Holy See, Marshall Islands and Micronesia

# Reccommendation
* Vaccines should be introduced to countries with high prevalence of Covid19
* The should be sensitized about precautionary measures to take in order to stay safe and manage it well.

