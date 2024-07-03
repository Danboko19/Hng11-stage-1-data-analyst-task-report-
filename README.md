# Hng11-stage-1-data-analyst-task-report
## Introduction 
This dataset shows the result of the 2023 election held Nigeria in Feb 23rd 2023 by the Nigeria Inec, It's a total of and 471 records. It's consist of the result of the parties including the pu_unit_code and addresses. 
## Purpose of Analyses
1. To determine the irregularities in the election.
2. To discovered the most irregular locations in the state
## Methodology
Since the dataset only have addresses and not latitude and longitude. I have to get the geographical location of all the polling unit! So this was done by using python API Geopy.
So at first I imported and my data and generated the latitude and longitude of the each location with this code.

And I've this result. 
Then I generated outliers and then determine the close poling unit with one another with a proximity radius of 5km.
The following code were used inother to achieved this
## Result of the analysis
After determining the polling unit close to one another. I used my generated result to the determine the top three outliers which are the top irregularities in the entire state. 
Which are   as shown in the illustration below;
## Conclusions
2023 election in calabar was a fair and free election with less irregularities but some location didn't go well, which not possible to not witness such a things. 
To learn more about coding and data analysis visit the following link:
