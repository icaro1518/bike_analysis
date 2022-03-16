# Part I - Exploring Ford GoBike System Data
## by Heiler Santiago Gómez Prieto


## Dataset

> The Ford GoBike System Data dataset contains information on bicycle trips made as part of the Ford GoBike program. This dataset includes travel information in terms of
* Location (Start and end points)
* Service duration
* Client identification (Sex, Birth year, Bike share for all trip)


## Summary of Findings

>With the data provided we have a series of interesting insights about the operation of the program. 

>In the first place, we can review the duration of the tours, where the distribution of these durations presents a log-normal behavior. These durations present a relationship with the age of the user, the older, the shorter the duration of the trips, and vice versa; in addition to having a certain relationship with the sex of the people and with the days of the week, where we see that weekends have longer durations than trips during the week. 

>On the other hand, associated with the characteristics of the times in which the trips are made, there is a certain weekly seasonality in the number of trips that are made per day, since in general, on weekends there are fewer trips than on weekends. weekday. 

>In addition, there is a quite interesting relationship between the number of trips made and the time of day, where the largest number of trips coincides precisely with what is usually the "rush hour" in the offices (arrival and departure times | 8 and 17)

>Finally, we have a very interesting component in how the location affects the number of trips made from each station, finding that we can separate the stations into 3 zones, each with more or less total number of trips in their stations.


## Key Insights for Presentation

> The trip duration depends on many factors as user sex, user age and user type. This implies that it is necessary to take into account the entire panorama to understand what can affect these times.
>The number of trips that are made in the program depends mainly on things such as the location of the stations and the day/time in which the trips are made, since it is very dependent on the needs of the population near the stations of the program. (need to move close to your area of residence or in rush hours)