

<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

#  Project 1: Local Traffic, Statistical Summaries and Inference

This project will take a look at the Kingdom of Saudi Arabia traffic reports including accidents, driving license issuing and some outside data that might be relevant. The goal is to try and find correlations and provide solutions and answers if needed for problems that might occur.

## Datasets
-   [Traffic Accidents and Casualties by Region](https://git.generalassemb.ly/DSI-MISK-VI/Project1/blob/master/data/saudi-arabia-traffic-accidents-2008.csv)
-   [Driving Licenses Issued By Administrative Area](https://git.generalassemb.ly/DSI-MISK-VI/Project1/blob/master/data/saudi-arabia-driving-licenses-2004-2008.csv)
-   [Car Plates Issued by Year and Type](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-car-plates-issued-in-the-kingdom-by-type-2004-2008/information/?disjunctive.type)
-   [Population by Administrative Area](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-population-by-administrative-region-nationality-and-sex/information/?disjunctive.administrative_region&disjunctive.gender)
-	[Population by Administrative Area 2018](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/information/?disjunctive.region&disjunctive.indicator&sort=time_period)
-	[Driving Licenses Issued By Administrative Area  2018](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008/information/?disjunctive.administritive_area&sort=time_period)
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

-	Download the CSV files by clicking on the highlighted links in the datasets section
-	If you do not have python installed, download Anaconda to be able to use jupyter
- Finally, you can fork the project or download it as a zip file
### What was done:
- Data Cleaning
- Data Formatting
- Data Grouping
- Data Visualization

### Data Dictionaries
|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Saudi Arabia Traffic Accidents 2008|The year in which an accident occurred|
|region|object|Saudi Arabia Traffic Accidents 2008|The region in which an accident occurred|
|accidents|int|Saudi Arabia Traffic Accidents 2008|The accident number|
|x|float|Saudi Arabia Traffic Accidents 2008|The x coordinate of the accident|
|y|float|Saudi Arabia Traffic Accidents 2008|The y coordinate of the accident|
|Casualties|object|Saudi Arabia Traffic Accidents 2008|The casualty degree of the accident|


|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Saudi Arabia Driving Licenses 2004 2008|The year of issuing the license|
|region|object|Saudi Arabia Driving Licenses 2004 2008|The region of issuing the license|
|driving_licenses|int|Saudi Arabia Driving Licenses 2004 2008|The issuing number|
|x|float|Saudi Arabia Driving Licenses 2004 2008|The x coordinate of the issuing location|
|y|float|Saudi Arabia Driving Licenses 2004 2008|The y coordinate of the issuing location|



|Feature|Type|Dataset|Description|
|---|---|---|---|
|Year|int|Car Plates Issued by Year and Type|The year of issuing the car plate|
|Type|object|Car Plates Issued by Year and Type|The type of vehicle|
|car_plates|int|Car Plates Issued by Year and Type|The number of issued car plates|



|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Population by Administrative Area|The year the data for population|
|region|object|Population by Administrative Area|The region of the population|
|gender|object|Car Population by Administrative Area|The gender of the population|
|population|int|Population by Administrative Area|The population of people in a region based on gender and year|


The data for 2018 are exactly the same as:
-	Traffic Accidents and Casualties by Region
-	Driving Licenses Issued By Administrative Area

## A Blog that was created for this project:
-	https://medium.com/@ghalib_tawfiq/saudi-arabia-traffic-accidents-driving-licenses-hidden-factors-4acd9615d64c
### References:
- https://datasource.kapsarc.org/explore/dataset/saudi-arabia-population-by-administrative-region-nationality-and-sex/information/?disjunctive.administrative_region&disjunctive.gender
- https://datasource.kapsarc.org/explore/dataset/saudi-arabia-car-plates-issued-in-the-kingdom-by-type-2004-2008/information/?disjunctive.type
- https://datasource.kapsarc.org/explore/dataset/saudi-population-10-years-and-over-by-gender-age-groups-and-educational-status/information/?disjunctive.sex&disjunctive.age_group&disjunctive.educational_status
- https://english.alarabiya.net/en/features/2019/06/24/One-year-on-Saudi-women-say-driving-has-steered-their-lives-for-the-better.html


### Project Completed by Ghalib Tawfiq - DSI7
