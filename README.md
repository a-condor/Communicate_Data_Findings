# Report on bike-sharing system in SF Bay area for February, 2019
## by Abdulafiz Musa


## Dataset

> This data set includes information about a bike-sharing system in greater San Francisco Bay area. It includes daily individual rides that occurred in the month of February, 2019. Data can be downloaded with https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv. No dictionary was needed for understanding this dataset.

> There are 16 columns and 183412 enteries for this individual bike rides. We have some columns with missing data.

> Only null values were dropped for certain exploration in this dataset.


## Summary of Findings

> Majority of the users are male. The users are prominently working class (1990s), we've got a number of old people too. Very few users share their bikes during each journey which are usually fewer ten thousands sec. suggesting it isn't for really long distances.

> There's an established majority of males using this system, however the variation between the subscribers and customers looked constant accross other categories. There is also a near equal distribution for the age groups too; they are majorly 1990s across the gender groups. Interestingly, there was no correlation between the distance traveled and the age of the users of the bike system. It has been show that majority of the users are subscribers; it's fun to have observed that either the customers didnt share their bikes on journeys or they just cant and only subscribers are able to do so.

> It's clearer that customers did not have the capacity to share their bikes. Depending on our ability to discern the take off and destination IDs, we can tell how long it wil take us to travel from one area to another; this could be dependent on how busy some areas are too.


## Key Insights for Presentation

> For the presentation, I focused on the distribution of the usage of this ride system by showing the durations often spent on each rides. I also noted if these durations are affected by age of users after observing the age of those who frequently use the system. I observed certain type of users - subscribers are able to share their bike on a particular ride while customers don't or can't. I used an heatmap as a prediction model to determine how long it would take one to travel from a particular station to another if one has an idea of the station IDs.