
# EDA US Car Accidents 2016-2021

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

An exploratory Data Analysis of a dataset with car accidents 
records in the US from 2016 to 2021.





## Dataset origin and breif description

The dataset was obtained from Kaggle: 
https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents. 

It contains data collected from February 2016 to Dec 2021, 
using multiple APIs that provide streaming traffic incident (or event) data. 
It's a car accident data set which covers 49 states of the United States of America 
(excluding NY) collected from February 2016 to Dec 2021.

The dataset cointains 47 variables different variables and 2,845,342 rows.





## Summary

A total of 16 columns was analyzed.
* Weather condition
* Astronomical_Twilight
* All the POI annotations (Amenity, Bump, Crossing, Give_Way, Junction, No_Exit, Railway, Roundabout, Station, Stop, Traffic_Calming, Traffic_Signal, Turning_Loop)
* Description

### Weather condition

![Weather](https://github.com/MaxPower14/EDA-US-Car-Accidents_2016-2021/blob/main/images/weather.png?raw=true)

### Astronomical_Twilight

![Twilight](https://github.com/MaxPower14/EDA-US-Car-Accidents_2016-2021/blob/main/images/astronomical.png?raw=true)


### POI annotations

![POI](https://github.com/MaxPower14/EDA-US-Car-Accidents_2016-2021/blob/main/images/poi.png?raw=true)

### Severity by weather condition

![severity](https://github.com/MaxPower14/EDA-US-Car-Accidents_2016-2021/blob/main/images/severity.png?raw=true)

### Description WordCloud

![description](https://github.com/MaxPower14/EDA-US-Car-Accidents_2016-2021/blob/main/images/wordcloud.png?raw=true)

## Conclusions

* 76% of the accidents occur on fairly normal weather conditions (Fair, Mostly Cloudy, Cloudy, Partly Cloudy, Clear).
* % of the accident occur during the day
* Only 26% of the accidents occured close to any of the road elements considered.
* Junctions are the road element where occur more accidents with 9.9%
* Severity 2 is the most recurrent with 89% of the accidents.
* Accidents with bad weather doesn't have a higher severity.
* Accidents are not more frequent on bad weather conditions.
* From the description wordcloud we learned that:
* The U.S. Route 101, Interstate 95 and Interstate 10 are involved in quite some accidents.
* Parkways, Highways, Freeways, Road exits, Avenue exits are involved in quite some accidents.
## Limitations and future work

* Enrich the analysis by considering more columns like Start_Time, City, and Street.
* Imputate the missing values of the columns already analyzed considering data from other columns:
* Weather condition: By checking the other weather variables like Precipitation
* Astronomical_Twilight: By checking the time of the accident and its coordinates.
* Find out the most recurrent roads, cities and states.