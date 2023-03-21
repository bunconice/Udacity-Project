# Exploration of Ford GoBike System Data

## by Bunmi Akinola


## Dataset

>There are 174952 rows in the dataset with 15 features; duration_sec, start station_id, start_station_name, end_station_id, end_station_name, bike id, user type, start day, member gender, bike share, age, age group, start hour, start day, end hour, end day.
>I did some data wrangling which included dropping rows with missing data for start station id, start station name, end station id, end station name,member birth year, member gender columns. i converted columns data type, added new columns for age, age groups, start hour, start day, end hour, end day. Finally i dropped columns that were not needed.

## Summary of Findings

> In the exploration, i found out that most rides were taken on Tuesday and Thursday.The market station at 10th st is the busiest of all stations because over 3500 rides were taken there. Subscribers took relatively higher amount of rides. Most rides were not shared. Out of all the members gender, the male took significantly high amount of rides. Most rides were taken at the 8th and 9th hour in the morning when people leave for work and at the 17th and 18th hour in the evening when when they close from work. Rides on saturday and sunday takes longer duration as compared to other weekdays. Bike share does not influence the duration of rides. The user type influences the duration of rides. Rides on the work free days(saturday and sunday) takes longer duration. Among the genders, the male gender shared the most ride. Also other gender took most rides. The duration of rides taken by other gender each day is significantly higher than the male and female. Age has no significant effect on hours of ride

## Key Insights for Presentation
.
> For thr presentation, i focused on figuring out when are most trips are taken in terms of hour and day of the week, followed by  the user type influence on the duration of the trip among many others